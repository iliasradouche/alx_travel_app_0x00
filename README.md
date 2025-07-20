# alx_travel_app_0x00

A Django-based travel application for managing Listings, Bookings, and Reviews.

## Features

- Create and manage travel listings
- Book listings for specific dates
- Leave reviews and ratings on listings
- REST API-ready using Django REST Framework

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/alx_travel_app_0x00.git
   cd alx_travel_app_0x00/alx_travel_app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Apply migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. Create a superuser (optional, for admin access):
   ```bash
   python manage.py createsuperuser
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Database Seeding

Populate the database with sample data using the seed command:

```bash
python manage.py seed
```

## Project Structure

- `listings/models.py` – Django models for Listing, Booking, Review
- `listings/serializers.py` – Serializers for REST API
- `listings/management/commands/seed.py` – Management command to seed the database

## Requirements

- Python 3.x
- Django 3.x/4.x
- Django REST Framework

## License

This project is for educational purposes as part of the ALX Software Engineering Program.