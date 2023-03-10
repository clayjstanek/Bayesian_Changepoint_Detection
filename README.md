I've included David's original paper in pdf format in this repository. I also built the package with pip
by downloading this whole directory and from the conda prompt typing : pip install -e <yourpathto/bayesian_changepoint_detection>

It will build a package called bayescd version 0.4.  But in your python files you must import it with the statement
<import bayesian_changepoint_detection> as the name for the package, not bayescd.

The best examples are in jupyter notebook form.
I suggest starting a jupyter server and work through example_code.ipynb and bayesian_changepoint_detection.ipynb

Im thinking of building a poetry .lock and .toml file for this project and will post them if I do.

Anyone seriously interested in this subject should read the pdf here in the repository written by my late, good friend David MacKay. One of the finest scientists and all-around human beings I have had the chance to know.


Bayesian Changepoint Detection
==============================

Methods to get the probability of a changepoint in a time series. Both online and offline methods are available. Read the following papers to really understand the methods:


[1] Paul Fearnhead, Exact and Efficient Bayesian Inference for Multiple                                    
    Changepoint problems, Statistics and computing 16.2 (2006), pp. 203--213                               
                                                                                                           
[2] Ryan P. Adams, David J.C. MacKay, Bayesian Online Changepoint Detection,                               
    arXiv 0710.3742 (2007)                                                                                 
                                                                                                           
[3] Xuan Xiang, Kevin Murphy, Modeling Changing Dependency Structure in                                    
    Multivariate Time Series, ICML (2007), pp. 1055--1062
    
To see it in action have a look at the [example notebook](https://github.com/clayjstanek/BayesianhangepointMethods/Example_Code.ipynb "Example Code in an IPython Notebook").
