# Founders Fall 2020 Backend Takehome

Scrape a local dataset of employee data and return the processed data at an endpoint using Python and Flask.

Feel free to consult as many outside resources as you would like and push your code to a fork of this repository when you are done.

Questions, errors, or needed clarifications? Reach out here: `sirajsc2 [at] illinois [dot] edu`.

## Task

#### ⚠️ You only need to edit `__init__.py` to complete this exercise

1. Fork this repository
2. Write a function to process data from `data.csv` into a JSON structure as follows

```
{
    employees: [
        {
            name: <full name of employee>,
            timezone: <timezone of employee>,
            dept: <department of employee>
        }
        ...
    ]
}
```

3. Return your processed data at a new endpoint located at `/api/fetch`
4. Don't forget to commit and push your solution

## Setup

1. Clone your fork of this repository
2. Ensure you have a Python 3 environment to run this Flask server
3. Install required packages by executing `pip3 install requirements.txt` OR `pip install requirements.txt` depending on your system installation of Python
4. Save the following environment variable via `export FLASK_RUN=__init__.py` (for macOS/Linux, environment variables are under Control Panel/System on Windows w/o WSL)
5. Execute `flask run` in the repository to run a development server

## External Help

* [Getting Started with Flask](https://flask.palletsprojects.com/en/1.1.x/tutorial/factory/)
* [Installing Python 3](https://www.codecademy.com/articles/install-python3)
