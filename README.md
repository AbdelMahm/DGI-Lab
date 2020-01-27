# DGI-Lab
Machine and Deep Learning Lab for DGI

## Lab setup
### Install Miniconda
#### Download 
Miniconda from https://conda.io/miniconda.html
#### install
$bash Miniconda3-latest-Linux-x86_64.sh

### Create environment
#### Create env
$conda create --name dgimllab python=3.6
#### Create environment a shared one (.yml file)
$conda env create -f environment.yml
#### activate env
$source activate dgimllab
(dgimllab)$

### Install packages 
(dgimllab)$pip3 install --upgrade pip
(dgimllab)$pip3 install numpy scipy pandas matplotlib 
(dgimllab)$pip3 install scikit-learn
(dgimllab)$pip3 install jupyter
(dgimllab)$pip install --ignore-installed --upgrade tensorflow
(dgimllab)$pip install -U nltk
#### list packages
(dgimllab)$ conda list

### Share Environment
#### create .yml file
(dgimllab)$conda env export > environment.yml

### Github
#### Get repository
git…
move to repository
(dgimllab)@cd lab_path

### Jupyter notebook
#### run jupyter
jupyter notebook
#### install package inside a jupyter notebook cell
!pip install numpy
