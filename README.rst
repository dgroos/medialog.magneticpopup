.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide.html
   This text does not appear on pypi or github. It is a comment.

==============================================================================
medialog.magneticpopup
==============================================================================
Adds popup to images in #content 


Features
--------
- Images embedded in a page, as well as the image shown on the ...jpg/view page, will popup in a jquery style lightbox. 
- If using a responsive theme, the popup image responds to the display size.
- Upon clicking on embedded image, it pops up to its full size if display size permits, otherwise it scales down to size of display.
- Title is taken from caption that was added to image or if none, from file name.


Examples
--------
This add-on can be seen in action at the following sites:

- classroom Plone site http://sci.mpls.k12.mn.us/ 


Documentation
-------------
Full documentation for end users can be found in the "docs" folder, and is also available online at http://docs.plone.org/foo/bar


Translations
------------
This product has been translated into
- Klingon (thanks, K'Plai)


Installation
------------
1. Install medialog.magneticpopup by adding it to your buildout::

    [buildout]

    ...

    eggs =
        medialog.magneticpopup


2. Next, run: ``bin/buildout``.
3. Finally, go to your site setup/addons and enable this new addon.

Contribute
----------

- Issue Tracker: https://github.com/collective/medialog.magneticpopup/issues
- Source Code: https://github.com/collective/medialog.magneticpopup
 


Support
-------

If you are having issues, please let us know.
 


License
-------

The project is licensed under the GPLv2.
