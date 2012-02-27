Coding Style and Standards
==========================

Projects under the SciELO Project scope have rigorous standards for
both coding style, testing, and documentation.

You may notice there are lots of legacy projects that don`t follow
the presented standards. Yes, it is a tragedy but we are fixing them little
by little.


Documentation Styling
---------------------

Every project needs to have documentation built with `sphinx <http://sphinx.pocoo.org/>`_.
This will allow us to easily integrate it with all the other docs.

For more information, see:

* `reST Specification <http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html>`_
* `sphinx <http://sphinx.pocoo.org/>`_
* `Read the Docs <http://docs.readthedocs.org>`_


Documentation Coverage
----------------------

If you fix a bug, and the bug requires an API or behavior modification, all documentation
in the package which references that API or behavior must change to reflect the bug fix,
ideally in the same commit that fixes the bug or adds the feature.


Change Log
----------

Feature additions and bugfixes must be added to the CHANGES.txt file in the prevailing style.
Changelog entries should be long and descriptive, not cryptic. Other developers should be able
to know what your changelog entry means.


Coding Style
------------

Currently we only support codes written in PHP5.2, or latest, and Python 2.6 or latest.

* `Python: Google Styleguide <http://google-styleguide.googlecode.com/svn/trunk/pyguide.html>`_
* `PHP: Zend Coding Style <http://framework.zend.com/manual/en/coding-standard.coding-style.html>`_