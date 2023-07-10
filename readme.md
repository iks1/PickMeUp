
<h2 align="center">IIT GUWAHATI CAMPUS CATALOGUE</h2>
<h4 align="left">A React native based application with NodeJs server powered by MongoDb database.</h4>

**A React-Node Based  Application**  

-------

# Development Readme

### Prerequisites

1.  [Git](https://git-scm.com/downloads).
2.  [Node & npm](https://nodejs.org/en/download/) _(version 18 or greater)_.
3.  clone of the repo.

## Installation of the Project

1. Clone the project by -  `git clone --recursive https://github.com/iks1/PickMeUp.git` to ensure it clones all the submodules as well.
2. Go to the directory PickMeUp by -  `cd PickMeUp`
3. To make sure the submodules are updated run the command -  `git submodule update --remote`
4. Follow the next procedures to run the project in your local environment.


## Running the Project

### Steps to run backend

In order to install all packages follow the steps below:

 1. Move to <b> CampusCatalogue---Backend </b> folder
 2. To make sure you have the required npm version run -  `nvm use 18`
 3. If you don't have the desired version of node install it by -  `nvm install 18` and then run -  `nvm use 18`
 4. Then to install all the required packages run -  `npm install`
 5. Then run -  `node index.js`
 6. Your server should start!

 > The server will be served on **http://localhost:8080/**

### Steps To Set Up Frontend
 
 #### customer side
 1. Move to <b> PickMeUp--Customer </b>
 2. `npm install`
 3. `npx expo start`
 4. To run the application install the Expo Go application from Play Store and scan the QR Code or run  it on emulator

 #### shopkeeper side
 1. Move to <b> PickMeUp--Shopkeeper </b> and repeat the above process


### Directory Structure

The following is a high-level overview of relevant files and folders.

```
CampusCatalogue---Backend/
├── config/
│   ├── default.js
│   └── ...
├── controllers/
|   ├── shopkeeper.js
|   ├── user.js
|   └── ...
├── middlewares/
|   ├── validation
|   |    ├──shopkeeper.js
|   |    └──user.js
|   └── auth.js
├── models/
|   ├── customer_model.js
|   ├── db.js
|   ├── order_model.js
|   └── shop_model.js
├── routes/
|   └── ...
├── .gitignore
├── package-lock.json
└── package.json

PickMeUp--Shopkeeper/
├── assets/
│   └── ...
├── components/
|   ├── Completed.js
|   ├── CompletedActive.js
|   ├── Google.js
|   ├── InputField.js
|   ├── Navbar.js
|   ├── Pending.js
|   └── ...
├── pages/
|   ├── Getstarted.js
|   ├── Login.js
|   └── PendingHomePage.js
├── .gitignore
├── App.js
├── app.json
├── babel.config.js
├── metro.config.js
├── package-lock.json
├── package.json
└── m-cli.config.js

PickMeUp--Customer/
├── assets/
│   └── ...
├── components/
|   ├── FilterCard.js
|   ├── FoodCard.js
|   ├── FoodCard2.js
|   ├── FoodItemCard.js
|   ├── FoodPopUp.js
|   ├── Google.js
|   └── ...
├── context/
|   ├── AuthContext.js
|   └── ...
├── pages/
|   ├── BillingPage.js
|   ├── foodDashboard.js
|   ├── FoodShopPage.js
|   ├── GetStarted.js
|   ├── Login.js
|   ├── printDashboard.js
|   ├── SignUp.js
|   └── ...
├── .gitignore
├── App.js
├── app.json
├── babel.config.js
├── metro.config.js
├── package-lock.json
├── react-native.config.js
├── package.json
└── m-cli.config.js


```
