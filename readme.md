
<h2 align="center">IIT GUWAHATI CAMPUS CATALOGUE</h2>
<h4 align="left">A React native based application with NodeJs server powered by MongoDb database.</h4>

**A React-Node Based  Application**  

-------

# Development Readme

### Prerequisites

1.  [Git](https://git-scm.com/downloads).
2.  [Node & npm](https://nodejs.org/en/download/) _(version 16 or greater)_.
3.  clone of the repo.

## Installation of the Project

1. clone the project by - `git clone --recursive https://github.com/iks1/PickMeUp.git` to ensure it clones all the submodules as well.
2. go to the directory PickMeUp by -  `cd PickMeUp`
3. To make sure the submodules are updated run the command - ` git submodule update --remote`
4. follow the next procedures to run the project in your local environment.


## Running the Project

### Steps to run backend

In order to install all packages follow the steps below:

 1. Move to CampusCatalogue--backend folder
 2. Then move into the dashboard_apis folder
 3. For making sure you have the required npm version- `nvm use 18`
 4. If you don't have the desired version of node install it by - `nvm install 18`
 5. Then to install all the required packages run - `npm install`
 6. Then run `node index.js`
 7. your server should start

### Steps To Set Up Frontend
 
 #### customer side
 1. Move to PickMeUp--Customer
 3. `npm install`
 4. `npx expo start`
 5. `to run the application install the Expo Go application from Play Store and scan the QR Code or run  it on emulator`

 #### shopkeeper side
 1. Move to PickMeUp--Shopkeeper and repeat the abhove process




> The sercer will be served on **http://localhost:8080/**

### Directory Structure

The following is a high-level overview of relevant files and folders.

```
CampusCatalogue--backend/
├── dashboard_apis/
│   ├── core/
│   ├── dashboard_apis/
|   ├── files/
|   ├── scripts/
|   ├── static/
|   ├── templates/
|   ├── utils/
|   ├── volume_estimation/
|   ├── dbsqlite3
|   ├── generate_data.py
|   ├── load_adress.py
|   ├── load_data_object.py
|   ├── load_data_owner.py
|   ├── load_rider.py
|   ├── manage.py 
|   └── requirements.txt
|
└── frontend/
    ├── public/
    │   ├── index.html
    │   └── ...
    ├── src/
    │   ├── app/
    │   │   ├── store.js
    │   ├── Components/
    |   |   ├── Auth/
    │   │   ├── Global/
    |   |   ├── Layout/
    |   |   ├── Mobile/
    |   |   ├── RiderManagement/
    │   │   └── VolumeEstimation/
    │   ├── constants/
    │   ├── dummy_files/
    │   ├── features/
    │   ├── Pages/
    |       ├── Mobile/
    |       |   ├──Checklist.jsx
    |       |   └── ...
    |       ├── Dashboard.jsx
    |       ├── Demo.jsx
    |       ├── Inventory.jsx
    |       ├── InventoryImages.jsx
    |       ├── ManagerLogin.jsx
    |       ├── RiderDetails.jsx
    |       ├── RiderManagement.jsx
    |       ├── Riders.jsx
    |       ├── UploadZipPage.jsx
    |       └── VolumeEstimation
    |   ├── redux/
    |   ├── shared/
    |   ├── styles/
    |   ├── App.js
    |   ├── index.js
    |   ├── package-lock.json
    |   ├── package.json
    |   └── tailwind.config.js
    ├── .gitignore
    └── .README.MD
       
```

