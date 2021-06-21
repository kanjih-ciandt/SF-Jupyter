# SF-Jupyter
How to invoke SF API from Jupyter

## Jupyter Notebook

The Jupyter notebook is a web-based notebook environment for interactive
computing.


### Installation

#### Step 1 : Install conda
Steps to install conda [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html#installing-conda-on-a-system-that-has-other-python-installations-or-packages)

#### Step 2: Create a env with jupyter and activate it
```bash
 conda create -n JUP python=3.7.10 numpy scipy pandas scikit-learn notebook
 conda activate JUP 
```
#### Step 3: Install dependencies

```bash  
conda install -c pytorch -c conda-forge -c anaconda -c uncbiag mermaid
pip3 install -r requiriments.txt

```
 
 ### Run Jupyter
 ```bash 
 jupyter notebook 
 ```

## Resources
- [Project Jupyter website](https://jupyter.org)
- [Online Demo at jupyter.org/try](https://jupyter.org/try)
- [Documentation for Jupyter notebook](https://jupyter-notebook.readthedocs.io/en/latest/) [[PDF](https://media.readthedocs.org/pdf/jupyter-notebook/latest/jupyter-notebook.pdf)]
- [Korean Version of Installation](https://github.com/ChungJooHo/Jupyter_Kor_doc/)
- [Documentation for Project Jupyter](https://jupyter.readthedocs.io/en/latest/index.html) [[PDF](https://media.readthedocs.org/pdf/jupyter/latest/jupyter.pdf)]
- [Issues](https://github.com/jupyter/notebook/issues)
- [Technical support - Jupyter Google Group](https://groups.google.com/forum/#!forum/jupyter)
