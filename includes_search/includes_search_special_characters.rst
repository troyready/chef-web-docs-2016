.. The contents of this file may be included in multiple topics (using the includes directive).
.. The contents of this file should be modified in a way that preserves its ability to appear in multiple topics.


|search special character| The following characters can be included within the search query syntax, but each occurrence of a special character must be escaped with a backslash (``\``):

.. code-block:: ruby

   +  -  &&  | |  !  ( )  { }  [ ]  ^  "  ~  *  ?  :  \

For example:

.. code-block:: ruby

   \(1\+1\)\:2
