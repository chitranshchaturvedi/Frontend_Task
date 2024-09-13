# Rental Property Management Application

This full-stack rental property management application was built using React, Node.js, Express, and MongoDB (MERN stack). The app allows users to list properties for rent, browse listings by categories, and manage trips, reservations, and wishlists.

## Features
- User registration and login
- Create and manage property listings
- Browse and search for properties by categories and keywords
- View detailed property information
- Manage trips, wishlists, and reservations
- Responsive design with a clean and user-friendly interface

## Pages & Routes

The HomePage (/) displays general information and listings of trips available for users to browse.
The RegisterPage (/register) allows new users to sign up and create an account.
The LoginPage (/login) is where existing users can log in to access their accounts.
The CreateListing page (/create-listing) lets users create a new property listing or trip by providing necessary details.
The ListingDetails page (/properties/:listingId) displays specific information about a particular property or trip using its unique ID.
The CategoryPage (/properties/category/:category) shows listings filtered based on a specific category like type, location, or other criteria.
The SearchPage (/properties/search/:search) is where users can view search results for properties or trips based on their input.
The TripList (/:userId/trips) displays a list of all the trips created or joined by a specific user.
The WishList (/:userId/wishList) allows users to view the list of properties they have saved or marked for future reference.
The PropertyList (/:userId/properties) shows all the properties or trips owned or listed by the user.
The ReservationList (/:userId/reservations) displays reservations made by the user for any properties or trips.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/chitranshchaturvedi/Frontend_task
Install the dependencies:

bash
Copy code
cd rental-app
npm install
Set up the backend server (assuming you have already set up the Node.js, Express, and MongoDB backend):

bash
Copy code
cd backend
npm install
npm start
Start the React frontend:

bash
Copy code
cd frontend
npm start
Open http://localhost:3000 to view the application in the browser.

Project Structure
frontend/: Contains the React frontend code.
backend/: Contains the Express and MongoDB backend code.
models/: Mongoose models for the application (e.g., User, Listing).
routes/: API routes for handling requests to the backend.
pages/: Contains all the React pages such as HomePage, RegisterPage, LoginPage, etc.
components/: Reusable components across different pages.
Technologies Used
Frontend: React, React Router, Axios, Tailwind CSS
Backend: Node.js, Express, MongoDB, Mongoose
Other: React Toastify for notifications, bcrypt for password hashing
How to Contribute
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit and push your changes (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

csharp
Copy code

This README provides an overview of the app, including setup instructions, routes, and features.
