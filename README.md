## "Building an E-learning app where course minted NFTs and users pay by Crypto."

<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" width="100" /> 
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" width="100" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" width="100" />
</p>

<p align="right">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" width="150" />
  <img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white" width="100" />
  <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" width="100" />
  <img src="https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white" width="100" />
</p>

### ~ Fully Fledged, Automated and Responsive Multi Page Application.
----

## Getting Started

- Clone the repo to your local environment, you have to seperately install all the dependencies for backend and frontend. 

---

-> For Backend, go to the backend folder (cd Backend) and run 
``` npm i ```

  - Use [MongoDB Cloud Storage](https://www.mongodb.com/) or you can Install [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/)
  - add your environmental variables
  - Create a .env file in the root directory of the backend folder and add your tokens there with respect to the config files variables.
 
    - ACCESS_TOKEN_SECRET = "somesecretlongstring"
    - ACCESS_TOKEN_LIFE = 10H
    - REFRESH_TOKEN_SECRET = "somesecretlongstringxyz"
    - REFRESH_TOKEN_LIFE = 10H
    - SENDGRID_KEY = "CreateAccountonSendGridaccesstheotpandgetthekeystringhere"
    - MONGO_DATABASE = "CreateAccountonMongoDBAtlascreateclustergetthekeystringhere"
    - OAuth2Client = ""
    - STRIPE_SECRET_TOKEN = ""
    - REDIS_HOST = ""
    - REDIS_PASSWORD = "" 
    - REDIS_PORT = ""
---

### [Note: Make sure the .env files variables matches with that of the config files.]
  
---
 
-> For Frontend, go to the frontend folder (cd Front-end) and run
``` npm i ```

- To run a development environment, you can use the `npm start` command. This will start up a development web server on port 3000 for frontend, and a nodemon-watched API server on port 8080.

---

### [Note: you have to do npm start for backend and frontend seperately.]

---

#### Implemented Features Overview:

-For Student's
- [x] Authentication with signup, login, OTP, resend OTP, forgot password (fully validated with bootstrap alerts)
- [x] Google authentication using react-google-login and google auth-library
- [x] Payment gateway -Stripe integrated with backend to buy courses with Net Banking / Card.
- [x] Redux store to easily manage states
- [x] Homepage with courses (categorically)
- [x] Recommended Courses based on user's preferences (Recommendation System)
- [x] Rating of Courses 
- [x] Bookmarked Courses where users can remove or add a bookmark
- [x] Download resources (pdf - notes)
- [x] Responsive React Video player for videos
- [x] Progress bar
- [x] CoursePage with all the content of the course
- [x] Searching based on course and teacher
- [x] Real Time Live Group classes

-For Teacher's
- [x] Proper Authentication system with signup, login, OTP, resend OTP, forgot password (fully validated with bootstrap alerts)
- [x] Fully validated uploading form with description, title, Image and other details
- [x] CKEditor for writing in textbox with abilities to add different headings, paragraphs, bold, italics, link, tables, sizes etc
- [x] Teacher can upload up to 5 videos with an upload bar to show progress
- [x] Teachers can see their uploaded courses
- [x] Teachers can delete their course
- [x] Teachers can edit their course
