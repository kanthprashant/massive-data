# Streaming K means clustering

Given an input text file named “data.txt”, run streaming k-means algorithm. The data file consists of about 1 million vectors and each vector has 20 dimensions.
Each line on the text file consists of a single vector. The vectors are enclosed in square brackets (“ [ ] ”) and the features in the vector are comma separated. 
Another file named “centers.txt” consists of the initial cluster centers. The “centers.txt” uses the same format as “data.txt”.</br></br>

- Once the clustering is done on the entire data set, evaluate the final cluster centers and save them on a text file: 
  - Format: (cluster_number) [cluster_center] </br>
- Specify the cluster number for the vectors in “testdata.txt”. Save the results on a text file in the format given below:
  - Format: (cluster_number) [test_data_vector] </br>
- Evaluate clustering by checking the sum of squares cost on “testdata.txt”. Save the results on a text file in the format given below:
  - Format: Cost = [number]</br>

