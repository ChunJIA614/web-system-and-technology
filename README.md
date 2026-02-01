# Web System and Technology Project

## Overview
This repository contains the source code and assets for a web-based system designed for managing events and user interactions. The project is divided into two main sections:

1. **Admin Panel**: Tools for administrators to manage events, users, and other system configurations.
2. **User Interface**: A user-friendly interface for participants to interact with the system, including event registration, profile management, and more.

---

## Project Structure

### Root Directory
- `chinesesociety.sql`: SQL file for initializing the database.
- `readme.txt`: Additional project notes.

### Admin Panel (`Admin/`)
Contains the backend logic and interface for administrators.

- **Key Files**:
  - `add-events.php`: Add new events.
  - `admin-login.php`: Admin authentication.
  - `event-list.php`: View and manage events.
  - `staff-list.php`: Manage staff details.
- **Includes**:
  - `config.php`: Database configuration.
  - `header.php`, `footer.php`, `navbar.php`, `sidebar.php`: Layout components.
  - `css/`: Stylesheets for the admin panel.
  - `js/`: JavaScript files for interactivity.

### User Interface (`User/`)
Contains the frontend and backend logic for user interactions.

- **Key Files**:
  - `home.php`: Homepage for users.
  - `event.php`: Event details and registration.
  - `profile.php`: User profile management.
  - `signup.php`, `login.php`: User authentication.
- **Includes**:
  - `assets/`: Additional assets like images, styles, and scripts.
  - `css/`: Stylesheets for the user interface.
  - `js/`: JavaScript files for interactivity.
  - `scss/`: SCSS files for advanced styling.

---

## Technologies Used

- **Frontend**:
  - HTML, CSS, JavaScript
  - Bootstrap for responsive design
- **Backend**:
  - PHP
  - MySQL for database management
- **Libraries and Plugins**:
  - jQuery
  - ApexCharts, Chart.js for data visualization
  - Lightbox, OwlCarousel for UI enhancements

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Import the database:
   - Use the `chinesesociety.sql` file to set up the database.
3. Configure the database connection:
   - Update the `config.php` files in both `Admin/includes/` and `User/` directories with your database credentials.
4. Start a local server:
   - Use tools like XAMPP or WAMP to host the project locally.
5. Access the system:
   - Admin Panel: `http://localhost/Admin`
   - User Interface: `http://localhost/User`

---

## Features

### Admin Panel
- Event management (add, edit, delete events).
- User and staff management.
- View participant lists.

### User Interface
- Event browsing and registration.
- Profile management.
- Booking history.

---

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments
- Bootstrap for responsive design.
- Open-source libraries and plugins used in the project.

---

## Contact
For any inquiries, please contact the project maintainer at `your-email@example.com`. Replace with your actual email address.

## Additional Information

### Login Pages
- **User Login Page**: 
  - `localhost/G4%20ChineseSociety/Project/User/login.php`
  - `localhost/Project/User/login.php`
  - *Note*: If the project is directly in `htdocs`, use the second URL.
- **Admin Login Page**: 
  - `localhost/G4%20ChineseSociety/Project/Admin/admin-login.php`
  - `localhost/Project/Admin/admin-login.php`

### Home Pages
- **User Home Page**: 
  - `localhost/G4%ChineseSociety/Project/User/home.php`
  - `localhost/Project/User/home.php`
- **Admin Home Page**: 
  - `localhost/G4%ChineseSociety/Project/Admin/index.php`
  - `localhost/Project/Admin/index.php`

### Test Credentials

#### User Accounts
- **Email**: chunjia@gmail.com | **Password**: abc123
- **Email**: chunwen@gmail.com | **Password**: abc123
- **Email**: zhiying@gmail.com | **Password**: abc123

#### Admin Accounts
- **Email**: chunwen@gmail.com | **Password**: chunwen
- **Email**: chunjia@gmail.com | **Password**: abc123
- **Email**: junkang@gmail.com | **Password**: jk123