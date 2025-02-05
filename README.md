# FlexiHub: A Fiverr Clone

FlexiHub is a comprehensive freelance services marketplace platform built using the MERN stack. It replicates the core functionalities of Fiverr, allowing users to offer, discover, and purchase freelance services across various domains.

## Key Features

### User Roles
- **Freelancers**: Create and manage service offerings ("gigs"), track orders, and communicate with clients.
- **Clients**: Search for services, place orders, and communicate with freelancers.

### Core Functionalities
1. **User Authentication**: Secure signup/login using JSON Web Tokens (JWT).
2. **Service Listings (Gigs)**: Freelancers can create, update, and manage their gigs with detailed descriptions, pricing, and delivery time.
3. **Search and Filtering**: Clients can search gigs by keywords, categories, ratings, and other filters.
4. **Order Management**: Seamless ordering process with real-time updates on order status.
5. **Messaging System**: Direct communication between freelancers and clients for collaboration.
6. **Ratings and Reviews**: Clients can rate and review completed gigs to ensure service quality.
7. **Payment Integration**: Simulated payment system for managing transactions securely.
8. **Admin Dashboard**: Manage platform activities, including user accounts, gig moderation, and dispute resolution.

### Advanced Features
- **Real-time Notifications**: Instant updates for new orders, messages, and system alerts.
- **Responsive Design**: Optimized for mobile and desktop experiences.
- **Analytics Dashboard**: Insights into user engagement, revenue, and other metrics (for admin users).

## Technologies Used

### Front-End
- **React.js**: For building a dynamic and responsive user interface.
- **SCSS**: For styling and ensuring a polished user experience.

### Back-End
- **Node.js**: For server-side logic.
- **Express.js**: For building RESTful APIs.

### Database
- **MongoDB**: For storing user data, gig details, and order history.

### Additional Tools
- **JWT**: For authentication.
- **Mongoose**: For MongoDB schema modeling.
- **Socket.IO**: For real-time communication.

## Installation and Setup

### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/username/flexihub.git
   ```
2. Navigate to the project directory:
   ```bash
   cd flexihub
   ```
3. Install dependencies for both the client and server:
   ```bash
   cd client && npm install
   cd ../server && npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the `server` folder.
   - Add the following variables:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_KEY=your_jwt_secret
     ```
5. Start the application:
   - Backend:
     ```bash
     cd server && npm start
     ```
   - Frontend:
     ```bash
     cd client && npm run dev
     ```
6. Access the application at `http://localhost:3000`.

## Project Structure
```
FlexiHub/
├── client/          # React frontend
├── server/          # Node.js backend
├── README.md        # Project documentation
└── .env             # Environment variables
```

## Acknowledgements
FlexiHub is inspired by Fiverr and aims to provide a similar seamless freelance service experience with added flexibility and customizations.

---

Feel free to reach out with suggestions or feature requests to make FlexiHub even better!