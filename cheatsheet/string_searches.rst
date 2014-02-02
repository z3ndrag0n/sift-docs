String Searches
---------------
ASCII string search and list the byte offset

``srch_strings -t d imagefile.dd > imagefile.ascii.str``

uNICODE string search and list byte offset

``srch_strings -e l –t d imagefile.dd > imagefile.uni.str``

Search for a specific string using grep

GREP useful Options

======  ===========
Option  Description
======  ===========
-i      ignore case
-f      dirty word list filename
======  ===========

.. code-block:: html

    grep -i password –f dirty_words.txt imagefile.ascii.str