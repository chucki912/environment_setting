# environment_setting


# check the anaconda setting
conda info --envs

# create and use another environment rather than 'base'
conda create --name DS_ML python =3.7

# install ipykernel on created environment
python -m ipykernel install --user --name DS_ML --display-name "Python (DSML)"


conda install ipykernel

# check
cd /

# Remove conda environment
sudo rm -rf anaconda

# install in virtual environment
ipython kernel install --user --name 가상환경 --display-name "Python(가상환경)"
python -m ipykernel install --user

