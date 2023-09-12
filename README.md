# angelQ_website

 
## Installation

### Prerequisites

- Python 3.x
- pip
- conda (optional)

### Steps

1. **Clone the repository**
    ```bash
    git clone https://github.com/leonidas1312/angelQ_website/tree/main
    ```

2. **Navigate to the project directory**
    ```bash
    cd angelQ_website2
    ```

3. **Create a new Conda environment**
    ```bash
    conda create --name myenv python=3.x
    ```

4. **Activate the Conda environment**
    ```bash
    conda activate myenv
    ```

5. **Install Django within the Conda environment**
    ```bash
    conda install django
    ```

    Or you can use pip within the Conda environment if you prefer:
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

To deactivate the Conda environment when you're done, you can use:
```bash
conda deactivate
```

## Usage

1. Open your web browser and go to `http://127.0.0.1:8000/`

## Project Structure
```
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
```

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
