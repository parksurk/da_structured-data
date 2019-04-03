Data Analytics - Structured Data
================================

How to analyze Structured Data using Python
-------------------------------------------

---

TBD - introduction about this course

### Prerequisites

#### Theoretical things

-	Read about Traditional Statistics :  

#### Technical things

-	Python : <a href="./prerequisites1 - python.ipynb">Prerequisite 1 - Python Notebook</a>
-	IPython & Jupyter Notebook : <a href="./prerequisites2 - python data science environment.ipynb">Prerequisite 2 - Python Data Science Environment Notebook</a>
-	NumPy : <a href="./prerequisites3 - numpy.ipynb">Prerequisite 3 - NumPy Notebook</a>
-	Pandas : <a href="./prerequisites4 - pandas.ipynb">Prerequisite 4 - Pandas Notebook</a>
-	Matplotlib : https://matplotlib.org
-	Seaborn : https://seaborn.pydata.org
-	Scikit-learn : https://scikit-learn.org/stable/

### Project Details

For this project, we will use DataSets in Kaggle Competition.

---

### Getting Started

Follow the steps below!

#### Step 1: Classification

Titanic: Machine Learning from Disaster https://www.kaggle.com/c/titanic

#### Step 2: Clustering

Mall Customer Segmentation Data Market Basket Analysis https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python

#### Step 3: Regression

Black Friday https://www.kaggle.com/mehdidag/black-friday

#### Step 4: Classification - LightGBM

Elo Merchant 카테고리 추천 https://www.kaggle.com/c/elo-merchant-category-recommendation

---

### Instructions

To setup our project environment to run the code in this repository, follow the instructions below.

1.	Clone this repository

```
git clone https://github.com/parksurk/da_structured-data.git
```

2.	Create (and activate) a new environment with Python 3.6.
	-	Linux or Mac:`
		conda create --name kaggle python=3.6
		source activate kaggle
		`
	-	Windows:`
		conda create --name kaggle python=3.6
		activate kaggle
		`
3.	Install Python Scientific Libraries

```
pip install jupyter numpy pandas matplotlib seaborn scikit-learn scipy
```

4. Install [RISE](https://github.com/damianavila/RISE) - Jupyter notebook slideshow library (Optional for Presenter)

```
conda install -c conda-forge rise
```

5.	Create an IPython kernel for the kaggle environment. (Skip if you done already)

```
pip install ipykernel
python -m ipykernel install --user --name kaggle --display-name "kaggle"
```

6.	Run Jupyter Notebook

```
jupyter notebook
```

7.	Before running code in a notebook, change the kernel to match the 'kaggle' environment by using the drop-down Kernel menu.

8.	Click **.ipynb** on root directory
