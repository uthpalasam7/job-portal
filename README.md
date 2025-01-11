# Job Portal

## Overview
The Job Portal Application is a React-based frontend application that allows users to interact with job posts through a user-friendly interface. The backend can be connected separately to provide API endpoints for CRUD (Create, Read, Update, Delete) operations on job posts.

## Features
- View all job posts.
- Search for jobs by keyword.
- Create new job posts.
- Update existing job posts.
- Delete job posts.

## Project Structure
```
job-portal/
├── src/        # React application source code
├── public/     # Public assets
├── package.json
├── README.md
```

## Prerequisites
- Node.js

## Setup

### Frontend (React Application)
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the React application:
   ```bash
   npm start
   ```
3. The frontend will be accessible at `http://localhost:3000`.

## Backend Integration
- The backend for this application is available in a separate repository: [Spring Boot REST Backend](https://github.com/uthpalasam7/spring-boot-rest).
- Clone and set up the backend repository by following its instructions.
- Update the API base URL in the environment configuration (e.g., `.env` file or constants in the source code) to match the backend's URL.

## How It Works
1. **View All Jobs:**
   - The React application fetches job data from the `/jobPosts` API endpoint and displays it in a list view.

2. **Search Jobs:**
   - Users can search for jobs by entering keywords, and the application queries the backend API.

3. **Add, Update, Delete Jobs:**
   - Forms and buttons are provided in the UI to add, edit, or delete job posts by sending requests to the backend API.

## Future Enhancements
- User authentication and role-based access.
- Enhanced search with filters (e.g., location, category).
- Pagination for job listings.
- Improved UI/UX design.

## License
This project is licensed under the MIT License.
