# Height Collector Web App

## Overview

This Flask web application allows users to submit their height and email address, stores the data in a PostgreSQL database, and sends an email response with the average height of users who submitted data. It's a simple yet powerful tool for collecting and sharing data with users.

## Features

- **Data Collection**: Users can submit their email address and height via a web form.

- **Data Storage**: User data (email and height) is stored in a PostgreSQL database.

- **Email Notification**: After submitting their data, users receive an email with the average height of all users who have submitted data.

## How It Works

1. Run the Flask web app using the command `python app.py`.

2. Access the web app by visiting the URL (usually http://localhost:5000) in your web browser.

3. On the web app's homepage, users can submit their email address and height.

4. The submitted data is stored in the PostgreSQL database.

5. After submission, users receive an email with the average height of all users who have submitted data.

## Prerequisites

Before using this web app, make sure you have the following Python libraries and a PostgreSQL database set up:

- [Flask](https://flask.palletsprojects.com/): For creating web applications.
- [Flask-SQLAlchemy](https://pypi.org/project/Flask-SQLAlchemy/): To work with the database.
- [PostgreSQL](https://www.postgresql.org/): As the database management system.
- An SMTP server for sending email notifications.

## Libraries Used

- **Flask**: Used to create and manage the web application.
- **Flask-SQLAlchemy**: Integrated with PostgreSQL for database management.
- **email.mime.text**: Part of the standard library for email content.
- **smtplib**: Part of the standard library for sending emails.

## Configuration

1. Set up a PostgreSQL database and configure its connection settings in the `app.py` file. Make sure to replace `"PASSWORD"` with your actual database password.

2. Customize the appearance and layout of the web app as needed.

3. Configure an SMTP server for sending email notifications in the `send_email.py` file.

4. Modify the email content and format according to your preferences.

## Notes

- Ensure that you run the web app using the command specified in the "How It Works" section.

- The app stores user data in a PostgreSQL database, and it calculates the average height dynamically.

- For email functionality, make sure to provide valid SMTP server settings.

- This web app can be expanded with additional features, such as user authentication, improved data visualization, or data export functionality.

That's it! Enjoy using the Height Collector Web App to collect and share data with users in a convenient and user-friendly way.

### License
This project is licensed under the MIT License. You are free to use and modify the code for your own purposes.

