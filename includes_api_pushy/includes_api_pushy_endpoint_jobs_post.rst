.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

The ``POST`` method is used to start a job.

This method has no parameters.

**Request**

.. code-block:: xml

   POST /organizations/ORG_NAME/pushy/jobs

with a request body that looks something like:

.. code-block:: javascript

   {
     "command": "chef-client", 
     "run_timeout": 300, 
     "nodes": ["NODE1", "NODE2", "NODE3", "NODE4", "NODE5", "NODE6"]
   }

**Response**

The response will return something similar to:

.. code-block:: ruby

   {
     "id": "aaaaaaaaaaaa25fd67fa8715fd547d3d"
   }

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Response Code
     - Description
   * - ``201``
     - |response code 201 created|
   * - ``400``
     - |response code 400 bad request|
   * - ``401``
     - |response code 401 unauthorized|
   * - ``403``
     - |response code 403 forbidden|
   * - ``404``
     - |response code 404 not found|