.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

The GET method is used to return a node.

This method has no parameters.

**Request**

.. code-block:: xml

   GET /environments/NAME/nodes

where the first instance of ``NAME`` is the name of the environment, and the second instance is the name of the node.

**Response**

The response will return something like the following:

.. code-block:: javascript

   xxxxx

**Response Codes**

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Response Code
     - Description
   * - ``200``
     - |response code 200 ok|
   * - ``401``
     - |response code 401 unauthorized|
   * - ``403``
     - |response code 403 forbidden|
   * - ``404``
     - |response code 404 not found|