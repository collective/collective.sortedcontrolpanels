.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide.html
   This text does not appear on pypi or github. It is a comment.

==============================
collective.sortedcontrolpanels
==============================

This sorts control panels alphabetically by title.

Plone used to do that, but in 2015 a change was quietly made that sorted instead by control panel IDs which are hidden, obscure, and arbitrarily-given.

On May 6, 2020, this pull request `PR 3093 <https://github.com/plone/Products.CMFPlone/pull/3093>`_ reverts Plone back to sorting control panels by title.

Until a new Plone release (> 5.2.1) includes that merged PR, use this add-on to accomplish the same.


Features
--------

- sorts control panels sensibly in alphabetical order, by title


Installation
------------

Install collective.sortedcontrolpanels by adding it to your buildout::

    [buildout]

    ...

    eggs =
        collective.sortedcontrolpanels


and then running ``bin/buildout``


Contribute
----------

- Issue Tracker: https://github.com/collective/collective.sortedcontrolpanels/issues
- Source Code: https://github.com/collective/collective.sortedcontrolpanels


License
-------

The project is licensed under the GPLv2.
