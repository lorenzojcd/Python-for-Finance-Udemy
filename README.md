# python-for-finance
Udemy Python for Finance

## Setup on Linux
```
sudo pip install jupyter
sh ./Anaconda3-5.1.0-Linux-x86_64.sh
cd /media/rudi/data/Python-for-Finance-Repo-master/
ls
pip install appnope
//Remove appnope from maclinuxenvironment.yml
vi maclinuxenvironment.yml 
conda env create -f maclinuxenvironment.yml 
source activate pyfinance
jupyter notebook
conda deactivate
```