# Travel-Package-Purchase-Project-using-CICD-Pipeline
In this project We Train our model for the prediction of Travel Package that a Person will Purchase a Package or Not.

🧳Travel Package Purchase Prediction 
A End to  End project using CICD pipeline which will predict that A new Customer will Purchase the Package or Not.
## 📝 Table of contents
* [General info](#general-info)
* [Data Source](#data-source)
* [Problem Statement](#Problem-Statement)
* [Demo Photos](#demo-photos)
* [Library Used](#Library-Used)
* [Run Locally](#Run-Locally)
* [Deployment Techniques](#deployment-Techniques)

## General info
"Visit with us". company wants to enable and establish a viable business model to expand the customer base. One of the ways to expand the customer base is to introduce a new package offering. Currently, there are 5 types of packages the company is offering - Basic, Standard, Deluxe, Super Deluxe, and King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information. The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance, or kick-start a healthy lifestyle, and support or increase one's sense of well-being. However, this time, the company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

We need to analyze the customers' data and information to provide recommendations to the Policy Maker and Marketing Team and also build a model to predict the potential customer who is going to purchase the newly introduced travel package.

## ⏳Data Source
[Travel Package Data](https://www.kaggle.com/code/yogidsba/travelpackageprediction-ensemble-techniques/input)

## Problem Statement
To predict which customer is more likely to purchase the newly introduced travel package
Which variables are most significant?
Which segment of customers should be targeted more?

## 📷 Demo Photos
<img width="1006" alt="tour_package" src="https://user-images.githubusercontent.com/92681972/232985096-7026b3ec-d469-442b-beb4-f5209d08acf9.png">
 Our Website will look like and when we hit the submit button, a prediction will happen. adn output will be that the customer will take the package or the customer will not the package.
 
 ## 🖥️Library Used
 There will be a file named requirement.txt which will contain all these libraries used in the project.
 ```
pandas
numpy
seaborn
matplotlib
scikit-learn
xgboost
flask
dill
 ```
## 👨🏻‍💻Run Locally
* Before the following steps make sure you have git, Anaconda or miniconda installed on your system
* Clone the complete project with git clonehttps://github.com/Gajender0707/Travel-Package-Project-using-CICD-Pipeline.git or you can just download the code and unzip it.
* Once the project is cloned, open VSCode prompt in the directory where the project was cloned and paste the following block ```python venv -m myenv python=3.11.3``` after that 
* ```myenv/Scripts/Activate.ps1```
* ```pip install -r requirements.txt``` And finally run the project with ```python app.py```.
* Open the localhost url provided after running app.py and now you can use the project locally in your web browser or put ```http://127.0.0.1:8080``` which is your local host.

# Deployment Techniques
* Deployment to AWS: The final step is to deploy all the files to an AWS server. This step is done by us using the ubuntu server where we deployed our model using the winSCP to connect the AWS server(EC2).

## 🎯Project Created BY
[@DevikaPagare](https://www.linkedin.com/in/devika-pagare-a205861aa/)

