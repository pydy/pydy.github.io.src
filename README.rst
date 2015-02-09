This repository contains the source files for the website hosted through Github
Pages at http://github.com/pydy/pydy.github.io.

How make a blog post
====================

Create a new rst file in `source/blog/<year>` and make sure to include a rst
directive with the date of the post, e.g.::

   .. post:: 22 Jan, 2014

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
