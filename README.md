# Installing-Keras-Xgboost-TensorFlow
Updated July- 2019


Dealing with TensorFlow incompatibility with Python 3.7

1) Install the latest version of Anaconda/Miniconda from the website

2) Once Anaconda/Miniconda has been downloaded you must create a Python 3.6 environment. Not all TensorFlow 2.0 packages currently (as of July 2019) support Python 3.7. So you must execute the following commands( In the Anaconda Prompt)

conda create -y --name tensorflow python=3.6</h3>

3) To enter this environment, you must use the following command (for Windows), this command must be done every time you open a new Anaconda/Miniconda terminal window:

For windows:
activate tensorflow

For Mac:
source activate tensorflow

4) Installing Jupyter: It is easy to install Jupyter notebooks with the following command:
conda install -y jupyter

Once Jupyter is installed, it is started with the following command:
jupyter notebook
    
5) Installing packages:
Install these packages first(one by one)

conda install -y scipy
pip install --exists-action i --upgrade sklearn
pip install --exists-action i --upgrade pandas
pip install --exists-action i --upgrade pandas-datareader
pip install --exists-action i --upgrade matplotlib
pip install --exists-action i --upgrade pillow
pip install --exists-action i --upgrade tqdm
pip install --exists-action i --upgrade requests
pip install --exists-action i --upgrade h5py
pip install --exists-action i --upgrade pyyaml
pip install --exists-action i --upgrade tensorflow_hub
pip install --exists-action i --upgrade bayesian-optimization
pip install --exists-action i --upgrade spacy
pip install --exists-action i --upgrade gensim
pip install --exists-action i --upgrade flask
pip install --exists-action i --upgrade boto3
pip install --exists-action i --upgrade gym
pip install --exists-action i --upgrade tf-nightly-2.0-preview
pip install --exists-action i --upgrade keras-rl2 --user
conda update -y --all


6) Installing Keras/TensorFlow/XGBoost

pip install --exists-action i --upgrade keras
pip install --exists-action i --upgrade tensorflow
pip install --exists-action i --upgrade xgboost


