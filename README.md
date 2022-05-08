Create conda envioronment
```bash
conda create -n wineq python=3.7
conda activate wineq
```
Create requirements.txt file
```bash
pip install -r requirements.txt
```

download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

```bash
git init
```
```bash
dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

git remote add origin https://github.com/isaranja/e2e-ml-ops.git
git branch -M main
git push origin main
```
