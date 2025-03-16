
# Hospital Management System


Hospital Management System is a web application for managing diagnostic center, faciliting interactions between agents and customers and providing a platform for patients appointment.



## Features

- Frontend Features::
    
- Appointment: Allows patients to book medical appointments online with available doctors.
- Contact: Provides hospital contact details and a contact form for inquiries.
- Services: Lists the medical services offered, including specialties and treatments.
- Doctors: Displays profiles of doctors, their expertise, and availability.
- About: Shares hospital information, mission, vision, and history.
- Subscription: Enables users to subscribe for health updates, newsletters, or special offers.


- Admin Features 
  - Operation Report: Manages surgical records, including patient details, surgery type, and date.
  - Birth Report: Maintains birth records, including newborn details and parental information.
  - Patient: Stores patient details, medical history, and treatment records.
  - Employee: Manages hospital staff details, roles, and schedules.
  - Room: Tracks hospital room availability, assignments, and occupancy.
  - Bed: Manages hospital bed allocation and availability.
  - Bill: Handles patient billing, payments, and invoices.
  - Medicine Store: Keeps inventory of medicines, stock levels, and suppliers.
  - Block: Categorizes different hospital sections (e.g., ICU, general ward).
  - Appointment: Oversees patient appointment scheduling and doctor availability.
  - Subscriber: Manages newsletter or health update subscriptions.
  - Message: Stores and organizes patient or visitor inquiries.
  - Setting: Controls system configurations, user roles, and hospital preferences.


## Technologies Used

- Frontend: HTML, CSS, Tailwind CSS
- Backend: Laravel Livewire
- Database: MySQL

## Installation Guide

Follow these steps to set up the project on your local machine:

### Prerequisites

- PHP (>= 8.0)
- Composer
- MySQL
- Git




## Setup Instructions

 1. Clone the repository:

```bash
    git clone https://github.com/smmehedi4u/hospital-management-system.git
```
2. Moved new Folder
```bash
    cd hospital-management-system
```

3. Install dependencies:

```bash
    composer install
```

4. Setup Environment: 

```bash
    cp .env.example .env
```

5. Open .env and configure the following:

```bash
    DB_DATABASE=your_database_name
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
```

6. Generate application key:

```bash
    php artisan key:generate
```

7. Run migrations and seed the database:

This command will create the database tables and populate initial data using seeders.

```bash
    php artisan migrate --seed
```

8. Serve the application:

Start the Laravel development server.

```bash
    php artisan serve
```

9.Access the application:

Open your browser and visit http://localhost:8000.

## Seeded Data for Testing

The project includes seeders to populate test data for each user role (Admin, Teacher, and Student).

- Admin Login:
    - Email: hasan@mail.com
    - Password: password





