# Create Conda Environment


## Firstly, we will create a conda environment called eda

conda create -n eda python=3.7.9

## Secondly, we will login to the eda environement

conda activate eda

## Install prerequisite libraries

Download requirements.txt file

wget https://github.com/anudeepb97/EDA-App.git

## Pip install libraries

pip install -r requirements.txt

## Download and unzip contents from GitHub repo

Download and unzip contents from https://codeload.github.com/anudeepb97/EDA-App/zip/main
Launch the app

streamlit run app.py
