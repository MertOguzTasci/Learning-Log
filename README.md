# Learning Log

Learning Log is a web application that allows users to
log the topics they’re interested in and make journal entries as
they learn about each topic. The Learning Log home page will
describe the site and invite users to either register or log in. Once
logged in, a user can create new topics, add new entries, and read
and edit existing entries.

# Features

User Authentication: Users can create accounts and log in to access their learning logs.
Topic Tracking: Users can create new topics they're learning about and add entries to each topic.
Timestamps: Entries are automatically timestamped to keep track of when they were added.
Data Visualization: Users can view their learning progress through simple data visualization charts.
Responsive Design: The application is designed to be responsive and accessible across different devices and screen sizes.

# Installation
To run Learning Log locally, follow these steps:

Clone this repository: git clone https://github.com/MertOguzTasci/Learning-Log.git
Navigate to the project directory: cd learning-log
Install the required dependencies: pip install -r requirements.txt
Set up the database: python manage.py migrate
Start the development server: python manage.py runserver
Open your web browser and go to http://localhost:8080 to access Learning Log.

# Usage

Sign up for a new account or log in if you already have one.
Add topics you're currently learning about.
Add entries to each topic to keep track of your progress.
Visualize your learning journey through the provided charts.
Log out when you're done.

# Contributing

Contributions are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue or submit a pull request.

# Acknowledgements

Special thanks to Eric Matthes for the inspiration and guidance provided in Python Crash Course.
Built with Django and Bootstrap.