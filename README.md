# Trip-To-Utopia

## Overview
Trip-To-Utopia is a comprehensive full-stack web application developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to:
- Search for hotels with relevant details such as ratings and locations.
- Book flights by querying flight details.
- Explore tourist destinations and manage bookings.
- Create and manage user accounts securely.

The application provides a seamless and user-friendly interface for travel planning and booking services.

---

## Features
- **User Authentication**: Login and signup functionality with secure password storage.
- **Hotel Search and Booking**: Displays available hotels with ratings and addresses.
- **Flight Booking**: Allows users to search for and book flights.
- **Tourist Locations**: Fetches and displays tourist destinations.
- **Booking Management**: Tracks and displays user bookings.

---

## How It Works

1. **User Authentication**:
   - Users can sign up by providing their email, username, and password.
   - Login functionality allows existing users to securely access their account.
   - Authentication is handled using hashed passwords and sessions.

2. **Search for Hotels and Flights**:
   - Users can search for hotels by location and view details like ratings, photos, and addresses.
   - Flight booking allows users to input origin, destination, and travel dates to get flight details.

3. **Book and Manage**:
   - Users can make hotel reservations or book flights.
   - Bookings are tracked in the user profile, allowing users to view their history and manage reservations.

4. **API Integration**:
   - The backend interacts with external APIs to fetch real-time data for flights and hotels.
   - MongoDB is used to store user accounts and booking details.

5. **Frontend**:
   - The user-friendly interface ensures smooth navigation between sections.
   - Components like cards dynamically display data fetched from the backend.

---

## Important Setup Steps
1. **Backend**:
   - Install dependencies:
     ```bash
     npm install
     ```
   - Add a `.env` file with:
     ```env
     CONNECTION_URL=mongodb://<your_mongo_db_connection_string>
     PORT=3002
     ```
   - Start the backend server:
     ```bash
     npm start
     ```

2. **Frontend**:
   - Navigate to the frontend directory and install dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
     ```

---

## File Structure
### Backend
- **index.js**: Entry point for the backend server.
- **models**: Contains Mongoose schemas for users, orders, and hotels.
- **routes**: Handles API endpoints for user authentication, hotel bookings, and orders.

### Frontend
- **src/LoginAndSignup**: Contains components for user login and signup.
- **src/components**: Reusable UI components like Navbar and Footer.
- **src/reducer**: Redux reducers for state management.
- **src/state**: Actions and global state configuration.
- **src/webpages**: Main pages for hotels, flights, bookings, and user profile.

---

## Components
- **LoginAndSignup**: Handles user authentication with separate components for login and signup functionalities.
- **Navbar**: Provides navigation links for different sections of the application.
- **Footer**: Displays additional information and links at the bottom of the page.
- **Hotel Cards**: Dynamically render hotel details using API data.
- **Flight Search**: Allows users to search for flights with origin, destination, and date inputs.

---

## Future Enhancements
- Add payment gateway integration for bookings.
- Implement real-time notifications for booking updates.
- Enhance UI with animations and interactive elements.

---

