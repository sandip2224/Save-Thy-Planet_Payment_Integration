# Save Thy Planet 🌏

You can Install and test Save-Thy-Planet webapp from below 👇

<p>
  <img src="https://img.shields.io/badge/MAINTAINED-YES-brightgreen?style=for-the-badge&logo=appveyor">
  <img src="https://img.shields.io/badge/WEBSITE-UP-green?style=for-the-badge&logo=appveyor">
</p>

<!-- ABOUT THE PROJECT -->

## 🎄 What it does
- This application features a carousel-based information display on multiple endangered species on our planet in the 21st century.
- This application features a working payment gateway to accept donations from the general masses who are willing to support the planet through financial support.
- This application features a working blog page that is constantly updated with stories that inspire and give hope.
- It also includes a facts section that is updated with quirky facts related to wildlife and our global ecosystem.

## 🛠 How we built it
My application utilizes the following tech stack:

#### Frontend
- HTML / CSS: Simple markup and styling for Save-Thy-Planet application.
- EJS Templating Engine: Backend templating engine to render frontend from MongoDB Atlas.
- Vanilla JS: Plain JavaScript without any additional libraries.

#### Backend
- Node.js: JavaScript runtime built on Chrome's V8 JavaScript engine.
- Express.js: Minimal and flexible Node.js web application framework that provides a robust set of features for webapp development.
- MongoDB Atlas: Primary database to store authenticated users and violation reports.

#### Frameworks / Libraries
- Bootstrap: Mininal JS Framework for speedy frontend setup.
- Passport.js: Base library for Google OAuth.
- Passport-Google-OAuth: Used to set up Google Oauth inside our application.
- Mongoose ODM: Used to interact with MongoDB Atlas Cluster.
- Razorpay API: Used to set up payment gateway inside our application.
- JavaScript Maps API: Renders the global map with violation markers inside our application.
- HTML Geolocation API: Accesses current location of individual submitting the violation form on the backend.

## 🚩 How to Install Locally

**1. Fork and clone this repository using**

   ```
   git clone https://github.com/sandip2224/Save-Thy-Planet-WebApp.git
   cd Wallet-X/
   ```  
   
**2. Install required dependencies and dev dependency using**  

   ```
   npm install
   npm install -D nodemon
   ```  

**3. Create a config.env file inside the `/config` directory and add the following**

   ```bash
   keyId=<Razorpay_API_KeyID>
   keySecret=<Razorpay_API_Secret>
   MONGO_URI=<Your_Unique_MongoDB_Cluster_URI>
   ```  
 **4. Start the server locally using**

   ```bash
   npm run dev
   ```  
   **or in production mode using**
   ```bash
   npm run start
   ```  
<div align="center">
  <img src="https://img.shields.io/badge/%20SERVER%20STARTS%20RUNNING%20ON%20PORT-3000-brightgreen?style=for-the-badge"/>
</div>

---

## Discuss 💬

Have any questions, doubts or want to present your opinions, views? You're always welcome. You can [start discussion](https://github.com/sandip2224/Wallet-X/discussions).

## 🥢 Contact
If you need any help, you can connect with me.

Visit: [sandip2224](https://linkedin.com/in/sandipan0164/)
