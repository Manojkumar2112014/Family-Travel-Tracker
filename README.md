# Visited Countries Tracker

## Overview
The Visited Countries Tracker is a web application built using Node.js, Express.js, and PostgreSQL. It allows users to create profiles, switch between them, and track countries they have visited. The application dynamically updates the interface based on user preferences, showcasing real-time data management and user-specific customization.

## Features
- User Management: Create new profiles, switch between users, and maintain user-specific data.
- Country Tracking: Add countries to a user's visited list by entering the country name.
- Dynamic Interface: Interface updates with the current user's preferred color and visited countries list.

## Technologies
- Node.js
- Express.js
- PostgreSQL
- EJS (Embedded JavaScript templates)

## Installation
1. Clone the repository: `git clone https://github.com/your-username/visited-countries-tracker.git`
2. Navigate to the project directory: `cd visited-countries-tracker`
3. Install dependencies: `npm install`
4. Set up PostgreSQL database and update connection settings in the code.

## Usage
1. Start the server: `npm start`
2. Open your browser and navigate to `http://localhost:3000`.

## Project Structure
- `app.js`: Main server file.
- `views/`: Contains EJS templates for rendering pages.
- `public/`: Static files like CSS and JavaScript.
- `routes/`: Defines application routes.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
