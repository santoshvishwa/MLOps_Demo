create env

using bash command bash
conda create -n wineq python=3.7 -y

activate env
using bash command 
conda activate wineq

create a requirement.txt file
Install the requiremets
using bash command
install -r requirement.txt

download the dataset from :

https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

git init
dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "firts commit"
