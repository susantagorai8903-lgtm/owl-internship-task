# Task-2

This project is a Flask-based web application with the following structure:

## Project Structure
```
Task-2/
├── app.py               # Main application file
├── requirements.txt     # Python dependencies
├── instance/            # Instance folder for configurations
├── static/              # Static files (CSS, JS, images, etc.)
├── templates/           # HTML templates
│   └── index.html       # Homepage template
```

## Description
The application is a simple web app that uses Flask and SQLAlchemy. It includes a form to submit user data, which is stored in a SQLite database.

### Features
- **Homepage**: Displays the main page (`index.html`).
- **Form Submission**: Allows users to submit their details, which are saved in the database.
- **SQLite Database**: Stores user information.

## Installation
1. Clone the repository or download the project files.
2. Navigate to the project directory.
3. Create a virtual environment and activate it:
   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate  # On Windows
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```bash
   python app.py
   ```
2. Open your browser and navigate to `http://127.0.0.1:5000/`.

## Dependencies
- Flask
- Flask-SQLAlchemy

## License
This project is licensed under the MIT License.