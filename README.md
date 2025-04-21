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

Examples of Our datset:
1) Image Dataset - ![Screenshot 2024-11-22 at 10 07 50 PM](https://github.com/user-attachments/assets/943540c0-996b-498a-b6aa-b27b710eb122)
2) Numerical Dataset - ![Numerical Dataset](https://github.com/user-attachments/assets/487e2a91-ca65-4645-8cd7-0e413bb8cd9c)

No additional steps were taken to expand the datasets. 
All the requirements (R2-R5) can be located in Code -> Jupyter -> F20DL Group8.ipynb , link: https://github.com/Leelian-Alhadhoud/F20DL-Group-8/blob/main/code%20/Jupyter/F20DL%20group8.ipynb


To run the Jupyter you have to import the following libraries -> 
You can use either of these 2 commands (depending on your environment) to install individually': "Pip3 install 'library_name'" OR    "Conda install 'library_name'" 
Or To install all of them at once you can use either of these: "pip install matplotlib numpy pandas seaborn tensorflow scikit-learn scipy" OR "conda install matplotlib numpy pandas seaborn -c conda-forge tensorflow scikit-learn scipy"


![Screenshot 2024-11-22 at 11 51 14 PM](https://github.com/user-attachments/assets/b8d0230e-05e8-45c6-97a8-aad3c0db2a74)

You can select a kernel and click on python environment.

![Screenshot 2024-11-29 at 12 14 01 PM](https://github.com/user-attachments/assets/92da7b1d-5dba-47f6-a9bd-0bd25300ea11)

Now click on create new python environment

![Screenshot 2024-11-29 at 1 59 21 PM](https://github.com/user-attachments/assets/bc75e8f3-85e2-4da4-9884-2ff5c3b3cea4)

Click on Conda or Pip environment

![Screenshot 2024-11-29 at 2 00 45 PM](https://github.com/user-attachments/assets/b3424576-c35f-4084-97dd-cd8732a73720)

You can choose your python verison from here

![Screenshot 2024-11-29 at 2 03 07 PM](https://github.com/user-attachments/assets/d2bf2c08-ed40-4a0e-a710-1761086c9233)


To Run the code you have to click on this "Run All" button and have Python 3.10 or under (Python 3.9 recommended)

![Screen Shot 2024-11-28 at 9 15 21 PM](https://github.com/user-attachments/assets/fbf76438-b016-4763-9260-b0c9a6b04a7f)




R2. Data Analysis and Exploration

Description:
The focus of this stage was to analyze and prepare the datasets for modeling. Preprocessing was performed on both the numerical and image datasets for missing values, standardizing features, and cleaning. The box plot and statistical summary were used to explore and compare the feature distributions between classes in the numerical dataset, while a correlation matrix revealed those features most related to the target variable. PCA was performed on the numerical dataset for the purpose of dimensionality reduction and the emphasis of the most important principal component, thus making further visualization and analysis easier.


R3. Clustering 

Description: 
In R3, we applied K-Means, Hierarchical Clustering, DBSCAN, and GMM to cluster the numerical data set preprocessed with PCA in R2. This PCA reduced dimensionality supported easier clustering. The Elbow Method was used to identify the best number of clusters, while cluster quality was assessed using Silhouette Scores and Silhouette Plots. Each of the methods contributed differently to the structure of the data: K-Means and GMM with sharp separations, DBSCAN-identifying noise points. The results of clustering have been checked by visualizations and metrics.

R4: **THE DECISION Tree** (Numerical Dataset) -
depicted here is predicting whether a breast tumor is benign or malignant based on various input features related to tumor characteristics, such as concave points_mean, radius_worst, texture_mean, and others. Expected output:

![output1](https://github.com/user-attachments/assets/2ba66761-ee2c-43e1-959a-4c9d0ed1711f)
![output](https://github.com/user-attachments/assets/12e9992d-af5c-4530-8467-87298ddcc1f6)

**THE K NEAREST NEIGBOURS** (Numerical Dataset) - 
The k-Nearest Neighbours algorithm is predicting whether a breast tumor is benign (non-cancerous) or malignant (cancerous) based on its similarity to nearby labeled data points in the dataset. Expected Output:
![Screenshot 2024-11-22 at 10 50 38 PM](https://github.com/user-attachments/assets/1a54d9a5-943e-40f8-86fe-6aa0f8eb3d45)

![3](https://github.com/user-attachments/assets/33c965a3-0a0e-4fe3-bc3b-11e8bdb89a09)
![1](https://github.com/user-attachments/assets/6d200785-0a8d-4c6f-a480-ede189b59129)
![2](https://github.com/user-attachments/assets/84d77f27-0ff6-4854-9f29-1295ccda45a1)
![4](https://github.com/user-attachments/assets/c0946001-8436-4432-af3e-a52403d72bd6)

**SUPPORT VECTOR MACHINE**(Numerical Dataset) - 
The Support Vector Machine (SVM) algorithm is predicting whether a breast tumor is benign or malignant. SVM works by finding the optimal hyperplane that separates the two classes in the feature space with the maximum margin, ensuring robust classification. Expected output
![5](https://github.com/user-attachments/assets/4981f171-ab47-4124-b892-b4d8ee14d857)
![8](https://github.com/user-attachments/assets/d9a5b687-99dc-467a-8d78-db4e0d14944a)
![7](https://github.com/user-attachments/assets/f7231d29-7f03-4019-b3f1-a4e5012e60ea)
![9](https://github.com/user-attachments/assets/d78cc1ea-cd7f-45e8-831f-7c542214d268)

R5: Neural Networks 
**Convolutional Neural Network** (Image Dataset) -
The Convolutional Neural Network (CNN) depicted here is predicting the category of images into one of two classes. Training and Validation Accuracy, Training and Validation Loss and it shows the Validation and test accuracy. Expected output
![cnn2](https://github.com/user-attachments/assets/aad056d2-7755-4d6b-b843-db8317c29a82)
![cnn1](https://github.com/user-attachments/assets/8f74ff37-fe8d-4f9e-829f-043ae81808f6)
![Screenshot 2024-11-22 at 11 04 38 PM](https://github.com/user-attachments/assets/7b507994-046b-4157-b795-1767d92ba26d)

**Multi-Layer Perceptron** (Image Dataset) -
The Multi-Layer Perceptron (MLP) depicted here is predicting whether a sample belongs to one of three classes: Benign, Malignant, or Normal.Expected output
![mlps1](https://github.com/user-attachments/assets/4c8d460c-a33e-42e3-b86d-4468e246ea41)

![Screenshot 2024-11-22 at 11 06 21 PM](https://github.com/user-attachments/assets/28782a25-f961-4357-9c8e-aa8dea79ab82)

![mlps2](https://github.com/user-attachments/assets/2b6f4ee8-65b1-4059-ac0a-4c06a83333e9)

**MultiLayer Perceptron** (Numerical Dataset)-
The Multi-Layer Perceptron (MLP) depicted here predicts whether a tumor is benign or malignant, achieving high accuracy. Expected output:
![mlps5](https://github.com/user-attachments/assets/1282b1a7-f861-4f03-8842-6802034e2de1)


![mlps4](https://github.com/user-attachments/assets/59634f6b-94ea-45ae-b306-447e5ccfad3b)








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




