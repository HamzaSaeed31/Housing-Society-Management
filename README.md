<h1 align="center">🏘️ Housing Society Management System</h1>

<p align="center">
  <strong>Full-stack MERN platform for managing residents, tenants, properties and payments in a housing society</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
</p>

---

## About

A comprehensive **Housing Society Management System** built on the MERN stack. The platform provides role-based portals for administrators, residents and tenants to manage properties, payments and society operations from a single interface.

## Features

- **Admin Dashboard** — Centralised control for users, properties and payments
- **Property Management** — Add, update and remove property listings
- **Buy and Rent** — Online property purchase and rental workflows
- **Payment System** — Monthly dues, utility bills and fee tracking
- **Property Search** — Filter by location, type, price and description
- **Real-time Notifications** — Push alerts for important society updates
- **Authentication** — Secure login and signup for all user roles

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Stack | MERN |

## Project Structure

```
backend/   Node.js + Express API
hsms/      React frontend application
```

## Getting Started

### Prerequisites
- Node.js 18+
- MongoDB (local or Atlas)

### Installation

```bash
git clone https://github.com/HamzaSaeed31/Housing-Society-Management.git
cd Housing-Society-Management

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../hsms
npm install
```

### Running

```bash
# Start backend (from /backend)
npm start

# Start frontend (from /hsms)
npm start
```

Open `http://localhost:3000` in your browser.
