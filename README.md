
<<<<<<< HEAD
This repository contains the source code for the **Travel_Ease** backend module, packaged as a ZIP file.

## 📦 Contents

The `Travelease.zip` archive contains a Node.js backend application designed for a bus booking system.

### 📂 Inside the Package

Once extracted, you will find a `backend` directory with the following structure:

- **`server.js`**: The main Express application handling API requests.
- **`db/`**: Contains database configuration files.
- **`node_modules/`**: Pre-installed dependencies (though running `npm install` is recommended).
- **`package.json`**: Project metadata and dependency list.

## � Languages Used
- **JavaScript (Node.js)**: The core logic server-side.
- **SQL**: For database schema definitions and queries.

## 📦 Modules & Dependencies
The project relies on the following npm packages:

| Module | Description |
| :--- | :--- |
| **express** | Fast, unopinionated, minimalist web framework for Node.js. |
| **mysql2** | MySQL client for Node.js, focusing on performance and prepared statements. |
| **cors** | Middleware to enable Cross-Origin Resource Sharing (CORS). |
| **nodemon** | (Dev Dependency) Utility that monitors for changes and automatically restarts the server. |

## � Suggested Workflow

To successfully run and develop this project, follow this workflow:

1.  **🗄️ Database Setup**
    - Install MySQL if not already available.
    - Create a new database named `Travels1`.
    - Create the required tables (`bus`, `booking`, `agency`). *Tip: Look at the SQL queries in `server.js` to infer the schema.*

2.  **⚙️ Configuration**
    - Open `backend/server.js`.
    - Update the `mysql.createConnection` settings (host, user, password) to match your local MySQL setup.

3.  **📦 Installation**
    - Open a terminal in the `backend` folder.
    - Run `npm install` to download dependencies.

4.  **🚀 Development**
    - Start the server in development mode:
      ```bash
      npm run dev
      ```
    - The server will restart automatically when you make code changes.

5.  **🧪 Testing**
    - Use tools like **Postman** or **cURL** to test the API endpoints:
      - `GET http://localhost:7000/search-bus?from=X&to=Y&date=Z`
      - `POST http://localhost:7000/book`

## 🔌 API Features

- **Bus Search**: Find buses by source, destination, and date.
- **Booking Management**: Book tickets with availability checks.
- **Passenger History**: View past bookings.

## 🚀 Getting Started (Quick Run)

1.  **Extract the Archive**: Unzip `Travelease.zip`.
2.  **Navigate**: `cd backend`
3.  **Install**: `npm install`
4.  **Run**: `node server.js`
=======
>>>>>>> 503d60c2b56262e2d7b7327e063240ee816d5482
