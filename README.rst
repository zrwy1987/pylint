
README for Pylint - http://pylint.pycqa.org/
============================================

.. image:: https://travis-ci.org/PyCQA/pylint.svg?branch=master
    :target: https://travis-ci.org/PyCQA/pylint

.. image:: https://ci.appveyor.com/api/projects/status/rbvwhakyj1y09atb/branch/master?svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/PCManticore/pylint

.. image:: https://coveralls.io/repos/github/PyCQA/pylint/badge.svg?branch=master
    :target: https://coveralls.io/github/PyCQA/pylint?branch=master


.. image:: https://img.shields.io/pypi/v/pylint.svg
    :alt: Pypi Package version
    :target: https://pypi.python.org/pypi/pylint

.. image:: https://readthedocs.org/projects/pylint/badge/?version=latest
    :target: http://pylint.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/ambv/black

.. |tideliftlogo| image:: doc/media/Tidelift_Logos_RGB_Tidelift_Shorthand_On-White_small.png
   :width: 75
   :height: 60
   :alt: Tidelift

.. list-table::
   :widths: 10 100

   * - |tideliftlogo|
     - Professional support for pylint is available as part of the `Tidelift
       Subscription`_.  Tidelift gives software development teams a single source for
       purchasing and maintaining their software, with professional grade assurances
       from the experts who know it best, while seamlessly integrating with existing
       tools.

.. _Tidelift Subscription: https://tidelift.com/subscription/pkg/pypi-pylint?utm_source=pypi-pylint&utm_medium=referral&utm_campaign=readme


======
Pylint
======

**It's not just a linter that annoys you!**

Pylint is a Python static code analysis tool which looks for programming errors,
helps enforcing a coding standard, sniffs for code smells and offers simple refactoring
suggestions.

It's highly configurable, having special pragmas to control its errors and warnings
from within your code, as well as from an extensive configuration file.
It is also possible to write your own plugins for adding your own checks or for
extending pylint in one way or another.

It's a free software distributed under the GNU General Public Licence unless
otherwise specified.

Development is hosted on GitHub: https://github.com/PyCQA/pylint/

You can use the code-quality@python.org mailing list to discuss about
Pylint. Subscribe at https://mail.python.org/mailman/listinfo/code-quality/
or read the archives at https://mail.python.org/pipermail/code-quality/

Pull requests are amazing and most welcome.

Install
-------

Pylint can be simply installed by running::

    pip install pylint

If you are using Python 3.6+, upgrade to get full support for your version::

    pip install pylint --upgrade

If you want to install from a source distribution, extract the tarball and run
the following command ::

    python setup.py install


Do make sure to do the same for astroid, which is used internally by pylint.

For debian and rpm packages, use your usual tools according to your Linux distribution.

More information about installation and available distribution format
can be found here_.

Documentation
-------------

The documentation lives at http://pylint.pycqa.org/.

Pylint is shipped with following additional commands:

* pyreverse: an UML diagram generator
* symilar: an independent similarities checker
* epylint: Emacs and Flymake compatible Pylint


Testing
-------

We use tox_ for running the test suite. You should be able to install it with::

    pip install tox pytest


To run the test suite for a particular Python version, you can do::

    tox -e py37


For more detailed information, check the documentation.

.. _here: http://pylint.pycqa.org/en/latest/user_guide/installation.html
.. _tox: https://tox.readthedocs.io/en/latest/

License
-------

pylint is, with a few exceptions listed below, `GPLv2 <COPYING>`_.

The icon files are licensed under the `CC BY-SA 4.0 <https://creativecommons.org/licenses/by-sa/4.0/>`_ license:

- `doc/logo.png <doc/logo.png>`_
- `doc/logo.svg <doc/logo.svg>`_


<a href="https://scan.coverity.com/projects/zrwy1987_pylint">
  <img alt="Coverity Scan Build Status"
       src="https://scan.coverity.com/projects/18896/badge.svg"/>
</a>
