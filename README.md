# Josh-Talks-Tasks
It is a repository including the task for the Backend internship of JoshTalks.
Youtube Fetch API - Back-End Task (Josh Talks) :
An API to fetch latest videos from youtube sorted in reverse chronological order of their publishing date-time from YouTube for a given tag/search query in a paginated response. The server fetches the latest videos async after every 10 minutes and saves it to the database.
This project is completely based on Django.


Setup Guide :
Open the project.
As this project is based on Django, your system needs to have proper python setup, refer this.
Also install the isodate, by using pip install isodate, in the terminal.
Inside the setting.py file, fill the variable YOUTUBE_DATA_API_KEY with all the API Keys available. For getting an API key follow this.
Run the server using python manage.py runserver.

