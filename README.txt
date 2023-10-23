README: Running the Python Code for Three Tasks
This README provides instructions on how to compile and run the Python code for the three tasks: Data Preparation, Community Detection, and Finding the Optimal Number of Communities.
Prerequisites
Ensure that you have the following installed on your system:
•	Python (version 3.x)
•	NetworkX library (install via pip install networkx)
•	NumPy library (install via pip install numpy)
•	SciPy library (install via pip install scipy)
•	scikit-learn library (install via pip install scikit-learn)
Task 1: Data Preparation
1.	Place your dataset in the same directory as the code file.
2.	Update the file_path variable in the code to point to your dataset file.
3.	Run the code. It will load the dataset and prepare the data for subsequent tasks.

Task 2: Community Detection
1.	After completing Task 1, proceed with the following steps:
2.	Ensure that you have implemented the BigCLAM algorithm and community detection logic. Replace the placeholder detect_communities(graph, number_communities) with your actual implementation.
3.	Update the number_communities variable to the desired number of communities.
4.	Run the code. It will execute the community detection algorithm and provide the detected communities.
Task 3: Finding Optimal Number of Communities
1.	After completing Task 2, proceed with the following steps:
2.	Ensure that you have implemented the modularity calculation logic. Replace the placeholder calculate_modularity(graph, communities) with your actual implementation.
3.	Run the code. It will try different numbers of communities and output the optimal number of communities based on modularity.
4.	Review the printed message to find the optimal number of communities.

