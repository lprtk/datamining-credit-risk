<h1 align="center">Data Mining & Machine Learning for credit risk analysis</h1> 

<p align="center"> 
<a href="https://github.com/lprtk/datamining-credit-risk/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/lprtk/datamining-credit-risk"></a> 
<a href="https://github.com/lprtk/datamining-credit-risk/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/lprtk/datamining-credit-risk"></a> 
<a href="https://github.com/lprtk/datamining-credit-risk/stargazers"><img alt="Github Stars" src="https://img.shields.io/github/stars/lprtk/datamining-credit-risk"></a> 
<a href="https://github.com/lprtk/datamining-credit-risk/"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a> 
</p>


## Table of contents
* [Content :mag_right:](#Content)
* [File details :open_file_folder:](#File-details)
* [Features :computer:](#Features) 

<a id="section01"></a> 
## Content 

<p align="justify">As an individual investor, we want to start investing on the Lending Club platform, a crowdfunding platform based on peer to peer lending, and build a financial portfolio. To do so, we want to build a credit model to help the selection decision of investment projects by classifying potential borrowers into two classes: clients who will default and clients who will fully repay their loan.
Our goal is to use the data that the platform has been able to store, as well as the data provided by the borrowers, at the time of their loan application, to design a statistical machine learning model that allows us to maximize the probability that the borrower will actually repay the loan.<p>

<p align="justify">Generally, the risk of a loan is measured through a credit score assigned to the borrower according to his risk profile (i.e. FICO scores). We will thus try to model the solvency of a client, i.e. his capacity to repay his credit lines in due time. As you can see, the higher the credit rating of a customer, the higher his creditworthiness and, consequently, the lower the risk of default, and the more likely he is to benefit from a credit facility. The model will be based on data collected from 20,000 recent borrowers who were granted consumer credit through the platform's current loan underwriting process.<p>

<p align="justify">The future credit granting model will be built from predictive modeling tools under several constraints:<p> 
<ul>
    <li><p align="justify">First, in strict compliance with the regulatory constraints that the bank must face.</p></li>
    <li><p align="justify">Secondly, our work must be in line with the fundamental and necessary commitment to the Data professions: ethics and the general regulation on data protection.</p></li>
    <li><p align="justify">Finally, the last constraint is that of interpretability. We are not necessarily looking for the most efficient or the most complex model. For predictive work on such a sensitive subject, we prefer a less powerful model, but one from which it is much simpler to explain to a customer why his credit application is rejected.</p></li>
</ul>

<a id="section02"></a> 
## File details
* **codefile**
  * This folder contains a .rmd files which contains the code.
* **data**
  * This folder contains the data.

</br> 

Here is the project pattern: 
```
- project
    > datamining-credit-risk
        > data 
            - data_dictionary.xlsx
            - data_lending_club.csv
            - data_unsupervised.csv
            - train.csv
            - test.csv
        > codefile 
            - data_cleaning.rmd
            - data_visualization.rmd
            - unsupervised_learning.rmd
            - supervised_learning.rmd
```

<a id="section03"></a> 
## Features 
<p align="center"><a href="https://github.com/lprtk/lprtk">My profil</a> • 
<a href="https://github.com/lprtk/lprtk">My GitHub</a>
</p>
