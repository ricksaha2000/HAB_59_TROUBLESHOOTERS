# Groc4All - An E-Commerce Website

An ecommerce website specially for old people with covid-19 testing and updates

ABSTRACT

GDRIVE LINK: https://drive.google.com/drive/folders/1TVyhQghZhkjdqBoRQvi5zCBc9mK7hFwH?usp=sharing
YOUTUBE LINK: https://youtu.be/nDtKoA-PrOw

GROC4All is an ecommerce website designed for faster and easier order-placing of groceries and other essential products especially for the older generation who  are at a greater risk due to the coronavirus pandemic. This application helps them order essentials very easily as it allows placing their orders by heading over to our interactive chatbot and speaking into the microphone. The products will be hence added to the cart and the order would be placed based on shortest distance and availaibility of the nearest vendor based on geolocation. It registers and logs-in into the website using their face as biometric. Our application has a chatbot that interacts with the user  and  gives them daily updates of covid-19. There is additionally a covid-19 predictor that uses machine learning algorithms taking user symptoms as input and predicts whether a   person is infected with covid-19.

MOTIVATION

The entire world is going through a hard time during this covid pandemic but the segment of society worst affected is the older generation. Prone to highest level of infection, they aren’t able to move out of their homes for stocking regular supplies coupled with lack of reaching out to them by their close ones due to frequent regional lockdowns. Hence, our application aims at extending a humanitarian support towards the elderly people helping them order necessities very easily without having prior knowledge or expertise.  Besides helping the older generation, our application supports the local vendors and unites them in this critical situation.


## Features
	1. Full Authentication via face-recognition
	2. Category Add
	3. Product Add
	4. Shopping Cart
	5. Checkout Page
	6. Wishlists Create
	7. Wishlish Delete
	8. Profile Create
	9. Profile Update
	10.Shopkeeper user
	11.Speech to Text Chatbot
	12.Stripe Payment
	13.Corona Prediction
	14.COVID-19 Charts
	15.Connects all local vendors and places orders using GEOLOCATION
	

## Quick Start Guide

Clone the project repository

 bash
# change directory
$ cd HACK

# Setup Virtual Environment(LINUX)
$ virtualenv venv
$ source venv/bin/activate

# Install requirements
$ pip install -r requirements.txt

# Migrate db File
$ python manage.py makemigrations
$ python manage.py migrate

# Launch server
$ python manage.py runserver
