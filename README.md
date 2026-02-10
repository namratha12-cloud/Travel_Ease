# Travel_Ease Module

This repository contains the source code for the **Travel_Ease** backend module, packaged as a ZIP file.

## 📦 Contents

The `Travelease.zip` archive contains a Node.js backend application designed for a bus booking system.

### 📂 Inside the Package

Once extracted, you will find a `backend` directory with the following structure:

- **`server.js`**: The main Express application handling API requests.
- **`db/`**: Contains database configuration files.
- **`node_modules/`**: Pre-installed dependencies (though running `npm install` is recommended).
- **`package.json`**: Project metadata and dependency list.

## 🚀 Getting Started

1.  **Extract the Archive**:
    Unzip `Travelease.zip` to your desired location.

2.  **Navigate to the Backend**:
    ```bash
    cd backend
    ```

3.  **Install/Update Dependencies**:
    ```bash
    npm install
    ```

4.  **Configure Database**:
    - Ensure MySQL is running on port 3306.
    - Create a database named `Travels1`.
    - Update credentials in `server.js` if necessary.

5.  **Run the Server**:
    ```bash
    node server.js
    ```


## 🔌 Features

- **Bus Search**: Find buses by source, destination, and date.
- **Booking Management**: Book tickets with availability checks.
- **Passenger History**: View past bookings.

<<<<<<< HEAD
## 💻 Languages Used
- **JavaScript (Node.js)**

## 📦 Modules & Dependencies
The project relies on the following npm packages:

| Module | Description |
| :--- | :--- |
| **express** | Fast, unopinionated, minimalist web framework for Node.js. |
| **mysql2** | MySQL client for Node.js, focusing on performance and prepared statements. |
| **cors** | Middleware to enable Cross-Origin Resource Sharing (CORS). |
| **nodemon** | (Dev Dependency) Utility that monitors for changes and automatically restarts the server. |
=======
## 🛠️ Technologies
- Node.js & Express
- MySQL Database
>>>>>>> f1ed3d90c259ca492955181c07f0e881c8084125
