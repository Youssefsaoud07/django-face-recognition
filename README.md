# Django Facial Recognition Project

Welcome to the Django Facial Recognition project! This project utilizes Django for building a facial recognition application.

## Setup Instructions

Follow these steps to set up and run the project locally:

1. **Clone Repository**: Clone the repository to your local machine.

    ```bash
    git clone <repository_url>
    ```

2. **Create Virtual Environment**: Create a virtual environment using Python's `venv` module.

    ```bash
    python -m venv ./venv
    ```

3. **Activate Virtual Environment**: Activate the virtual environment.

    - On Windows:

    ```bash
    venv\Scripts\activate
    ```

    - On macOS/Linux:

    ```bash
    source venv/bin/activate
    ```

4. **Install Dependencies**: Install the required dependencies for your project.

    ```bash
    pip install -r requirements.txt
    ```

5. **Check Python Version**: Ensure that you have the correct Python version installed, especially if your project depends on a specific version of `dlib`.

6. **Create Superuser**: Create a superuser account for accessing the Django admin interface.

    ```bash
    python manage.py createsuperuser
    ```

    Follow the prompts to set up the superuser account.

7. **Run Migrations**: Apply database migrations to create necessary database tables.

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

8. **Run Development Server**: Start the Django development server.

    ```bash
    python manage.py runserver
    ```

9. **Access the Application**: Open a web browser and navigate to `http://localhost:8000` to access your Django application.

10. **Have Fun!**: You're all set! Explore your Django facial recognition project and have fun experimenting with it.