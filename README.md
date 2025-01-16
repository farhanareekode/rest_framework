# Product Inventory API

A simple API for managing a product inventory built using Django REST Framework.

## Features

- List all products
- Add a new product
- Update a product
- Delete a product
- **Bonus:** Validation to ensure the product price is non-negative

---

## Requirements

- Python 3.9+
- Django 4.x
- Django REST Framework 3.x

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/product-inventory-api.git
   
2. **Create a virtual environment:**
Run the following command to create a virtual environment:
`python3 -m venv env`

   *Activate the virtual environment:*
   On Linux/macOS:
   `source env/bin/activate`
   
   On Windows:
   `.\env\Scripts\activate`

3. **Install project dependencies:**
Run the following command to install all required dependencies:
   `pip install -r requirements.txt`
   
4. **Apply database migrations:**
Run the following command to apply migrations and set up the database:
  - `python manage.py migrate`
  - `python manage.py makemigrations`

5. **Run the development server:**
Start the server using the following command:
   `python manage.py runserver`
