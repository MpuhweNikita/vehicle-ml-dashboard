# Vehicle ML Dashboard

A Django web dashboard for exploring vehicle data using manufacturer frequency tables.

## Features

- Manufacturer frequency analysis using pandas.
- HTML tables generated from vehicle data.
- Responsive interface styled with Bootstrap 5.
- Django-based web application.

## Technologies

- Python
- Django
- pandas
- Plotly
- Bootstrap 5

## Getting Started

Clone the repository:

```bash
git clone https://github.com/MpuhweNikita/vehicle-ml-dashboard.git
cd vehicle-ml-dashboard
```

Create and activate a virtual environment on Windows:

```cmd
python -m venv venv
venv\Scripts\activate
```

Install dependencies:

```cmd
pip install -r requirements.txt
```

Apply database migrations and start the server:

```cmd
python manage.py migrate
python manage.py runserver
```

Open `http://127.0.0.1:8000/` in your browser.

## Dataset

Place the required vehicle CSV file at `dummy_data/vehicles_data_1000.csv`.

## Learning Objective

Practice building a data dashboard with Django, pandas, HTML tables, and Bootstrap styling.
