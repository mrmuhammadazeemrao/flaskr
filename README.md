
# Blog Application

Creating a basic blog application called Flaskr. Users will be able to register, log in, create posts, and edit or delete their own posts. You will be able to package and install the application on other computers.


Install
-------

**Be sure to use the same version of the code as the version of the docs
you're reading.** You probably want the latest tagged version, but the
default Git version is the main branch. ::

    # clone the repository
    $ git clone https://www.github.com/mrmuhammadazeemrao/flaskr
    $ cd flask
    # checkout the correct version
    $ git tag  # shows the tagged versions
    $ git checkout latest-tag-found-above
    $ cd examples/tutorial

Create a virtualenv and activate it::

    $ python3 -m venv venv
    $ . venv/bin/activate

Or on Windows cmd::

    $ py -3 -m venv venv
    $ venv\Scripts\activate.bat

Install Flaskr::

    $ pip install -e .

Or if you are using the main branch, install Flask from source before
installing Flaskr::

    $ pip install -e ../..
    $ pip install -e .


Run
---

.. code-block:: text

    $ flask --app flaskr init-db
    $ flask --app flaskr --debug run

Open http://127.0.0.1:5000 in a browser.


Test
----

::

    $ pip install '.[test]'
    $ pytest

Run with coverage report::

    $ coverage run -m pytest
    $ coverage report
    $ coverage html  # open htmlcov/index.html in a browser

## Commands(Take aways)

Command to run a single app in development
```bash
  flask --app flaskr --debug run
```


## Authors

- [@mrmuhammadazeemrao](https://www.github.com/mrmuhammadazeemrao)


## Acknowledgements

 - [Flask Documentation](https://flask.palletsprojects.com/en/2.2.x/tutorial/)


## Tech Stack

**Client:** HTML, CSS, Jinja

**Server:** Python, Flask

<!-- Need to continue from below link -->
<!-- https://flask.palletsprojects.com/en/2.2.x/tutorial/views/ -->
