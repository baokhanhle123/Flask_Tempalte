# Project Setup Instructions

## Virtual Environment Setup

To create and activate a virtual environment, follow these steps:

```bash
# Create a virtual environment
py -3 -m venv venv

# Activate the virtual environment
venv\Scripts\activate
```

## Installing Dependencies

To install all required dependencies, use the following commands:

```bash
# Save current dependencies to requirements.txt
python -m pip freeze > requirements.txt

# Install dependencies from requirements.txt
pip install -r requirements.txt
```

## Development Mode

To enable Flask development mode (which includes features like auto-reload and detailed error messages), run:

```bash
# Enable Flask debug mode
set FLASK_DEBUG=1
```

## Running the Application

To run the Flask application locally:

```bash
# Start the Flask development server
flask run
```

## Deployment

To deploy your application to Heroku, commit your changes and push them to the Heroku remote:

```bash
# Stage all changes
git add .

# Commit changes with a message
git commit -m "Your commit message"

# Push to Heroku
git push heroku master
```

---

Make sure you have the Heroku CLI installed and are logged in before deploying.