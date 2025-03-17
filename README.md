<h1 align="center">Movie Ticket Reservation KBA-Project</h1>

## Project Description
Movie ticket booking web application with MERN stack (MongoDB, Express, React, NodeJS) & Tailwind CSS and Docker

## Technologies
* React JS
* Tailwind CSS
* Vite
* NodeJS
* Mongoose
* Express
* MongoDB
* Docker

## Guide

### 🧩 Role / Feature

There are 3 roles on this website with corresponding permissions:

| Role  | Permisson / Feature |
|-------------|-------------|
|👀 Viewer (Not logged in)  | **1. View released showtimes by choosing from** <br> &emsp;- Movie in home page <br>  &emsp;- Cinema's theater in cinema page <br> &emsp;- Cinema's schedule in schedule page <br> **2. View released showtimes for today and the future** <br> **3. View seats for released showtimes on the showtime page**|
|👤 User   | **1. All Viewer permissions** <br> **2. Purchase tickets on the showtime page** <br> **3. View purchased tickets on the ticket page**|
|👑 Admin   | **1. All User permissions** <br> **2. View all showtimes for any date** <br> **3. Manage cinemas** <br> **4. Manage theaters** <br> &emsp;- View theater's row, column, seats information <br> **5. Manage showtimes** <br> &emsp;- Search & filter & sort showtimes <br> &emsp;- View details of booked seats <br> **6. Manage movies** <br> **7. Manage user & admin**|

## How to run the app
1. Download the code
2. Start server side
```
cd server
npm install
npm start
```
3. Start client side
```
cd client
npm install
npm run dev
```
