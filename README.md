# EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool

# Date: 13.10.2023

# AIM:
To perform a classification technique using WEKA tool

# WEKA:
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements. WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram −


![280514918-c3702dff-f72d-4ba1-9cca-eb444358ab21](https://github.com/prithviraj5703/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418418/f9a99f60-199a-427b-98b8-5ac689f0d951)


# CLUSTERING:
Clustering or cluster analysis is a machine learning technique, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points. The objects with the possible similarities remain in a group that has less or no similarities with another group." It does it by finding some similar patterns in the unlabelled dataset such as shape, size, color, behavior, etc., and divides them as per the presence and absence of those similar patterns. It is an unsupervised learning method, hence no supervision is provided to the algorithm, and it deals with the unlabeled dataset.

# PROCEDURE:

  1. In the WEKA explorer select the Preprocess tab. Click on the Open file ... option and select the iris.arff file in the file selection dialog.

     ![280516188-bd6df0b2-51db-4cee-a6f7-33152b2aac12](https://github.com/prithviraj5703/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418418/532bbea0-5fb4-45fa-9dc4-2caacdc851c1)

    
     
  2.  Click on the Cluster TAB to apply the clustering algorithms to our loaded data. Click on the Choose button. Now, select EM as the clustering algorithm.

   
   ![280516240-34796748-9934-4cf0-9ce9-9b8204adb904](https://github.com/prithviraj5703/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418418/a6c4aade-3b20-4a20-9a1c-bcace46a92d8)


  3. In the Cluster mode sub window, select the Classes to clusters evaluation option

     ![280516260-658892f7-e190-4264-a5ae-175bb6e64a2b](https://github.com/prithviraj5703/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418418/e144ca61-0fce-4e86-97de-50a465b30764)
  
   
     
  4. Click on the Start button to process the data. After a while, the results will be presented on the screen.
     

     ![280516290-a9b44cbc-15db-4821-8dc7-7a22cd5999a4](https://github.com/prithviraj5703/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418418/2b545555-2575-4c9a-af9c-a88316f355a8)

    
  5.  From the output screen, you can observe that − There are 5 clustered instances detected in the database. The Cluster 0 represents setosa, Cluster 1 represents virginica, Cluster 2 represents versicolor, while the last two clusters do not have any class associated with them.

![280516378-5e2ee384-d8fc-45c3-ac20-fb716fd8cf5b](https://github.com/prithviraj5703/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418418/0c9ad23d-b8a9-4333-b61d-6b4b7122e45f)

    


  6. To visualize the clusters, right click on the EM result in the Result list.

       ![280516419-4078b056-ad78-4f6d-b86c-a1dc8e8b9f9e](https://github.com/prithviraj5703/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418418/748e0ce3-d5af-45ee-8c0c-940ca4822bb5)

               
  7. Select Visualize cluster assignments.

     ![280516443-b28a21b1-4965-412f-8ac2-b8cdc079b703](https://github.com/prithviraj5703/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/121418418/3252e994-794e-4dc9-8177-8d513b21ddf8)


# RESULT:
Thus the simulation of clustering technique has been executed using WEKA tool successfully.
