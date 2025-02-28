# User Authentication System

This is a simple user authentication system built with Flask. It includes features for user registration, login, and logout, with password hashing and session management.

## Features

- User registration with unique username and email
- User login with session management
- Password hashing using Flask-Bcrypt
- Flash messages for user feedback
- Basic styling with CSS

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/sheeerr/user-authentication-system.git
    cd user-authentication-system
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the application:
    ```sh
    python app.py
    ```

## Usage

- Open your web browser and go to `http://127.0.0.1:5000/`
- Register a new user account
- Log in with the registered account
- Access the home page and log out

## Project Structure

GitHub Copilot
Sure, here is the updated README.md with the project structure included:

user-authentication-system/ 
├── instance/
│ └── users.db
├── static/
│ ├── facebook-logo-facebook-icon-transparent-free-png.webp 
│ ├── Google_Icons-09-512.webp 
│ ├── Screenshot_1-1-2025_192350_images-platform.99static.com-removebg-preview.png
│ └── style.css
├── templates/ 
│ ├── login.html 
│ └── signup.html
├── .gitattributes
├── .gitignore
├── app.py 
├── LICENSE 
└── README.md

## License

This project is licensed under the MIT License. See the [LICENSE](http://_vscodecontentref_/6) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/)
- [Flask-Bcrypt](https://flask-bcrypt.readthedocs.io/en/latest/)
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/)
- [Flask-Login](https://flask-login.readthedocs.io/en/latest/)

