# Travelwise – Travel & Tourism Website

A modern MERN stack web application for discovering travel destinations and booking tour packages. Travelwise allows users to explore destinations, view reviews, and securely book experiences through a responsive and intuitive interface.

## Features

- Explore and filter travel destinations
- User authentication with JWT
- Admin panel for managing tours, users, and bookings
- Review and rating system
- Responsive design with mobile-first approach

## Folder Structure

```
project-root/
├── backend/
│   ├── controllers/     # Route logic
│   ├── models/          # Mongoose schemas
│   ├── routes/          # Express routers
│   ├── utils/           # Utility functions (e.g., auth)
│   └── index.js         # Entry point
├── frontend/            # React frontend (if available)
└── README.md            # Project documentation
```

## Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js
- Tailwind CSS
- JWT, bcrypt.js

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB Atlas URI or local MongoDB setup

### Installation

1. Navigate to the backend directory:

```bash
cd backend
```

2. Install backend dependencies:

```bash
npm install
```

3. Create a `.env` file and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

4. Start the backend server:

```bash
npm start
```

5. (If applicable) Navigate to the frontend directory and run:

```bash
cd frontend
npm install
npm start
```

## Usage

- Visit `http://localhost:3000`
- Register or log in as a user
- Browse destinations and book packages
- Leave reviews and ratings
- Admins can manage content from their dashboard

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request for improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
