# Airbnb Clone - Web Dynamic Features

## Description

This repository builds upon a static Airbnb clone to create a dynamic web application using JavaScript and jQuery. It focuses on fetching data from an API, user interactions, and dynamically updating content.

## Key Features:

Dynamic Amenity Filters: Users can select amenities to filter displayed listings.
API Status Indicator: Displays the API's availability for data retrieval.
Fetching Places: Retrieves place data via API calls and renders it dynamically.
Additional Filters: Filters listings based on city and state selections.
Reviews Toggle: Shows or hides reviews based on user interaction.
## Prerequisites:

* Node.js and npm (or yarn)
* Python 3
* Required Python libraries (see setup instructions)
## Setup:

Clone this repository: git clone https://github.com/MARWAHAMED629/AirBnB_clone_v4.git
Install dependencies: npm install or yarn install
Create a virtual environment (recommended) and install Python dependencies: pip install -r requirements.txt
Set necessary environment variables (see details below).
Start the Flask web server: python3 -m web_dynamic.0-hbnb
Start the API server (in a separate terminal): python3 -m api.v1.app
## Environment Variables:

* HBNB_MYSQL_USER
* HBNB_MYSQL_PWD
* HBNB_MYSQL_HOST
* HBNB_MYSQL_DB
* HBNB_TYPE_STORAGE
* HBNB_API_PORT (for the API server)
## Usage:

Access the web application in your browser: http://localhost:5000/0-hbnb/
Interact with the filters and features as described in the specific tasks.
## Project Structure:

* api/v1 (API endpoints)
* web_dynamic (web application files)
* templates (HTML templates)
* static (static assets, including JavaScript files)
## Tasks:

The project is divided into several tasks, building upon each other. Refer to the tasks directory for detailed instructions on each task's implementation.

## Additional Notes:

Thoroughly read the task instructions for specific implementation details.
Consider adding screenshots or a demo video to visually showcase the project's features (optional).
If you encounter issues, refer to the troubleshooting tips for common dependencies.
Explore optional advanced tasks for further enhancements.
## Manual QA Review

It's essential to request a review from a peer or staff member before the project deadline.
## Troubleshooting Tips:

Refer to the troubleshooting section for common dependency errors.
If you encounter issues with asset caching, ensure the cache_id query string is correctly added to asset URLs.
## Author(s):
MARWAHAMED629 (github)[https://github.com/MARWAHAMED629]
