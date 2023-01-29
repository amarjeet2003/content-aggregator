# Content-Aggregator app 

This project is built using Python & Django with background asynchronous process scheduled with django-apscheduler and frontend built using Bootstrap.

This project loads the latest podcasts from The Real Python Podcast feed. It uses a custom management console to automate personalized schedule. It also have some basic unit tests to check all database transactions along with HTTP Response check.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.txt.

```bash
pip install -r requirements.txt
```

## Usage


```python
# run local server
python manage.py runserver
```

```python
# run custom commands in another terminal
python manage.py startjobs
```