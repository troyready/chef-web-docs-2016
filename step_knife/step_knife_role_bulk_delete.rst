.. The contents of this file may be included in multiple topics (using the includes directive).
.. The contents of this file should be modified in a way that preserves its ability to appear in multiple topics.


Use a regular expression to define the pattern used to bulk delete roles:

.. code-block:: bash

   $ knife role bulk delete "^[0-9]{3}$"