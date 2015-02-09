This repository contains the source files for the website hosted through Github
Pages at http://github.com/pydy/pydy.github.io.

Dependencies
============

- Sphinx http://sphinx-doc.org/
- Sphinx Bootstrap Theme https://github.com/ryan-roemer/sphinx-bootstrap-theme
- werkzeug http://werkzeug.pocoo.org/
- ablog http://ablog.readthedocs.org

Build Process
=============

Build the website with the included ``Makefile``::

   make html

Serve the website locally with, e.g.::

   firefox _build/html/index.html

Once the website is to your liking, copy the files from ``_build/html`` to the
root directory of your clone of the https://github.com/pydy/pydy.github.io
repository and submit a pull request with the updates. Make sure you do not
delete the `.nojekyll` file in that repository.
