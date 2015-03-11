========================
 cookiecutter-pypackage
========================

Cookiecutter_ template for a Python package. Forked from
`audreyr/cookiecutter-pypackage`_.

Unfamiliar with Cookiecutter? It's a simple tool which allows you to create new
projects from a starting template (like this one). The last thing you want to
do when you have an idea is waste time setting up your code layout while
remembering how to get started from scratch.

This template is an excellent jump-off point for any Python project. It has
strong, but justified opinions about how Python packages should look and be
written. It includes:

* Vanilla testing setup with `unittest` and `python setup.py test`
* Travis-CI_: Ready for Travis Continuous Integration testing
* Tox_ testing: Setup to easily test for Python 2.6, 2.7, 3.3, 3.4
* Sphinx_ docs: Documentation ready for generation with, for example,
  ReadTheDocs_

Usage
-----

Ensure that Cookiecutter is `installed
<http://cookiecutter.readthedocs.org/en/latest/installation.html>`_.

Make a directory for your new project and enter it. In this example we're
calling it "fancypants".

.. code-block:: bash

    $ mkdir fancypants
    $ cd fancypants

Generate your initial code by using Cookiecutter with this template:

.. code-block:: bash

    $ cookiecutter gh:Pewpewarrows/cookiecutter-pypackage

Begin tracking the project in version control:

.. code-block:: bash

    $ git init
    $ git add *
    $ git commit -m "Initial commit"

Then:

* Add the repo to your Travis CI account.
* Add the repo to your ReadTheDocs account + turn on the ReadTheDocs service
  hook.
* Release your package the standard Python way. Having a `release checklist`_
  always helps!

Not Exactly What You Want?
--------------------------

Don't worry, you have options:

Similar Cookiecutter Templates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

See the `network`_ and `family tree`_ for `audreyr`_'s original repo. (If you
find anything that should be listed here, please add it and send a pull
request!)

Fork This / Create Your Own
~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Or create your own; it doesn't strictly have to
be a fork.

* Once you have your own version working, add it to the Similar Cookiecutter
  Templates list above with a brief description.

* It's up to you whether or not to rename your fork/own version. Do whatever
  you think sounds good.

Or Submit a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~

I also accept pull requests on this, if they're small, atomic, and if they
make my own packaging experience better.


.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
.. _Travis-CI: http://travis-ci.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.org/
.. _`release checklist`: https://gist.github.com/audreyr/5990987
.. _`network`: https://github.com/audreyr/cookiecutter-pypackage/network
.. _`family tree`: https://github.com/audreyr/cookiecutter-pypackage/network/members
.. _`audreyr`: https://github.com/audreyr
