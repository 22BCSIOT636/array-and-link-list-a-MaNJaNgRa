[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/jMgR4AG6)
[![Work in MakeCode](https://classroom.github.com/assets/work-in-make-code-8824cc13a1a3f34ffcd245c82f0ae96fdae6b7d554b6539aec3a03a70825519c.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17599562&assignment_repo_type=AssignmentRepo)
# Livestock Tracking and Management System

## Overview
The Livestock Tracking and Management System is a web-based application designed to simplify the process of managing livestock information. It allows users to add, view, update, and delete livestock records. The system consists of a frontend built with HTML and CSS and a backend powered by Node.js and Express.

---

## Features
- **Add Livestock**: Record new livestock details such as name, type, and age.
- **View Livestock**: Display a list of all livestock entries.
- **Update Livestock**: Edit details of an existing livestock record.
- **Delete Livestock**: Remove livestock entries from the system.

---

## Technologies Used
### Frontend
- HTML
- CSS
- JavaScript (for API integration with the backend)

### Backend
- Node.js
- Express.js
- body-parser (for JSON parsing)
- CORS (to allow cross-origin requests)

---

## Project Setup

### Backend Setup
1. **Prerequisites**: Ensure Node.js and npm are installed on your machine.
   ```bash
   node -v
   npm -v
   ```

2. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd livestock-backend
   ```

3. **Install Dependencies**:
   ```bash
   npm install
   ```

4. **Run the Server**:
   ```bash
   node server.js
   ```

5. **API Endpoints**:
   - **GET** `/api/livestock`: Retrieve all livestock records.
   - **POST** `/api/livestock`: Add new livestock. Example payload:
     ```json
     {
         "name": "Bella",
         "type": "Cow",
         "age": 3
     }
     ```
   - **PUT** `/api/livestock/:id`: Update livestock details by ID.
   - **DELETE** `/api/livestock/:id`: Remove a livestock record by ID.

### Frontend Setup
1. **Open the Frontend**:
   - Open the `index.html` file in a browser.

2. **Connect to Backend**:
   - Ensure the backend server is running at `http://localhost:3000`.
   - The frontend will fetch data from the backend to display livestock information.

---

## File Structure
```
project-folder/
|-- backend/
|   |-- server.js          # Backend server file
|   |-- package.json       # Node.js configuration
|-- frontend/
|   |-- index.html         # Frontend structure
|   |-- styles.css         # Frontend styling
```

---

## Usage
1. Start the backend server:
   ```bash
   node server.js
   ```

2. Open the `index.html` file in your browser.

3. Use the interface to add, view, or delete livestock records.

---

## Screenshots

### Add Livestock
A form to add new livestock records with fields for name, type, and age.

### View Livestock List
A dynamic list that displays all livestock records fetched from the backend.

---

## Future Enhancements
- Implement user authentication for secure access.
- Add search and filter functionality for livestock records.
- Integrate a database (e.g., MongoDB) to persist data.
- Build a more interactive UI with advanced JavaScript frameworks like React or Vue.js.

---

## License
This project is licensed under the MIT License. Feel free to use and modify it as needed.

---

## Author
Aman 
amanjangra855@gmail.com

