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
    cd my-django-app
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
    pip install -r requirements.txt
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

## Features

- User authentication
- CRUD operations on sample models
- RESTful API
- More to come!

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
