.. _install:


Install
=======

Dependencies
------------

secedgar relies on:

-  `beautifulsoup4 <https://www.crummy.com/software/BeautifulSoup/bs4/doc/>`__
-  `requests <http://docs.python-requests.org>`__

Installation
------------

Latest stable release via pip (recommended):

.. code:: bash

    $ pip install secedgar

Latest development version:

.. code:: bash

    $ pip install git+https://github.com/coyo8/sec-edgar.git

or

.. code:: bash

     $ git clone https://github.com/coyo8/sec-edgar.git
     $ cd sec-edgar
     $ pip install .

**Note:**

The use of
`virtualenv <http://docs.python-guide.org/en/latest/dev/virtualenvs/>`__
is recommended as below:

.. code:: bash

    $ pip install virtualenv
    $ virtualenv env
    $ source env/bin/activate