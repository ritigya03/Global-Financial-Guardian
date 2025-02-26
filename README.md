# Global-Financial-Guardian

Overview

Global Financial Guardian is an AI-powered financial management platform that simplifies tax compliance, provides personalized investment insights, and helps prevent financial losses. It is designed to assist students, freelancers, small businesses, and retirees in navigating complex tax regulations both in India and globally.

Features

AI-Powered Tax Automation: Automatically calculates taxes and deductions based on global tax rules.

Personalized Financial Insights: Provides tailored investment suggestions to minimize risks and maximize returns.

Fraud Detection: Identifies potential financial risks and prevents fraud.

GST & Compliance Assistance: Simplifies tax filing for businesses with automated GST calculations.

User-Friendly Dashboard: Intuitive UI for managing finances easily.

Tech Stack

Backend: Node.js, Express.js

Database: MongoDB (Atlas + Compass)

Frontend: React.js (to be implemented later)

Authentication: JWT-based authentication

Hosting: GitHub, Cloud (to be decided)

## Installation

### Clone the repository:
```sh
git clone https://github.com/your-username/Global-Financial-Guardian.git
```

Navigate to the backend folder:

```sh
cd backend
```
Install dependencies:
```sh
npm install
```
Set up MongoDB Atlas:

Create a MongoDB cluster on MongoDB Atlas

Whitelist your IP address

Get the connection string and update .env
```sh
MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your-secret-key
```
Start the server:
```sh
npm start
```
API Endpoints

User Routes

Get all users: GET /api/users

Add a user: POST /api/users/add

{
  "name": "Ritigya Gupta",
  "email": "ritigya@example.com",
  "password": "123456"
}

Future Enhancements

Implement AI-driven investment predictions.

Add multi-country tax rule support.

Develop a mobile application.

Improve fraud detection algorithms.




