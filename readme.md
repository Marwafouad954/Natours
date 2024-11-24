# Natours Application

Built using modern technologies: node.js, express, mongoDB, mongoose

Natours is a tour booking web application, The app uses Node.js, Express and MongoDB to create a RESTful API and a dynamic website. The app also implements authentication, authorization, security, payments and email features.

## :rocket: Getting Started

To run this project locally, you need to have Node.js and MongoDB installed on your machine.

### Prerequisites

- Node.js
- MongoDB
- NPM 
- JavaScript

### Installation

1. Clone this repo to your local machine using `git clone https://github.com/<your-username>/natours.git`.
2. Go to the project directory using `cd natours`.
3. Install the dependencies using `npm install` or `yarn install`.
4. Create a `.env` file in the root folder and add the following environment variables:

`
NODE_ENV=development
PORT=3000
DATABASE=<your-mongodb-connection-string>
DATABASE_PASSWORD=<your-mongodb-password>
JWT_SECRET=<your-jwt-secret>
JWT_EXPIRES_IN=90d
JWT_COOKIE_EXPIRES_IN=100
EMAIL_USERNAME=<your-email-username>
EMAIL_PASSWORD=<your-email-password>
EMAIL_HOST=<your-email-host>
EMAIL_PORT=<your-email-port>
EMAIL_FROM=<your-email-address>
STRIPE_SECRET_KEY=<your-stripe-secret-key>`

Run the app using npm start or yarn start.<br> Open your browser and go to http://localhost:3000.<br> 

### :sparkles: Features
User registration and login with JWT authentication<br> Password reset with email verification<br>
User roles and permissions<br> Searching for tours (Filtering & Sorting)<br> Tour creation, update and deletion<br> Tour image upload and processing<br> Tour ratings and reviews<br> Tour booking with Stripe integration<br> Booking confirmation and invoice email<br> Error handling and logging<br>
### :hammer_and_wrench: Technologies
Node.js<br> Express<br> MongoDB<br> Mongoose<br> Bcrypt<br> Jsonwebtoken<br> Validator<br> Stripe<br> Sendgrid<br> Nodemailer<br> Multer<br> Sharp<br> Morgan<br> Helmet<br> Xss<br>
