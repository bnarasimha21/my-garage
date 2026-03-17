# My Garage

A vehicle management web application for tracking and organizing personal project links and services. Built with Flask and featuring a CI/CD pipeline with Jenkins integration, SonarQube code analysis, and automated testing.

## Features

- **Dashboard View** -- Central landing page with quick-access links to various services
- **Configurable URLs** -- Centralized constants file for managing service endpoints
- **Automated Testing** -- Unit tests and functional tests included
- **CI/CD Pipeline** -- Full Jenkins pipeline with build, code analysis, unit testing, and deployment stages
- **SonarQube Integration** -- Automated code quality analysis

## Tech Stack

- **Language:** Python 3
- **Framework:** Flask 1.1.2
- **Templating:** Jinja2 (Flask templates)
- **Styling:** Custom CSS
- **CI/CD:** Jenkins (Jenkinsfile)
- **Code Quality:** SonarQube

## Setup / Installation

### Prerequisites

- Python 3.x
- pip

### Local Development

```bash
git clone https://github.com/bnarasimha21/my-garage.git
cd my-garage
pip install -r requirements.txt
python app.py
```

The application will start at `http://localhost:5000`.

## Usage

Open the app in your browser to view the dashboard. The landing page provides links to:

- Jenkins CI/CD server
- Blog
- Scrum Guide app
- Code Snippets platform
- Resume page

### Running Tests

```bash
# Unit tests
python3 -m unittest tests/unittests/testapp.py

# Functional tests
python3 -m unittest tests/functionaltests/testmygarage.py
```

## License

MIT
