# MERN Stack CRUD Application

This is a full-stack CRUD (Create, Read, Update, Delete) application built using the MERN stack (MongoDB, Express.js, React, and Node.js).

## Features
- **Create:** Add new records to the database.
- **Read:** View all records.
- **Update:** Edit existing records.
- **Delete:** Remove records from the database.
- **Routing:** Utilizes React Router for navigation.
- **Database:** MongoDB for data storage.
- **API:** Express.js for backend API routes.
- **Frontend:** React for building the user interface.
- **Styling:** Basic CSS for styling.
- **Environment Variables:** Managed with dotenv.
- **CORS:** Enabled for cross-origin requests.

## Prerequisites
- Node.js and npm installed.
- MongoDB installed and running.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Farzeen002/Mern_Crud.git
    cd your-repo-name
    ```

2. **Setup the backend:**
    ```sh
    cd backend
    npm install
    ```

3. **Setup the frontend:**
    ```sh
    cd ../frontend
    npm install
    ```

## Configuration

1. **Backend:**
    - Create a `.env` file in the `backend` folder with the following content:
      ```env
      URI=your-mongodb-uri
      PORT=your-port
      ```

## Running the Application

1. **Start the backend server:**
    ```sh
    cd backend
    npm start
    ```

2. **Start the frontend development server:**
    ```sh
    cd ../frontend
    npm start
    ```

## Project Structure

your-repo-name/
│
├── backend/
│ ├── node_modules/
│ ├── routes/
│ │ └── userRoute.js
│ ├── .env
│ ├── app.js
│ ├── package.json
│ └── ...
│
├── frontend/
│ ├── node_modules/
│ ├── src/
│ │ ├── components/
│ │ │ ├── Create.js
│ │ │ ├── Read.js
│ │ │ ├── Update.js
│ │ │ ├── NavBar.js
│ │ ├── App.js
│ │ ├── App.css
│ │ └── ...
│ ├── public/
│ ├── package.json
│ └── ...
│
└── README.md


## Usage

- **Create Record:** Navigate to `/` to create a new record.
- **Read Records:** Navigate to `/all` to view all records.
- **Update Record:** Navigate to `/:id` to update a specific record (replace `:id` with the actual record ID).

## Contributing

Feel free to fork this repository and contribute by submitting a pull request. Any contributions, suggestions, or improvements are welcome!

## Contact

For more information, please contact:

**Farzeen Ahmed**  
[Portfolio](https://farzeens-portfolio.netlify.app/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
