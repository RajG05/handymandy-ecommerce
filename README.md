# HandyMandy — E-commerce Web Application

HandyMandy is a Django-based e-commerce web application built with Python, Django, SQLite, HTML, CSS, and JavaScript. It includes product browsing, user accounts, order management, and Razorpay payment integration.

## Requirements

- Python (compatible with your Django version)
- Django
- SQLite
- A web browser

## Steps to Run the Code

1. Clone the repository:

   ```bash
   git clone https://github.com/RajG05/handymandy-ecommerce.git
   cd handymandy-ecommerce
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

3. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure the required environment variables in a local `.env` file.

5. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

6. Start the development server:

   ```bash
   python manage.py runserver
   ```

7. Open the application in your browser:

   http://127.0.0.1:8000/

## Security

- Keep secret keys and payment credentials out of version control.
- Use Django's secure password hashing and authentication system.
- Configure production settings before deployment.
