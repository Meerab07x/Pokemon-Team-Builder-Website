# Pokémon Team Builder Website

## Installation

1. Download the ZIP and extract the project.
2. Open a terminal and navigate into the folder:

   ```bash
   cd <foldername>
   ```
3. Install frontend dependencies:

   ```bash
   npm install
   ```
4. Install backend dependencies:

   ```bash
   pip install flask flask-cors mysql-connector-python bcrypt flask_jwt_extended
   ```

   If that doesn't work, try:

   ```bash
   py -3 -m pip install --user flask flask-cors mysql-connector-python bcrypt flask_jwt_extended
   ```

## Running the Backend

Open VS Code and in the terminal run:

```bash
python app.py   # or py app.py
# Mac users:
python3 app.py
```

This starts the Flask backend.

## Database Setup

* Install and open **XAMPP**
* Start **Apache** and **MySQL**
* Go to `localhost/phpmyadmin`
* Create the database using the included SQL file
* User logins are stored securely (passwords are hashed)

## Tech Stack

React.js • Node.js • Flask • MySQL

❤️
