
# Course: Graph Machine Learning

> **The highest activity a human being can attain is learning for understanding, <br> because to understand is to be free.** *Baruch Spinoza*

|<b>Lecturer</b>    |   |
|:-:|:-:|
| <img src="https://raw.githubusercontent.com/zahta/zahta/main/img/zahra_taheri.png"  width=170pt > <br> <b>[Zahra Taheri](https://github.com/zahta)</b>   | **[Data Science Center](http://ds.sbu.ac.ir/)**  <br>  <br> **[Shahid Beheshti University](https://en.sbu.ac.ir/)** <br>  <br> <b> Winter 2023</b> |


## :bulb: Course Overview

<div align="justify">
  
*Graph Machine Learning* is a course that focuses on the application of machine learning algorithms on graph-structured data. Some of the key topics that are covered in the course include graph representation learning and graph neural networks, algorithms for the world wide web, reasoning over knowledge graphs, and social network analysis. The course is designed for graduate students with a background in machine learning and/or data science who want to expand their skills to work with graph data. The course may also be useful for students and professionals working in fields such as computer science, biology, chemistry, and physics that require the analysis of graph-structured data. The objective of the course is to provide students with a comprehensive understanding of graph machine learning and its various applications, challenges, and opportunities, as well as hands-on experience in implementing these algorithms.

  </div>

## :beginner: Prerequisites

- Familiarity with the basic probability theory, and the basic linear algebra
- Basic knowledge of machine learning and/or deep learning concepts
- Familiarity with the basics of Python programming language
- Familiarity with PyTorch is a plus


## :books: Recommended Materials

### Books
- [Graph Representation Learning](https://www.cs.mcgill.ca/~wlh/grl_book/) by William L. Hamilton
- [Network Science](http://networksciencebook.com/) by Albert-László Barabási
- [Networks, Crowds, and Markets: Reasoning About a Highly Connected World](https://www.cs.cornell.edu/home/kleinber/networks-book/) by David Easley and Jon Kleinberg
- [Analysis of Biological Networks](https://onlinelibrary.wiley.com/doi/book/10.1002/9780470253489), 2007.

###  Graph Machine Learning Tools
- [DGL (Deep Graph Library)](https://www.dgl.ai/)
- [PyG (PyTorch Geometric)](https://www.pyg.org/)
- [NetworkX](https://networkx.org/)

### Courses
- [CS224W: Machine Learning with Graphs](http://web.stanford.edu/class/cs224w/) by Jure Leskovec

### Tips and Tools for Data Science
- [Fundamental and Useful Tools and Tips for Data Science](https://github.com/zahta/tools_tips_data_science)
- [Essential Steps to Set Up Your PC for Graph Machine Learning with PyG](https://github.com/zahta/graph_ml/tree/main/setup_pc_for_coding_gml)

## :closed_book: Other Materials
### Books 
- [Deep Learning on Graphs](https://www.cambridge.org/core/books/deep-learning-on-graphs/CF908050EECC148A9E6F3EAED6099DB4) by Yao Ma and Jiliang Tang
- [Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges](https://geometricdeeplearning.com/) by Michael M. Bronstein, Joan Bruna, Taco Cohen, and Petar Veličković

[//]: # (### Papers)
  

## :book: Contents

The contents and materials related to the course will be posted here. 

### 1. Introduction to Graph Machine Learning

#### Required Reading:
  - **Slide:** [Introduction; Machine Learning for Graphs](http://snap.stanford.edu/class/cs224w-2020/slides/01-intro.pdf) by Jure Leskovec

#### Suggested Reading:
  - **Papers:** To fully understand the following papers, you should be familiar with graph neural networks.
    - **Node-Level Graph ML Task:**
      - [Alphafold2: Highly accurate protein structure prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2) by Jumper, et.al., Nature 2021. 
    - **Edge-Level Graph ML Task:**
      - [Graph Convolutional Neural Networks for Web-Scale Recommender Systems](https://arxiv.org/pdf/1806.01973.pdf) by Ying et.al., KDD 2018.
      - [Modeling Polypharmacy Side Effects with Graph Convolutional Networks](https://arxiv.org/pdf/1802.00543.pdf) by Zitnik et.al., Bioinformatics 2018.
    - **Subgraph-Level Graph ML Task:**
      - [ETA Prediction with Graph Neural Networks in Google Maps](https://dl.acm.org/doi/abs/10.1145/3459637.3481916) by Derrow-Pinion et.al., CIKM 2021.
    - **Graph-Level Graph ML Task:**
      - [A Deep Learning Approach to Antibiotic Discovery](https://www.cell.com/cell/fulltext/S0092-8674(20)30102-1?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867420301021%3Fshowall%3Dtrue) by Stokes et.al., Cell 2020.
      - [Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation](http://papers.neurips.cc/paper/7877-graph-convolutional-policy-network-for-goal-directed-molecular-graph-generation.pdf) by You et.al., NeurIPS 2018.
      - [Learning to simulate complex physics with graph networks](https://arxiv.org/abs/2002.09405) by Sanchez-Gonzalez et al., ICML 2020. 

### 2. Traditional Methods for Machine Learning on Graphs

#### Required Reading:
  - **Slide:** [Traditional Methods for ML on Graphs](http://snap.stanford.edu/class/cs224w-2020/slides/02-tradition-ml.pdf) by Jure Leskovec

#### Suggested Reading:
  - **Blog:** 
    - [Link Prediction in Large-Scale Networks](https://hackernoon.com/link-prediction-in-large-scale-networks-f836fcb05c88?gi=b86a42e1c8d4) by Cdiscount Data Science
    - [Expressive power of graph neural networks and the Weisfeiler-Lehman test](https://towardsdatascience.com/expressive-power-of-graph-neural-networks-and-the-weisefeiler-lehman-test-b883db3c7c49) by Michael Bronstein
  
  - **Slide:** 
    - [Introduction to Kernel Methods](https://www.cs.upc.edu/~belanche/Talks/MEETUP-July2014.pdf)
    - [Elements of Positive Definite Kernel and Reproducing Kernel Hilbert Space](https://www.ism.ac.jp/~fukumizu/H20_kernel/Kernel_2_elements.pdf)
  - **Paper:** 
    - [Graph Kernels](http://jmlr.csail.mit.edu/papers/volume11/vishwanathan10a/vishwanathan10a.pdf) by Vishwanathan et al., JMLR 2010.
    - [Efficient graphlet kernels for large graph comparison](https://proceedings.mlr.press/v5/shervashidze09a.html) by Shervashidze et al., JMLR 2009.
    - [Weisfeiler-Lehman Graph Kernels](https://jmlr.csail.mit.edu/papers/v12/shervashidze11a.html) by Shervashidze et al., JMLR 2011.
  - **Question:** [How does the dot product determine similarity?](https://math.stackexchange.com/questions/689022/how-does-the-dot-product-determine-similarity)
     
### 3. Node Embeddings

#### Required Reading:
  - **Slide:** [Node Embeddings](http://snap.stanford.edu/class/cs224w-2020/slides/03-nodeemb.pdf) by Jure Leskovec
  - **Example of node2vec:** [Detailed Example and Implementation](https://github.com/zahta/graph_ml/tree/main/example_node2vec) by Zahra Taheri

#### Suggested Reading:
  - **Blog:** 
    - [Complete guide to understanding Node2Vec algorithm](https://towardsdatascience.com/complete-guide-to-understanding-node2vec-algorithm-4e9a35e5d147) by Tomaz Bratanic
    - [Node2Vec Explained](https://towardsdatascience.com/node2vec-explained-db86a319e9ab) by Vatsal
    - [node2vec: Embeddings for Graph Data](https://towardsdatascience.com/node2vec-embeddings-for-graph-data-32a866340fef) by Elior Cohen
    - [Node2vec explained graphically](https://towardsdatascience.com/node2vec-explained-graphically-749e49b7eb6b) by Remy Lau
    - [Word2Vec Tutorial - The Skip-Gram Model](http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/) by Chris McCormick 
    - [How to Use Negative Sampling With Word2Vec Model?](https://analyticsindiamag.com/how-to-use-negative-sampling-with-word2vec-model/) by Vijaysinh Lendave
    - [Understanding Representation Learning With Autoencoder](https://neptune.ai/blog/representation-learning-with-autoencoder#:~:text=It%20is%20a%20modified%20version,autoencoders%2C%20they%20are%20fairly%20limited.) by Nilesh Barla
  - **Video:** 
    - [Graph Embeddings (node2vec) explained - How nodes get mapped to vectors](https://www.youtube.com/watch?v=pS_POUVFXvk) by Philipp Brunenberg
    - [Node2Vec: Scalable Feature Learning for Networks | ML with Graphs (Research Paper Walkthrough)](https://www.youtube.com/watch?v=LpwGZG5j_q0) by TechViz-The Data Science Guy
  
### 4. Graph Neural Networks 1: 

#### Required Reading:
  - **Slide:** [Graph Neural Networks 1: GNN Model](http://snap.stanford.edu/class/cs224w-2020/slides/06-GNN1.pdf) by Jure Leskovec

#### Suggested Reading:
  - **Blog:** 
    - [A Gentle Introduction to Graph Neural Networks](https://distill.pub/2021/gnn-intro/)  
    - [Understanding Convolutions on Graphs](https://distill.pub/2021/understanding-gnns/)
    
### 5. Graph Neural Networks 2: 

#### Required Reading:
  - **Slide:** [Graph Neural Networks 2: Design Space](http://snap.stanford.edu/class/cs224w-2020/slides/07-GNN2.pdf) by Jure Leskovec

#### Suggested Reading:
  - **Blog:** 
    - [Best Graph Neural Network architectures: GCN, GAT, MPNN and more](https://theaisummer.com/gnn-architectures/#inductive-vs-transductive-learning)  
    
        
## :pencil: Homework and assignment

More information about homeworks, assignments, and projects will be posted here. 

- [Assignment Set 1](https://github.com/zahta/graph_ml/tree/main/assignments#assignment-set-1-deadline-21-feb-2023-2-esfand-1401-at-1159pm): Deadline 21 Feb 2023 (2 Esfand 1401) at 11:59pm.
- [Assignment Set 2](https://github.com/zahta/graph_ml/blob/main/assignments/Readme.md#assignment-set-2-deadline-17-mar-2023-26-esfand-1401-at-1159pm): Deadline 17 Mar 2023 (26 Esfand 1401) at 11:59pm.
- [Assignment Set 3](https://github.com/zahta/graph_ml/tree/main/assignments#assignment-set-3-deadline-4-apr-2023-15-farvardin-1402-at-1159pm): Deadline 4 Apr 2023 (15 Farvardin 1402) at 11:59pm.
- [Assignment Set 4](https://github.com/zahta/graph_ml/blob/main/assignments/Readme.md#assignment-set-4-deadline-25-apr-2023-5-ordibehesht-1402-at-1159pm): Deadline 25 Apr 2023 (5 Ordibehesht 1402) at 11:59pm.

### :copyright: Honor Code and Submission Policy

<div align="justify">

The Honor Code and Submission Policy are the foundation for ethical and academic standards in the Graph Machine Learning course. All students are expected to adhere to the Honor Code by not engaging in academic misconduct such as plagiarism or cheating on exams. The Submission Policy requires that all assignments are submitted on time, in the specified format, and accurately reflect the student's own work. Late submissions may be accepted with a penalty, as outlined in the policy. Failure to comply with the Honor Code and Submission Policy may result in consequences such as a reduced grade or failure in the course. It is the responsibility of all students to familiarize themselves with the Honor Code and Submission Policy and to maintain the highest level of academic integrity.

</div>

## :bar_chart: Grading

The weighting scheme of the grading:

- 20% on Homeworks
- 25% on the Mid-Term Exam
- 30% on the Final Exam
- 25% on the Final Project
- Course participation and contribution in the discussions as extra credit


## :clock130: Course Schedule

Sunday and Tuesday 1:30pm to 3pm

**Office Hours**  
Sunday and Tuesday 12:30pm   
Also, students may ask their questions via the group of the course.

## :alarm_clock: Exam

- Mid-Term: Sunday, 18 April 2023 (29 Farvardin 1402)
- Final: Saturday, 17 June 2023  (27 Khordad 1402)
