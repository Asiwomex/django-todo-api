
# This is a simple Django todo app

This README provides instructions on setting up and running your Django Todo app locally.

**Prerequisites:**

* Python 3 (Download from [https://www.python.org/downloads/](https://www.python.org/downloads/))
* pip (Installed with Python 3)

**Installation:**

1. **Clone the repository:**

   ```bash
   git clone https://<your_github_repo_url>.git
   ```

2. **Create a virtual environment (recommended):**

   ```bash
   python -m venv venv  # or virtualenv venv
   source venv/bin/activate  # or . venv/bin/activate (Windows)
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## **Running the App:**
1. **Run migrations (Optional):**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

2. **Start the development server:**

   ```bash
   python manage.py runserver
   ```

   This will typically launch the server on `http://localhost:8000`.

3. **Access the application:**

   Open your web browser and navigate to `http://localhost:8000` to see your Django Todo app running.


