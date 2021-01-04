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
sudo rm -rf anaconda
