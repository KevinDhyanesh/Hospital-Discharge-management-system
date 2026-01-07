# Hospital Discharge Management System

A comprehensive system designed to automate and streamline the hospital discharge process, improving patient outcomes and operational efficiency.

## Features

- **Real-time Hospital Department Visualization**: Interactive network view showing connections between departments
- **Patient Discharge Dashboard**: Track discharge progress with a comprehensive step-by-step process
- **Departmental Patient Management**: View and manage pending discharges by department
- **Role-based Access**: Separate interfaces for doctors and patients

## Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Express.js, Node.js
- **Database**: MongoDB
- **Real-time Communication**: Socket.io

## Installation

1. Clone the repository
2. Install dependencies:
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables:
   - Create a `.env` file in the backend directory
   - Add the following variables:
   ```
   PORT=5001
   MONGODB_URI=mongodb://localhost:27017/hospital_discharge_system
   ```

4. Start the application:
```bash
# Start MongoDB
mongod --dbpath ~/data/db

# Start the backend
cd backend
npm start

# Start the frontend
cd ../frontend
npm run dev
```

5. Access the application:
   - Frontend: http://localhost:3001
   - Backend API: http://localhost:5001

## Login Credentials

For demo purposes, use these credentials:
- **Doctor**: Username: `doctor`, Password: `password`
- **Patient**: Username: `patient`, Password: `password`

## Project Structure

```
hospital-discharge-system/
├── backend/                  # Express.js server
│   ├── src/                  # Backend source code
│   └── .env                  # Environment variables
└── frontend/                 # Next.js client
    ├── src/                  # Frontend source code
    ├── pages/                # Next.js pages
    └── public/               # Static assets
```

## Screenshots

[Add screenshots of your application here]

## License

MIT 
