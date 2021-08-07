## Machine Learning
### Setup Environment on local machine
- #### Setup Python
  ```
  sudo apt update
  sudo apt install python3-pip python3-dev
  ```
- #### Create Python Virtual Environment
  ```
  sudo -H pip3 install --upgrade pip
  sudo -H pip3 install virtualenv
  mkdir ~/my_project_dir
  cd ~/my_project_dir
  virtualenv my_project_env
  source my_project_env/bin/activate
  ```
- #### Install Jupyter and Run Jupyter Notebook
  ```
  pip install jupyter
  jupyter notebook
  ```
- #### Optionally connect using SSH Tunneling
  - [How To Set Up Jupyter Notebook with Python 3 on Ubuntu 20.04 and Connect via SSH Tunneling](https://www.digitalocean.com/community/tutorials/how-to-set-up-jupyter-notebook-with-python-3-on-ubuntu-20-04-and-connect-via-ssh-tunneling)

**Note** - *Can Open, Edit and Save Jupyter notebook present in Github on Google Colab directly. [[Using Google Colab with GitHub]](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)*
