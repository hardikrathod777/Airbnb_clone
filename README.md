
# Airbnb Clone 

## Project Overview

This is an **Airbnb Clone** built using the **Next js , Prisma, mongoDb**. The project includes essential features such as property listing management, user authentication, and booking functionality. The frontend is built with **React** and designed to be fully responsive using **Tailwind CSS** , while the backend is built with **Next js**, **Prisma** to manage property listings, user authentication, and bookings. The **MongoDB** database is used to store all related data.

## Key Features

- **User Authentication**: Secure login and registration using JWT (JSON Web Tokens).
- **Property Listings**: Users can browse, add, edit, and delete property listings.
- **Booking Management**: Users can book properties and manage their bookings.
- **Responsive Design**: The UI is optimized for mobile, tablet, and desktop screens using CSS frameworks like Tailwind CSS .
- **RESTful API**: Backend server with fully implemented API endpoints for CRUD operations on properties, users, and bookings.

## Technologies Used

- **Frontend**: React, Tailwind CSS
- **Backend**: Nextjs, prisma
- **Database**: MongoDB (MongoDB Atlas for cloud)
- **Authentication**: JSON Web Tokens (JWT)
- **State Management**: React Hooks


## Installation Instructions

### Prerequisites

Make sure you have the following installed:
- **NextAuth**
- **Prisma**
- **MongoDB** (or MongoDB Atlas for cloud-based database)
- **Code Editor** (e.g., VSCode)
- **Git** for version control

### Setup and Running the Project Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/airbnb-clone.git
   cd airbnb-clone

## Set up environment variables

**In the root directory, create a .env file with the following values:**
  ```bash
  MONGO_URI=mongodb+srv://yourMongoDBUser:yourMongoDBPassword@cluster0.mongodb.net/airbnb-clone?retryWrites=true&w=majority
  JWT_SECRET=yourJWTSecret
  ```

## Run the project

```bash
npm run dev
```

## Access the application

Open **http://localhost:3000**  in your browser

