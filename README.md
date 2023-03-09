# The Dorm Den  🐐

A Hostel Web Portal using MERN stack

## [Live Preview](https://dormden.me) 🎈

![This is an image](https://github.com/SAMEER-SHRESTHA911/Readme/blob/main/output/HomePage.png)


## About ℹ️

**`The Dorm Den`** is a Hostel Web Portal implemented in `MERN stack` by [Bikrant Bidari](https://github.com/bikrantbdr), [Sudeep Kaucha](https://github.com/Sudeep-K), [Sameer Shrestha](https://github.com/SAMEER-SHRESTHA911) and [Arahanta Pokhrel](https://github.com/arahanta). While creating the project, we learnt about `Event Listeners in React`, `React State`, `Conditional Rendering in React`, `React Hooks(useEffect,useState)`, `React Routers`, `Styled components`, etc.  A user can search for hostels as per his/her requirement and a hostel owner can showcase his/her hostel. After creating the project, `Frontend` was deployed to `Netlify`and `Backend` was deployed to `Render`.

## Technologies Used 💻

<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="50" height="50"/> </a>                                         <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="50" height="50"/> </a>
<a href="https://reactjs.org/" target="_blank" rel="noreferrer">  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="50" height="50"/> </a>                                      <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="50" height="50"/> </a>                                                          <a href="https://www.figma.com/" target="_blank" rel="noreferrer">  <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="50" height="50"/> </a>                                       <a href="https://postman.com" target="_blank" rel="noreferrer">  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="50" height="50"/> </a>                             <a href ="https://npmjs.com/>" target="_blank" rel="noreferrer">  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" alt = "npm" width = "50" height="50" /> </a>                       <a href="https://www.cloudinary.com/" target="_blank" rel="noreferrer"> <img src="https://github.com/SAMEER-SHRESTHA911/Readme/blob/main/output/cloudinary.png" alt = "cloudinary" width="50" height="50">
  

</br >

## Includes the following features ⚙️

        - Places autocomplete
        - Geo encoding
        - Filtering
        - Sorting
        - Encryption 

</br>

## Usage 🪄

```bash
###Clone the repository using Github CLI
git clone https://github.com/bikrantbdr/TheDormDen.git
```

<h4>Frontend</h4>

```bash
###Go to the client folder
cd client
###Install Dependencies
npm install
```

```bash
###Start the developmet server(App will open in a new window)
npm start
```

<h4>Backend</h4>

```bash
###Go to the Backend folder
cd Backend
###Install Dependencies
npm install
```

```bash
###Create a .env file inside the Backend folder and add the following things inside that file:

MONGODB_URI = 
SECRET = 
PORT = 
SMPT_SERVICE = 
SMPT_EMAIL = 
SMPT_PASSWORD = 
COOKIE_EXPIRES_IN = 
CLOUDINARY_NAME =
CLOUDINARY_API_KEY = 
CLOUDINARY_API_SECRET = 

#Fill in the blank contents of the .env file with your data
```

```bash
###Deploy backend server locally
npm run dev
```
<br/>

<h2>Steps we used to complete this project 🪜</h2>

## ➡️ Frontend

### 1. Initialize project 🐲

-   [x] Initialize the project using `npx create-react-app thedormden` which will create a
        complete **React App** pre-configured and pre-installed with the dependencies.
-   [x] Delete the Boiler plate.

### 2. Organize the project 🧹

-   [x] Create `components`, `utils`, `assets` and `Pages` folder inside the `src` directory.

### 3. Routing and Rendering 🛣️

-   [x] Index.jsx renders the React components
-   [x] App.jsx routes to the different pages.

### 4. Designing the Pages ✂️✨

-   [x] Design basic layout of the pages
-   [x] 

### 5. Pages 📄

-   [x] Create different pages according to the requirements
<br/>

    #### 5.1 Home Page
    ![Home page]()
    #### 5.2 Search Page
    ![Search Page]()
    #### 5.3 Individual Page
    ![Individual Page]()
    #### 5.4 Dashboard(User, Admin)
    ![Individual Page]()
    #### 5.5 Login Page
    ![Login]()
    #### 5.6 Register Page
    ![Register Page]()

### 6. Packages 📦

-   [x] Install the packages to be used.
```bash
npm install 'npm-package-name'
```
-   [x] Some of the packages used in our project are
    

    #### 6.1 Styled Components
    
    - Used to write CSS code within the JSX components.

    #### 6.2 React Icons 

    - To access customizable icons for use in React components

    #### 6.3 Pigeon Map 🗺️

    - Display and access location details.

    #### 6.4 Axios

    - Handle request from the frontend and get respond from the backend

    #### 6.5  React Router DOM

    - Implement dynamic routing in the web app.

    #### 6.6 Universal Cookie

    - Access cookies from all the routes.

    #### 6.7 JWT decode

    - Decode the data from the cookie. 
</br>

### 7.  API(Application Programming Interface)📥

-   [x] Add the API's used in the project.
-   [x] Some of the used API's are

    #### 7.1 Places Autocomplete API
    -   predicts place in response to an HTTP response
    #### 7.2 Geo Encoding API
    -   provide geocoding and reverse geoencoding of addresses

### 8. Make App Responsive 📱

-   [x] Change _Absolute_ units to _Relative_.
-   [x] Make App responsive for mobile by adding `media query`. 😊

### 9. Prepare for Deployment 🪢

-   [x] Delete **unnecessary** files from directory and format code with `Prettier`.
-   [x] Test for _Responsiveness_ and make changes if need be.
-   [x] Add links to `Live Preview` and _screenshots_.

### 10. Deploy 🚀

-   [x] Use official documentation of [Netlify](https://docs.netlify.com/) and [Render](https://render.com/docs) to deploy both Backend and Frontend🎆🎆🎆

<br/>

## Future Changes ♾️

    
