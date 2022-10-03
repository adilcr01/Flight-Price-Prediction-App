# Flight Fare Prediction: 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployment on Azure](#deployement-on-Azure)
  * [Directory Tree](#directory-tree)
  * [Bug / Feature Request](#bug---feature-request)
  * [Future scope of project](#future-scope)


## Demo
Link: [https://flightpriceprediction.azurewebsites.net](https://flightpriceprediction.azurewebsites.net)

[![](https://i.imgur.com/R1g2wvC.png)](https://flight-price-prediction-api.herokuapp.com/)

![image](https://user-images.githubusercontent.com/93968656/193299188-733dec46-791f-4266-8cf8-7a4b3e6da388.png)


## Overview
This is a Flask web app which predicts fare of Flight ticket.

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning model to get most out of it. I came to know mathematics behind all supervised models. Finally it is important to work on application (real world application) to actually make a difference.

## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Azure
Login or signup in order to create virtual app. You can either connect your github profile or Azure Repos or Use Local git to manually deploy this project.

![image](https://user-images.githubusercontent.com/93968656/193308702-5549dafa-564e-4cb1-ad46-287a6759208c.png)


Our next step would be to follow the instruction given on [Azure Documentation](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python?tabs=flask%2Cwindows%2Cazure-cli%2Cvscode-deploy%2Cdeploy-instructions-azportal%2Cterminal-bash%2Cdeploy-instructions-zip-azcli) to deploy a web app.

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/adilcr01/Flight-Price-Prediction-App/issues) here by including your search query and the expected result

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 
