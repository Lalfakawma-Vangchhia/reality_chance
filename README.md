# Reality Chance

A Django web application.

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/reality_chance.git
cd reality_chance
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
.\venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the project root and add your secret key:
```
SECRET_KEY=your-secret-key-here
```

5. Run migrations:
```bash
python manage.py migrate
```

6. Create a superuser (optional):
```bash
python manage.py createsuperuser
```

7. Run the development server:
```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000/ to see the application.

## Features

- Bootstrap 5 integration
- Responsive design
- Custom styling
- Django crispy forms with Bootstrap 5

## Development

- The main application is in the `main` app
- Static files are in the `static` directory
- Templates are in the `templates` directory

## License

This project is licensed under the MIT License.
