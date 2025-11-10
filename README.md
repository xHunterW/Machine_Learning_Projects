# Machine Learning Projects
A curated collection of data science and machine learning projects.  
Each notebook explores a different technique, from classical supervised models and clustering to evolutionary algorithms, NLP, and dimensionality reduction, with reproducible workflows and visual analyses.

---

## Project Index

### [Imputation Algorithm Comparison](./Imputation_Algorithm_Comparison)
This Jupyter notebook examines the use of *k-Nearest Neighbors* and *Regression* as algorithms for missing-data imputation in the **Titanic dataset** (Kaggle). kNN imputes missing Cabin numbers, and regression predicts missing ages. Both are validated and tested in downstream models.

---

### [Pre-trained Model Hub Comparison](./Pre-trained_Model_Hub_Comparison)
Compares lightweight pretrained models across hubs for NLP (IMDb) and CV (CIFAR-10): **Hugging Face**, **PyTorch Hub**, **TF Hub**, and a scikit-learn baseline. Standardized preprocessing, fixed budgets, linear-probe vs light fine-tune. Reports F1 and F1/min with Apple-silicon tips.

---

### [Unsupervised Learning for Dimensionality Reduction](./Unsupervised_Learning_for_Dimensionality_Reduction)
Analyzes the performance of **PCA** versus an **autoencoder** for dimensionality reduction. Both techniques are compared using KMeans and DBSCAN clustering, evaluated via within-cluster metrics and classification accuracy to assess representation quality and separability.

---

### [Supervised and Unsupervised ML Algorithm Demo](./Supervised_and_Unsupervised_ML_Algorithm_Demo)
Two-part notebook:  
1. Supervised learning on a **heart-disease** dataset including cleaning, encoding/scaling, cross-validated models (logistic, KNN, NB, SVM, RF, GB) with full metric reporting.  
2. Unsupervised clustering of **mall customers** using PCA + KMeans/DBSCAN/GMM/hierarchical clustering, evaluated via silhouette, ARI, and NMI.

---

### [Consumer Data Segmentation and Churn Modeling](./Consumer_Data_Segmentation_And_Churn_Modeling)
Uses **kNN clustering** and **PCA visualization** to find subgroups within wholesale consumer data, informing marketing strategy and product-demand forecasting. Highlights how clustering can guide actionable segmentation insights in real business data.

---

### [Evolutionary Algorithm Evaluation](./Evolutionary_Algorithm_Evaluation)
Compares **PSO**, **GA**, and **ES** on two tasks: feature selection (Breast Cancer) and MLP hyperparameter tuning (Digits). Tracks accuracy, convergence speed, evaluations, and runtime.  
ES is most accurate and robust, GA most stable, PSO fastest but prone to stalling, illustrating exploration-exploitation trade-offs.

---

### [NLP for Twitter Hate Speech Detection](./NLP_For_Twitter_Hate_Speech_Detection)
NLP project analyzing the **Kaggle Hate Speech and Offensive Language** dataset.  
Includes preprocessing, TF-IDF feature extraction, and clustering to classify hate, offensive, and neutral tweets, evaluating normalization effects on model performance.

---

### [Decision Making Algorithm Evaluation](./Decision_Making_Algorithm_Evaluation)
Compares three decision-making paradigms including **Decision Trees, Monte Carlo Tree Search, and Markov Decision Processes** on tasks matched to their strengths: California Housing prediction, Tic-Tac-Toe planning, and FrozenLake navigation. It contrasts interpretability, scalability, and computational cost while showing how deterministic trees, simulation-based search, and probabilistic value iteration handle uncertainty and sequential decisions differently. Highlights practical trade-offs to guide algorithm selection by problem type.

---

## Tech Stack
Python · NumPy · pandas · scikit-learn · TensorFlow · PyTorch · Matplotlib · Seaborn · Jupyter Notebook · Huggingface

---

## Contact
Created by [Hunter Worssam](https://github.com/xHunterW)  
Feel free to fork, explore, or connect for collaboration opportunities!
