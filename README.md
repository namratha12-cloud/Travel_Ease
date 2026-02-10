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

## 🛠️ Technologies
- Node.js & Express
- MySQL Database
