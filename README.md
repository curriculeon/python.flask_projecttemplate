
### Prerequisite Software
* Install Python
* Install PiP via Python
    * `python -m ensurepip`

* Install `Flask`
    * `python -m pip install Flask`



### How to run this
* There are two simple ways to run this in development
    1. Execute the following command from the root directory of this project.

    `python web.py`

    2. A better way, that provides more control over how to run this is to use:
    
    `FLASK_APP=web FLASK_DEBUG=1 flask run --port 3000 --host 127.0.0.1`

* _This application was built using [code-maven](https://code-maven.com/flask-serve-static-files) as a reference._