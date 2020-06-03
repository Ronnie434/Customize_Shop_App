React Native Customize_Shop_App

React Native Bookstore App
This is a simple bookstore app developed with React Native and integrated with Rave React Native SDK for payment collection.

Table of contents
Prerequsites
How To Set It Up Locally
Deployment
Contributions
Prerequisites
To set this app up locally, you need to have the following available:

Rave Test Public And Private Keys
Rave Live Public And Private Keys
Node
NPM
React Native
Expo CLI
How To Set It Up Locally
Fire up your git bash terminal, then do follow the process below:

First of all ensure you have Expo command line tool installed, To set it up successfully you can use this link as guide.

Clone this repo - git clone https://github.com/MaestroJolly/react-native-bookstore-app

cd into react-native-bookstore-app - cd react-native-bookstore-app.

Run npm install to install all our dependencies.

From the screens directory inside our project directory, open the PaymentScreen.js and add your Rave Test or Live public and secret keys depending on the environment you want to deploy.

Then run the command npm start or expo start to start up our app.

Deployment
You can deploy the project on test and live environment with this options:

Flutterwave Rave Live to get your LIVE public and private key

Flutterwave Rave Test to get your TEST public and private key

NOTE: Set the production of option to true or false depending on our deployment environment.

Contributions
You are free to fork or clone this repo to use for test
