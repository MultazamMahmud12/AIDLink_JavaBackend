# AIDLink Java Backend & Frontend

## Project Overview
AIDLink is a platform for managing humanitarian aid events, organizations, and recipients. It provides a modern web interface for donors, organizations, and administrators to collaborate and respond to crises efficiently.

## Technologies Used
- **Frontend:** React (with Vite)
- **Backend:** Java Spring Boot & Node.js (Express, MongoDB)
- **Database:** MongoDB
- **Other:** Cloudinary (image uploads), Maven (Java build)

## Features
- Event management (create, update, delete, view events)
- Organization registration, review, and approval
- Recipient details and donation options
- Admin dashboard for managing organizations and events
- Secure document upload (certificates, licenses, audit reports)
- Responsive UI for donors, organizations, and admins

## Folder Structure
```
AIDLink/
  backend/      # Java Spring Boot & Node.js backend
    src/
      config/           # Cloudinary config
      events/           # Event controllers, models, routes
      main/java/com/    # Java source code
      resources/        # Application properties
      test/java/com/    # Java tests
    package.json        # Node.js backend scripts
    pom.xml             # Maven config
  frontend/     # React + Vite frontend
    public/             # Static assets & data
    src/
      components/       # Shared React components
      pages/            # Main app pages (Home, Registration, Admin, Events, Recipients)
      routers/          # React Router setup
      utils/            # Helper functions
    package.json        # Frontend scripts
    vite.config.js      # Vite config
```

## Setup Instructions

### Prerequisites
- Node.js & npm
- Java (JDK)
- Maven
- MongoDB (local or cloud)

### Backend Setup
1. Navigate to `AIDLink/backend`
2. Install Node.js dependencies:
   ```sh
   npm install
   ```
3. Configure environment variables in `.env`
4. Start Node.js backend:
   ```sh
   npm start
   ```
5. For Java backend:
   ```sh
   mvn spring-boot:run
   ```

### Frontend Setup
1. Navigate to `AIDLink/frontend`
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend:
   ```sh
   npm run dev
   ```

## Usage
- Access the frontend at `http://localhost:5173` (default Vite port)
- Backend API runs at `http://localhost:5000` (Node.js) and `http://localhost:8080` (Spring Boot)
- Register organizations, manage events, and donate to recipients via the web interface

## Contribution
Feel free to fork the repository, create issues, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
Specify your license here (e.g., MIT, ISC).

## Contact
Multazam Mahmud 
01977108849
https://www.linkedin.com/in/multazam-mahmud-8abb751bb/
