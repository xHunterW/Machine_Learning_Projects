# Machine Learning Projects
A curated collection of graduate level data science and machine learning projects.  
Each notebook explores a different technique ranging from classical supervised models and clustering to evolutionary algorithms, NLP, pre-trained models and dimensionality reduction, with reproducible workflows and visual analyses for each.

---

## Project Index

### [Imputation Algorithm Comparison](./Imputation_Algorithm_Comparison)
This Jupyter notebook examines the use of *k-Nearest Neighbors* and *Regression* as algorithms for missing-data imputation in the **Titanic dataset** (Kaggle). kNN imputes missing Cabin numbers, and regression predicts missing ages. Both are validated and tested in downstream models.

---

### [Pre-trained Model Hub Comparison](./Pre-trained_Model_Hub_Comparison)
Compares lightweight pretrained models across hubs for NLP (IMDb) and Computer Vision (CIFAR-10): **Hugging Face**, **PyTorch Hub**, **TF Hub**, and a scikit-learn baseline. Standardized preprocessing, fixed budgets, linear-probe vs light fine-tune. Reports F1 and F1/min with Apple-silicon optimizations.

---

### [Unsupervised Learning for Dimensionality Reduction](./Unsupervised_Learning_for_Dimensionality_Reduction)
Analyzes the performance of **PCA** versus an **Autoencoder** for dimensionality reduction. Both techniques are compared using KMeans and DBSCAN clustering, evaluated via within-cluster metrics and classification accuracy to assess representation quality and separability.

---

### [Supervised and Unsupervised ML Algorithm Demo](./Supervised_and_Unsupervised_ML_Algorithm_Demo)
Two-part notebook:  
1. Supervised learning on a **heart-disease** dataset including cleaning, encoding, scaling, and cross-validated models (logistic, KNN, NB, SVM, RF, GB) with full metric reporting.  
2. Unsupervised clustering of **mall customers** using PCA + KMeans/DBSCAN/GMM/hierarchical clustering, evaluated via silhouette, ARI, and NMI.

---

### [Consumer Data Segmentation and Churn Modeling](./Consumer_Data_Segmentation_And_Churn_Modeling)
Uses **kNN clustering** and **PCA visualization** to find subgroups within wholesale consumer data, informing marketing strategy and product-demand forecasting. Highlights how clustering can guide actionable consumer segmentation insights in real world business data.

---

### [Evolutionary Algorithm Evaluation](./Evolutionary_Algorithm_Evaluation)
Compares **PSO**, **GA**, and **ES** on two tasks: feature selection (Breast Cancer data) and MLP hyperparameter tuning (Digits). Tracks accuracy, convergence speed, evaluations, and runtime.  
ES is most accurate and robust, GA is most stable, PSO fastest but prone to stalling, illustrating exploration-exploitation trade-offs.

---

### [NLP for Twitter Hate Speech Detection](./NLP_For_Twitter_Hate_Speech_Detection)
NLP project analyzing the **Kaggle Hate Speech and Offensive Language** dataset.  
Includes preprocessing, TF-IDF feature extraction, and clustering to classify hate, offensive, and neutral tweets; while also evaluating normalization effects on model performance.

---

### [Decision Making Algorithm Evaluation](./Decision_Making_Algorithm_Evaluation)
Compares three decision-making paradigms including **Decision Trees, Monte Carlo Tree Search, and Markov Decision Processes** on tasks matched to their strengths: California Housing prediction, Tic-Tac-Toe planning, and FrozenLake navigation. It contrasts interpretability, scalability, and computational cost while showing how deterministic trees, simulation-based search, and probabilistic value iteration handle uncertainty and sequential decisions differently. Highlights practical trade-offs to guide algorithm selection by problem type.

---

### [Pre-trained LLM Tuning and Evaluation](./PreTrained_LLM_Tuning_and_Evaluation.html)
Fine-tunes **FLAN-T5-Small** on an *Alice in Wonderland* question-answer dataset using the Hugging Face `datasets`, `transformers`, and `Trainer` APIs. The notebook compares three strategies for question answering: (1) fine-tuning alone, (2) few-shot prompt engineering, and (3) retrieval-augmented QA; and analyzes how model size and limited domain data affect hallucinations, validation loss, and overall answer quality.

---

### [Image Captioning and Object Detection](./Image_Captioning_and_Object_Detection)
Implements a full multimodal deep-learning pipeline on the Flickr30k dataset, demonstrating image captioning, zero-shot classification, and visual grounding with state-of-the-art vision-language models. The notebook fine-tunes BLIP for conditional caption generation and evaluates the resulting model against the pretrained baseline using BLEU scores and qualitative comparisons. It then applies CLIP for zero-shot semantic classification and OWL-ViT for open-vocabulary object localization, highlighting how Transformer-based VLMs bridge image–text understanding across generation, retrieval, and grounding tasks.

---

## Tech Stack
Python · NumPy · pandas · scikit-learn · TensorFlow · PyTorch · Matplotlib · Seaborn · Jupyter Notebook · Huggingface

---

## Contact
Created by [Hunter Worssam](https://github.com/xHunterW)  
Feel free to fork, explore, or connect for collaboration opportunities!
