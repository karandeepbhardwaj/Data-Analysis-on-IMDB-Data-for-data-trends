# Data Trends on imDB dataset from 1960 - 2016

## Project: Investigate the IMDB dataset

### Introduction

In this project, we have to analyze a dataset and then communicate our findings about it.
We will use the Python libraries NumPy, pandas, and Matplotlib to make your analysis easier.

What do I need to install?
You will need an installation of Python, plus the following libraries:
* pandas
* NumPy
* Matplotlib
* csv

It will be recommend to installing Anaconda, which comes with all of the necessary packages, as well as IPython notebook.


### Why this Project?
In this project, we have to go through the data analysis process and see how everything fits together.
I have also use the Python libraries NumPy, pandas, and Matplotlib, which make writing data analysis code in Python a lot easier! 

| Table of Contents |
| :--- |
| <a href='#Prerequisites'> Prerequisites </a> 🔍📜 | 
| <a href='#Design'> Design </a>  📐 |
| <a href='#Conclusions'> Conclusions </a>  📌 |
| <a href='#License'> License </a> 🔖 |


<a id='Prerequisites'></a>

### Prerequisites


![](https://img.shields.io/badge/platform-ios-green.svg?colorA=abcdef)


- Python 3.6.3
- Jupyter Notebook
- Anaconda-Navigator

### Data

#### Files

This project contains 2 files and 2 folder:
- `data.csv` : The dataset file containing 10k+ entries of movies that I have worked on. 
- `report.ipynb` : The investigation of the dataset has been done in this jupyter notebook file. 
- `export/` : Folder containing HTML and PDF file of notebook.
- `plots/`  : Contains images of all the plots that are displayed in `report.ipynb` file.

#### Dataset file

This data set contains information about 10,000 movies collected from The Movie Database (TMDb). Contains data such as `title, cast, director, runtime, budget, revenue, release year` etc. 
- Certain columns, like `‘cast’` and `‘genres’`, contain multiple values separated by pipe (|) characters.
- There are some odd characters in the `‘cast’` column. Nothing to care much of, I leave them as is.
- The final two columns ending with `“_adj"` show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.


<a id='Design'></a>

### Design


![](https://img.shields.io/badge/language-Python-orange.svg)


**_Step One_** - Choose Data Set


Click this [link](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True) to download the corresponding data.

**_Step Two_** - Get Organized


This project eventually contain:


- The report communicating any findings;
- Any Python code used during the analysis;
- The data set;


**_Step Three_** - Analyze


Brainstorm some questions that could be answered using the data set, then start answering those questions, we would mainly focus on looking at the relationships between multiple variables. 

-----

### Loading Project

#### Requirements

This project requires **Python 3** and the following Python libraries installed:

- [Python 3.6.5](https://www.python.org/downloads/release/python-365/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 


#### Execution

In a terminal or command window, navigate to the top-level project directory `Investigate_TMDb_Movies/` (that contains this README) and run one of the following commands:

```bash
ipython notebook report.ipynb
```  
or
```bash
jupyter notebook report.ipynb
```

or if you have 'Jupyter Lab' installed
```bash
jupyter lab
```

This will open the Jupyter/iPython Notebook software and project file/folder in your browser.

-----

### Conclusion

#### What I learned

 - What all steps are involved in a typical data analysis process.
 - Comfortable posing questions that can be answered with a given dataset and then answering those questions.
 - Know how to investigate problems in a dataset and wrangle the data into a format that can be used.
 - Have practice communicating the results of the analysis.
 - Being able to use vectorized operations in NumPy and Pandas to speed up your data analysis code.
 - Being familiar with Pandas Series and DataFrame objects, which lets access data more conveniently.
 - Last but not least, Know how to use Matplotlib and Seaborn to produce plots showing findings.
 

#### Evaluation
My project was reviewed by a Udacity reviewer against the **<a href="https://review.udacity.com/#!/projects/3176718735/rubric" target="_blank">Investigating a Dataset rubric</a>**. All criteria found in the rubric must be *meeting specifications* for me to pass.

<a id='License'></a>

## License 


[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://github.com/Shilin0806/Investigate_the_FBI_Gun_Dataset/blob/master/LICENSE)

----
