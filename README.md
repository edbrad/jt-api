# jt-api
## EMS Job Ticket (Microsoft ACCESS) REST API w/ Basic Web GUI

The purpose of this application is to provide external access the EMS Legacy MS ACCESS 97 database tables and
the serve data to other, more modern, applications via a REST/HTTP API.

The basic Job Search Web GUI is built using **Django**, a *Python-based* Web application framework (https://www.djangoproject.com/).

The REST API is implemented using the Django REST Framework (http://www.django-rest-framework.org/).

This project currently utilizes the **pyodbc** Python library (https://mkleehammer.github.io/pyodbc/) to connect and read from the MS Access Database (.mdb) via ODBC.
