\# Software Project Management - Final Project Backend

This is the backend application for the final project in the Software Project Management subject. It has been built using Node.js and Express.js and provides an API for the frontend React application.

The backend API is currently hosted on [Render](https://www.render.com/).

\## Installation and Local Development

Follow the steps below to install and run the application in your local environment.

\### Step 1: Clone the repository

\```bash
git clone https://github.com/PuvaanRaaj/SoftwareProjectManagement-BackEnd.git
\```

\### Step 2: Navigate into the project directory

\```bash
cd SoftwareProjectManagement-BackEnd
\```

\### Step 3: Install the necessary dependencies

\```bash
npm install
\```

\### Step 4: Duplicate the .env example to .env

Create a new file in the project root directory named `.env`. Copy the contents of the `.env.example` file into the `.env` file.

\### Step 5: Create a MongoDB Database

Create a new MongoDB database for this project. If you are unfamiliar with this process, [watch this video tutorial](https://youtu.be/KD1vGsymHuA).

\### Step 6: Create an account at Stripe

Create an account at [Stripe](https://stripe.com/).

\### Step 7: Fill up the data in the .env file

Ensure to fill up the necessary data in the `.env` file, such as the MongoDB URI, Stripe account details.

\### Step 8: Update the Stripe public key in app.js

Find the place in `app.js` where the Stripe public key is defined and replace it with your Stripe public key.

\### Step 9: Start the Application

You can start the application with either of the following commands:

\```bash
npm run start
\```

or

\```bash
nodemon app.js
\```

After starting the application, take the localhost link and paste it into the frontend application to connect both.

\### Step 10: Full Backend Setup

For a detailed guide on setting up the entire backend, you can watch [this video tutorial](https://youtu.be/vqWm6nyc2YE).

\## Available Scripts

In addition to `npm start`, the following scripts are available:

\### `npm test`

This launches the test runner in interactive watch mode.

\### `npm run build`

This builds the app for production.

\### `npm run eject`

This removes the single build dependency from your project.

\## API Endpoints

Please add a section here detailing your API endpoints, request/response formats, and any other information necessary for using the API.

\## License

\```bash
MIT License

Copyright (c) 2023 Puvaan Raaj

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
\```
