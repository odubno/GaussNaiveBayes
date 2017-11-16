# Naive Bayes In Python

Writing a Gaussian Naive Bayes classifier in python from scratch.

## Getting Started

Git clone the repo to use the code 
```
git clone https://github.com/odubno/naive_bayes.git
```

### Prerequisites


Every function is created from scratch.
However, instead of you having to download the data, we're using a quick api call to get the csv.

```
pip install requests
```

### Step by Step
#### Train
Calculate the mu and variance of features for each target class.

#### Test
Using the the Normal Distribution, calculate the PDF for all test features of each target class using N(x; mu, variance).
Calculate the Joint PDF of each row, by multiplying pdf results together.
Choose the highest joint pdf.

![Alt text](img/normal_distribution.svg "Optional Title")

### Installing

Once cloned, running the program is as simple as calling 
```bazaar
python naive_bayes.py
```


End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Authors

* **Oleh Dubno** - *algorithms and python code* - [odubno](http://odubno.github.io/)
* **Danny Argov** - *algorithms and idea generation*

See also the list of [contributors](https://github.com/odubno/naive_bayes/graphs/contributors) who participated in this project.


## Acknowledgments

* Hat tip to Dr. Jason Brownlee, who wrote a blog of [How To Implement Naive Bayes From Scratch in Python](https://machinelearningmastery.com/naive-bayes-classifier-scratch-python/). 
Much of the logic here comes from his post. 
* Inspiration:
Project for Columbia Probability and Statistics course - Prof. Banu Baydil
