# Foreword

Hi! First of all, thank you for givin me the chance to have this challenge. I really enjoy it. 

You can find three jupyter notebooks within the *notebooks* folder.

1. "Warm up", which was developed to have a first look of the data.
2. "Getting started", which corresponds to the challenge section with the same name.
3. "Super bowl", wich corresponds to the inventory forecasting section.
 

## Stack

I have used jupyter notebooks with python kernels for this challenge. I think this is a very powerful tool to describe this kind of processes.

### Environment

You can access to a running environment of jupyter notebooks through **http://zamuvps.ddns.net:8888** (password: mejuri)


Otherwise, you can use this notebooks on your own jupyter environment.

You should install package required to run this notebooks with:
`pip install -r requirements.txt`

It is recommended to use a [virtual environment](https://virtualenv.pypa.io/en/latest/)

Remember to save a copy of the [dataset](https://s3.amazonaws.com/mejuri-web/public/orders_report.csv) on `data` folder


### Notebooks structure

I have tried to keep a consistent structure for every notebook, including: 
answer 
1. Introduction
2. Data preprocessing
3. Development
4. Conclusions and further analysis


## Conclusions

In particular, for 'The future' section of the challenge, I think that further analysis sections within notebooks obey o this end and can be resumed as follows:

* Multidimensional data structures, such as OLAP cubes and [datamarts](https://en.wikipedia.org/wiki/Data_mart) can be very helpful to empower non technical users
* Despite of the ad-hoc data preprocessing sections developed for this challenge, they must be defined as standarized [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) processes.
* More data is a must for training useful forecast models with machine learning. This can be achieved with more granular data (see '5. Top speed of sale product (1 day window)' in *Getting started* notebook) and external data (see 'Further analysis' section in *Super bowl* notebook).


