# Foreword

This repository includes a set of jupyter notebooks of the data analysis for a retail company.

You can find three jupyter notebooks within the *notebooks* folder.

1. "Warm up", which was developed to have a first look of the data.
2. "Getting started", which try to give answers to some bussiness questions.
3. "Super bowl", which contains an inventory forecasting section by product.
 

## Environment

The main components of the stack include:

* pandas
* seaborn
* matplotlib

In order to use this notebooks on your own jupyter environment, you should install the required packages with:
`pip install -r requirements.txt`

It is recommended to use a [virtual environment](https://virtualenv.pypa.io/en/latest/)


## Notebooks structure

I have tried to keep a consistent structure for every notebook, including: 
 
1. Introduction
2. Data preprocessing
3. Development
4. Conclusions and further analysis



# Challenge Description #

This challenge have two sections, as follows:

## 1. Getting started ##

These are some of our recurrent questions.

* Create a comprehensive way to show when a customer has its first purchase at the showroom (Purchase location == offline, you can see the column in the file I've attached below) and we are interested in knowing what is the behavior on the subsequent purchases (for example if the 2nd transaction happens online, and so on). A chart and a table it would be useful.
* We want to know the LTV (lifetime value) by customer
* We want to create a cohort to know the customers who first purchased a certain material (there's a column called material group name) and so on. For example:

|                 | Q1      | Q2    | Q3    | Q4    |
|-----------------|---------|-------|----------------
| bought Gold     | 5000    | 1000  | 500   | 50    |
| bought Vermeil  | 5000    | 1000  | 500   | 50    |

Note: for instance, in the first row, 5000 (Q1) means 5000 customers bought gold in the first quarter, and 1000 (Q2) only 1000 bought again on the Q2, etc. 

* We want to create a cohort to know the customers who first purchased a certain product type and so on. In this case, the data is not clean, you should extract (or fix the data) the type from the product name (the types are Ring, necklace, Stud, bracelet, earrings, hoops), and the cohort should look like.

|                   | Q1      | Q2    | Q3    | Q4    |
| ------------------|---------|-------|----------------
| bought Ring       | 5000    | 1000  | 500   | 50    |
| bought bracelet   | 5000    | 1000  | 500   | 50    |

* What product has the highest speed of sale in a 1 day window? and when did it happen?


## 2. Super bowl ##

As you might know, the year is divided in quarters, here at the company, even though each day counts, we put a lot of effort to perform and succeed during the Q4 (October, November, and December). 
What's special about this? Black Friday week! (and holidays, of course). You will find in the file below the historical data from 2016 to the beginning of October 2018. You can see all the items sold during the last 2 years and the idea is to create a model to forecast the inventory needed for November and December of 2018.
Even though the data might not be enough, do your best and justify your approach. 


## Dataset ##

The dataset can be downloaded from this [public repository](https://s3.amazonaws.com/mejuri-web/public/orders_report.csv)
