# Foreword #

First of all, thanks for taking the time to take this tech challenge. We really appreciate it. Rather than using a strictly theoretical approach, the idea is to solve problems related to our daily questions. The file with the raw data is at the end of this document.

### Getting started, this is mejuri ###

Mejuri is all about the customer journey, we are constantly questioning what we can improve and one valuable source the customer behavior. These are some of our recurrent questions.

* Create a comprehensive way to show when a customer has its first purchase at the showroom (POS == true, you can see the column in the file I've attached below) and we are interested in knowing what is the behavior on the subsequent purchases. A chart an a table it would be useful.
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

Note: Feel free to show (besides the table) whatever chart/table you think can help us to understand better the cohort. If you don't know about the quarters: https://en.wikipedia.org/wiki/Calendar_year

* What product has the highest speed of sale in a 5 minutes window? and when did it happen?


### The Mejuri super bowl ##

As you might know, the year is divided in quarters, here at Mejuri, even though each day counts, we put a lot of effort to perform and succeed during the Q4 (October, November, and December). 
What's special about this? Black Friday week! (and holidays, of course). You will find in the file below the historical data from 2016 to the beginning of October 2018. You can see all the items sold during the last 2 years and the idea is to create a model to forecast the inventory needed for November and December of 2018.
Even though the data might not be enough, do your best and justify your approach. 


### The future :robot: ###

Besides the flying cars and talking robots, like many others, we do believe we can use science to deliver a better experience. We want to hear from you how machine learning, big data or whatever you're familiar with can help our Mejuri e-commerce platform to deliver the best possible experience.


### What we expect, requirements and considerations ###

The technology to solve this is up to you, we use Looker, ruby, python and Postgres DB. Please specify the stack you have chosen to solve this, create a repository and it should be easy to run a reproduce the outputs.
If something is not clear please ask for clarification. We are here to help you.

As you might notice the email is hashed, that shouldn't be a problem, the emails are still unique and they can be treated as regular emails.
