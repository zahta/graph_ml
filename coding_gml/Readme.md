

## Essential Steps to Set Up Your PC for Graph Machine Learning with PyG

### 1. Install [miniconda3](https://docs.conda.io/en/latest/miniconda.html)

### 2. Create a [conda environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) as follows, and execute the following commands

```
conda create -n gml python pip
```
```
conda activate gml
```
```
conda install ipykernel
```  
```
python -m ipykernel install --user --name gml --display-name "Python (gml)"
```
```
conda install -c conda-forge matplotlib scikit-learn pandas
```

### 3. Install [PyTorch](https://pytorch.org/get-started/previous-versions/)
```
conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 cpuonly -c pytorch
```

### 4. Install NetworkX:
```
conda install -c anaconda networkx
```

### 5. Install Scipy:
```
conda install -c conda-forge scipy
```

### 6. Install DGL or PyG(Pytorch-Geometric):
#### 6.1 Install PyG (Pytorch-Geometric):

```
conda install -c pyg pyg
```

- Another options to install PyG:

  - Base on your Python and PyTorch version: https://pytorch-geometric.readthedocs.io/en/latest/install/installation.html
  - For newer versions: https://pytorch-geometric.com/whl/
  - For older versions: https://data.pyg.org/whl/
  - An Installation example for version 1.9.0 of pytorch:
      ```
      pip install torch_scatter -f https://data.pyg.org/whl/torch-1.9.0%2Bcpu.html
      pip install torch_sparse -f https://data.pyg.org/whl/torch-1.9.0%2Bcpu.html
      pip install torch-geometric
      ```  
          
#### 6.2 Install DGL:

##### System Requirements

**Supported OS:**

All Linux distributions no earlier than CentOS 7+ / Ubuntu 18.04.

macOS X 10.9+

Windows 10+ (with VC2015 Redistributable Installed) / Windows server 2016+

Supported Python versions: 3.6, 3.7, 3.8, 3.9, 3.10, 3.11

**Supported deep learning frameworks:**

PyTorch 1.12.0+

Apache MXNet 1.6+

TensorFlow 2.3+.

##### Installation

**With Conda (without cuda):**

conda install -c dglteam dgl

**With pip (without cuda):**

pip install  dgl -f https://data.dgl.ai/wheels/repo.html

pip install  dglgo -f https://data.dgl.ai/wheels-test/repo.html
        
