Topic: Breast Tumour Classification 


Project Milestones:

Here is a plan of when we expect to finish the 5 Requirements-

R1. Project Topic and Direction - Week 3

R2. Data Analysis and Exploration - Week 5

R3. Clustering - Week 7

R4. Baseline Training and Evaluation Experiments - Week 9

R5. Neural Networks - Week 11



Our Dataset Sources: 
1) Images Dataset - https://datasetninja.com/breast-ultasound-images
2) Numerical Dataset - https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data

License Sources:
1) Images Dataset - https://creativecommons.org/publicdomain/zero/1.0/
2) Numerical Dataset - https://creativecommons.org/licenses/by-nc-sa/4.0/


To run the Jupyter you have to import the following libraries -> 
You can use either of these 2 commands (depending on your environment) to install individually': "Pip3 install 'library_name'" OR    "Conda install 'library_name'" 
Or To install all of them at once you can use either of these: "pip install matplotlib numpy pandas seaborn tensorflow scikit-learn scipy" OR "conda install matplotlib numpy pandas seaborn -c conda-forge tensorflow scikit-learn scipy"

You can select a kernel and click on python environment.



Now click on create new python environment



Click on Conda or Pip environment



You can choose your python verison from here



To Run the code you have to click on this "Run All" button and have Python 3.10 or under (Python 3.9 recommended)




R2. Data Analysis and Exploration

Description:
The focus of this stage was to analyze and prepare the datasets for modeling. Preprocessing was performed on both the numerical and image datasets for missing values, standardizing features, and cleaning. The box plot and statistical summary were used to explore and compare the feature distributions between classes in the numerical dataset, while a correlation matrix revealed those features most related to the target variable. PCA was performed on the numerical dataset for the purpose of dimensionality reduction and the emphasis of the most important principal component, thus making further visualization and analysis easier.


R3. Clustering 

Description: 
In R3, we applied K-Means, Hierarchical Clustering, DBSCAN, and GMM to cluster the numerical data set preprocessed with PCA in R2. This PCA reduced dimensionality supported easier clustering. The Elbow Method was used to identify the best number of clusters, while cluster quality was assessed using Silhouette Scores and Silhouette Plots. Each of the methods contributed differently to the structure of the data: K-Means and GMM with sharp separations, DBSCAN-identifying noise points. The results of clustering have been checked by visualizations and metrics.

R4: **THE DECISION Tree** (Numerical Dataset) -
depicted here is predicting whether a breast tumor is benign or malignant based on various input features related to tumor characteristics, such as concave points_mean, radius_worst, texture_mean, and others. 

**THE K NEAREST NEIGBOURS** (Numerical Dataset) - 
The k-Nearest Neighbours algorithm is predicting whether a breast tumor is benign (non-cancerous) or malignant (cancerous) based on its similarity to nearby labeled data points in the dataset. 


**SUPPORT VECTOR MACHINE**(Numerical Dataset) - 
The Support Vector Machine (SVM) algorithm is predicting whether a breast tumor is benign or malignant. SVM works by finding the optimal hyperplane that separates the two classes in the feature space with the maximum margin, ensuring robust classification. 

R5: Neural Networks 
**Convolutional Neural Network** (Image Dataset) -
The Convolutional Neural Network (CNN) depicted here is predicting the category of images into one of two classes. Training and Validation Accuracy, Training and Validation Loss and it shows the Validation and test accuracy. 


**Multi-Layer Perceptron** (Image Dataset) -
The Multi-Layer Perceptron (MLP) depicted here is predicting whether a sample belongs to one of three classes: Benign, Malignant, or Normal.


**MultiLayer Perceptron** (Numerical Dataset)-
The Multi-Layer Perceptron (MLP) depicted here predicts whether a tumor is benign or malignant, achieving high accuracy. 


The main datasets:
https://datasetninja.com/breast-ultasound-images
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data




Week 1 (23-9-2024 to 29-9-2024)
-> Confirm the datasets for training, validating, and testing and check if it's ethical

Week 2  (30-9-2024 to 6-10-2024)

-> Decided to do 2 datasets

Week 3 (7-10-2024 to 13-10-2024)

-> Finalized the Data Preprocessing

week 4 (28-10-204 to 3-11-2024)

-> Started and Finalized 
  - Zero R
  - One R
  - Min-Max
  - zscore
  - Wrap
  - Missing


week 5 (4-11-2024 to 10-11-2024)

- Did PCA
- Started and Finalized Clustering
- Started and Worked on Baseline Training & Evaluation Experiments

week 6 (11-11-2024 to 17-11-2024)

- Worked on the other half of Baseline Training & Evaluation Experiments
- Worked on Neural Networks
- Finished Neural Networks




