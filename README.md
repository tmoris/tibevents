# Tibevents-Event marketing platform

Welcome to the repository for my event marketing and ticketing system project. This application provides a platform for users to browse, purchase, and manage event tickets. It also includes user authentication, event creation, and testimonial submission features.

## Table of Contents

1. [Technologies Used](#technologies-used)
2. [Project Structure](#project-structure)
3. [Installation and Usage](#installation-and-usage)
4. [Features](#features)
5. [Future Enhancements](#future-enhancements)
6. [Contact](#contact)
7. [Contributing](#contributing)
8. [License](#license)

## Technologies Used

- Python
- Flask
- SQLAlchemy
- HTML
- CSS
- JavaScript
- Bootstrap
- SQLite

## Project Structure

- `app/`: The main application directory containing:

  - `errors/`: error handlering methods
  - `templates/`: HTML templates for rendering web pages.
  - `static/`: Static assets including CSS, JavaScript, and images.
  - `forms/`: Flask-WTF forms for user input validation.
  - `models/`: Database models using SQLAlchemy ORM.
  - `views/`: Flask routes for different application views.
  - `utils/`: Utility functions and helper modules.
  - `__init__.py`: The main application entry point.

- `migrations/`: Database migration scripts generated by Flask-Migrate.

- `tests/`: Unit and integration tests for the application.

## Installation and Usage

1. Clone this repository: `git clone https://github.com/tmoris/tibevents.git`.
2. Navigate to the project directory: `cd tibevents`.
3. Create a virtual environment: `python -m venv venv`.
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
5. Install project dependencies: `pip install -r requirements.txt`.
6. Set up the database: `flask db init`, `flask db migrate`, `flask db upgrade`.
7. Run the application: `flask run`.
8. Open your web browser and visit `http://localhost:5000`.

## Features

- User registration and login with authentication.
- Event creation and management for administrators.
- Event browsing, filtering, and ticket purchase for users.
- Testimonial submission and display.
- User profile management.
- Contact form for user inquiries.

## Future Enhancements

- Implement payment gateway integration for online ticket purchases.
- Enhance user interface for better user experience.
- Add notifications and email alerts.
- Expand admin features for event analytics.
- Implementing a social media login autho, and password recovery

## Contact

Feel free to get in touch with me for any questions or feedback:

- [Email](mailto:tibenkanamoris@gmail.com)
- [GitHub](https://github.com/tmoris)

## Contributing

I welcome contributions to improve the project. Please follow our [contribution guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
