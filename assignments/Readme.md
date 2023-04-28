
# Homeworks, Assignments, and Projects

**First Step:** Note that it is the responsibility of all students to familiarize themselves with the 
[Honor Code and Submission Policy](https://github.com/zahta/graph_ml/edit/main/README.md#copyright-honor-code-and-submission-policy) and 
to maintain the highest level of academic integrity.

**Second Step:** Create a GitHub Repository for the course with the name "graph_ml_course_assignments", 
and send its link to the course's group, as soon as possible.

### Assignment Set 1: Deadline 21 Feb 2023 (2 Esfand 1401) at 11:59pm.
  - **Part 1: Python Basics**    
  Do [these Python exercises](https://www.freecodecamp.org/learn/scientific-computing-with-python/#python-for-everybody) up to
  the exercise "comparing and sorting tuples", and take a photo from your final score and put it on your GitHub repository of the course.
  - **Part 2: Numpy, Pandas, and Matplotlib**   
    In each of the following problem sets, do at least 30 exercises (the more, the better). Use Git to save the .ipynb files of your assignments `from Labex to your GitHub repository (with a bonus)`, or use similar .ipynb files that I have already saved to the course repository using Git `(without a bonus)`.
    - [100 NumPy Exercises](https://labex.io/courses/100-numpy-exercises)
    - [100 Pandas Exercises](https://labex.io/courses/100-pandas-exercises)  
    - [Draw 2D and 3D Graphics with Matplotlib](https://labex.io/courses/draw-2d-and-3d-graphics-by-matplotlib)
    
### Assignment Set 2: Deadline 17 Mar 2023 (26 Esfand 1401) at 11:59pm.   

Understanding the concepts of these [two assignment sets](https://github.com/zahta/graph_ml/tree/main/assignments/assignment_set_2) will help you to solve the next assignments. Study the concepts presented in the two assignment sets and execute the codes. Try to understand the concepts correctly by printing the outputs and changing the parameters in each of the code cells.
- First: [networkx_tutorial_full.ipynb](https://github.com/zahta/graph_ml/blob/main/assignments/assignment_set_2/networkx_tutorial_full.ipynb)
- Second: [intro_networkx_pyg.ipynb](https://github.com/zahta/graph_ml/blob/main/assignments/assignment_set_2/intro_networkx_pyg.ipynb)

### Assignment Set 3: Deadline 4 Apr 2023 (15 Farvardin 1402) at 11:59pm.  

This assignment will guide you through the process of learning node embeddings by following a full pipeline consisting of three steps. First, we will load the Karate Club Network, which is a classic graph in network science, and explore various graph statistics related to it. Next, we will work together to transform the graph structure into a PyTorch tensor, which will enable us to perform machine learning on the graph. Finally, we will write a node embedding model, which is the first learning algorithm on graphs. Although our model is simpler than DeepWalk and node2vec algorithms taught in the lecture, it is still challenging and rewarding as we will write it from scratch using PyTorch. 

It is important to run all the cells sequentially to ensure that intermediate variables and packages carry over to the next cell.

Notebook: [node_embeddings.ipynb](https://github.com/zahta/graph_ml/blob/main/assignments/assignment_set_3/node_embeddings.ipynb)

### Assignment Set 4: Deadline 25 Apr 2023 (5 Ordibehesht 1402) at 11:59pm. 

From the pdf file below, please solve exercises 2.1, 2.3, 2.6, 4.1, 4.2, and 4.3.

File: [CS224W_Winter2223_HW1.pdf](https://github.com/zahta/graph_ml/blob/main/assignments/assignment_set_4/CS224W_Winter2223_HW1.pdf)

### Assignment Set 5: Deadline 28 Apr 2023 (8 Ordibehesht 1402) at 11:59pm. 

Write the Mid-term exam answers and Upload them to your repo.

### Assignment Set 6: Deadline 5 May 2023 (15 Ordibehesht 1402) at 11:59pm. 

Inspired by this [notebook](https://github.com/zahta/graph_ml/blob/main/example_node2vec/DeepWalk_and_node2vec_Implementation_details.ipynb) and based on this [example](https://github.com/zahta/graph_ml/blob/main/example_node2vec/node2vec_example.pdf), do the following exercises:
  - Give 5 different sets of the hyperparameters `embedding_dim, walk_length, context_size, walks_per_node, p, q`, train the node2vec model on a dataset from the [PyG's Dataset Cheatsheet](https://pytorch-geometric.readthedocs.io/en/latest/cheatsheet/data_cheatsheet.html) (different from the Cora dataset), report your final results of the test set on a table, and compare your results. 
  - Do the previous part for a given graph, e.g., the graph of this [example](https://github.com/zahta/graph_ml/blob/main/example_node2vec/node2vec_example.pdf).
  
         
