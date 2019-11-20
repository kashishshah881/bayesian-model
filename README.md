# Modeling Rainfall Distribution using Gamma Parameters


<img src="https://github.com/kashishshah881/bayesian-model/blob/master/images/all.png" width="2000">




In this project, We build a Bayesian Model on the Dataset. <br/>
The Steps used are:
* Looking at the histogram of the data, the best fitting distribution would be a gamma distribution.
* Pick an analytic probability density function matching the shape of the histogram(Uniform,Normal,Exponential)
* Model its parameters (priors) as probability density functions
* Try different shape and values of these parameters (**hyperparameters**)
* Run a probabilistic program to give us the posterior pdfs
* Plot the posterior means on top of the histogram and check if we get a good match!

Results: The Following are the result for the three distributions we have used:

###### Uniform Distribution
<img src="https://github.com/kashishshah881/bayesian-model/blob/master/images/uniform.png" width="500">


###### Normal Distribution

<img src="https://github.com/kashishshah881/bayesian-model/blob/master/images/normal.png" width="500">


###### Exponential Distribution (Does fit better than the other two!)
<img src="https://github.com/kashishshah881/bayesian-model/blob/master/images/exponential.png" width="500">






## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

```
git clone https://github.com/kashishshah881/bayesian-model.git

```

### Prerequisites

What things you need to install the software:

```
Python3.5+
```

### Installing

Run These Commands on the terminal
```
pip3 install jupyter numpy pandas matplotlib pymc3 seaborn
```
Once Everything is installed successfully run

```
jupyter notebook
```



## Authors

* **[Kashish Shah](www.kashishshah.com)**


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

