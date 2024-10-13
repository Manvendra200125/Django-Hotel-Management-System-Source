# Room Booking System

This is a Django-based room booking system that allows users to manage room bookings, customer details, room availability, and more.

## Features

- User login and authentication.
- Manage room bookings and customer details.
- Manage room availability and room slots.
- Static and media file handling.
- API integration for data handling.

 ## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/room-booking-system.git
   cd room-booking-system

   python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
python manage.py createsuperuser
