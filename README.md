# Modern Miller Assessment

## 1 About

This repository contains the source code for the Build Yelp in React

I Created a two-page application using the Yelp Fusion API.

On the first page, you should be able to search for businesses in Naperville or any location.

When you select a result, it should take you to a second page where you can see details about the business.

## 2.Screenshots

The application shows real data by calling the Yelp Fusion API.

## 2.1. Home
![Yelp Home](/src/ReadmeImages/HomePage.png)


## 3.2. Search for businesses / restaurants
![Yelp Search](/src/ReadmeImages/businessDetails.png)


## 3.Restriction while calling Yelp Fusion API

This app uses the CORS Anywhere because the Yelp Fusion REST API is meant for server to server communication and does not support CORS So i searched and find an option to to proxy all request through CORS Anywhere so we can focus on building the frontend part of the application.

## 4.How to run this Application

This application looks pretty much the same like the original Yelp website.

It leverages the free Yelp Fusion REST API for which you need an API key.

Head over to the Yelp Fusion API documentation
Click on Create App and sign in if you haven't done so already

Once you have signed in, click on the Get Started button. If you already have an app, then you will already see the API key
Fill out the form for creating a new app

Copy the generated API key. This is a bearer token that must be put inside the header of each request

Navigate to the src/hooks/yelp-api/config.js file and assign the BEARER_TOKEN variable the following content

const BEARER_TOKEN = '<your-token-here>'

Install the dependencies by running npm install or yarn install

Run the app with npm start or yarn start

## 5.Used Technologies

React / create-react-app

only functional components

communication with web servers with React Hooks only

no higher order or class-based components

React router with useReactRouter

Flexbox


