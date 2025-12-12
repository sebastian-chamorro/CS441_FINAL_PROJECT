## Zero-Shot Sports Event Categorization
This project uses a Multi-Layer Perceptron to classify unseen sports events into one 
of five categories (Offensive, Defensive, Error, Transition, Neutral) to help individuals
become more familiar with new sports lingo in various settings from watching to playing sports.

## How to Run Demo (Google Colab)
1. Upload `CSS441_Final_Project.ipynb` code to your google drive
2. Upload sports_events.csv to your google drive in specified path: `/content/drive/MyDrive/CS441_Final_Project/`
3. Install dependencies if not already present: `pip install torch numpy pandas scikit-learn matplotlib seaborn gradio`
4. Run google colab cells sequentially
5. Final cell launches interactive Gradio App for live zero-shot testing

### Model Architecture
Used model:
* Multi-Layer Perceptron

Baseline Models used for comparison:
* Logistic Regression
* Linear SVM
### Methods of Quantitative Evidence
* Best validation accuracy for choosing best MLP model
* Average and standard deviation of test accuracy
* Best single-run test accuracy for choosing best model
### Methods of Qualitative Evidence
* PCA Clustering
* Nearest-Neighbors
### Feature Engineering
* Word Embeddings
* IDF Weighting