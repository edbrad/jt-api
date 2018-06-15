# jt-api
## EMS Job Ticket (Microsoft ACCESS) REST API w/ Basic Web GUI

The purpose of this application is to provide external access the EMS Legacy MS ACCESS 97 database tables and
the serve data to other, more modern, applications via a REST/HTTP API.

The basic Job Search Web GUI is built using **Django**, a *Python-based* Web application framework (https://www.djangoproject.com/).

The REST API is implemented using the Django REST Framework (http://www.django-rest-framework.org/).

This project currently utilizes the **pyodbc** Python library (https://mkleehammer.github.io/pyodbc/) to connect and read from the network-shared MS Access Database (.mdb) file via the Microsoft ODBC driver (Included as part of a typical Windows OS Installation).

This project is deployed to IIS 8, running on Windows Server 2012 R2, and using Microsoft's wfastcgi Python application server.  The blog article by Matt Woodward (http://blog.mattwoodward.com/2016/07/running-django-application-on-windows.html) was used as a guide to aid in the deployment. 
