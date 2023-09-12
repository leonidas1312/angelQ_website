# angelQ_website

 
## Installation

### Prerequisites

- Python 3.x
- pip
- virtualenv (optional)

### Steps

1. **Clone the repository**
    ```bash
    git clone https://github.com/leonidas1312/angelQ_website/tree/main
    ```

2. **Navigate to the project directory**
    ```bash
    cd angelQ_website
    ```

3. **Create a virtual environment (optional)**
    ```bash
    virtualenv venv
    ```

4. **Activate the virtual environment**
    - On Windows:
        ```bash
        .\venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```bash
        source venv/bin/activate
        ```

5. **Install the required packages**
    ```bash
    pip install django
    ```

6. **Apply migrations**
    ```bash
    python manage.py migrate
    ```

7. **Run the development server**
    ```bash
    python manage.py runserver
    ```

## Usage

1. Open your web browser and go to `http://127.0.0.1:8000/`
2. Explore the app!

## Project Structure

.
├── angelQ_website2
│ ├── asgi.py
│ ├── settings.py
│ ├── urls.py
│ ├── views.py
│ ├── wsgi.py
│ └── init.py
├── db.sqlite3
├── manage.py
├── static
│ └── assets
│ ├── css
│ ├── fonts
│ ├── images
│ └── js
└── templates
└── index.html


- `angelQ_website2`: This directory contains the main Django project settings.
  - `asgi.py`: Entry point for ASGI-compatible web servers.
  - `settings.py`: Contains all the website settings.
  - `urls.py`: Defines the URL routing for the project.
  - `views.py`: Handles the request/response logic.
  - `wsgi.py`: Entry point for WSGI-compatible web servers.
  - `__init__.py`: Instructs Python to treat this directory as a Python package.
- `db.sqlite3`: SQLite database file.
- `manage.py`: Command-line utility for interacting with the Django project.
- `static`: Contains all the static files.
- `templates`: Contains all the HTML templates.
