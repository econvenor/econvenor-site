eConvenor site
==============

eConvenor is the `Django-based <https://djangoproject.com>`_ web app which
powers the `eConvenor <https://econvenor.org>`_ web service.

eConvenor helps progressive campaigns and organisations be more effective.

This repo is for the website which sits in front of the eConvenor app.

Building the site
-----------------

Step 1 - Install build tools
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Install Node.js version 6 using `nvm <https://github.com/creationix/nvm>`_.

Then install Node packages we will need globally::

    $ npm install -g gulp-cli bower less

Step 2 - Get local Node packages and Bower frameworks
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

::

    $ cd /path/to/econvenor-site
    $ npm install
    $ bower install

Step 3 - Serve the site with Gulp
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

::

    $ gulp serve

This will serve the site at `localhost:9000 <http://localhost:9000>`_.

Each time you save a ``.pug`` or ``.less`` file, the site should update
automatically.
