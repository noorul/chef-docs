.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

This resource has the following attributes:

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Attribute
     - Description
   * - ``pattern``
     - |pattern process_table| Default value: ``service_name``.
   * - ``provider``
     - Optional. |provider resource_attribute|
   * - ``reload_command``
     - |command service_reload| Default value: ``nil``.
   * - ``restart_command``
     - |command service_restart|
   * - ``service_name``
     - |name service| Default value: the ``name`` of the resource block (see Syntax section above).
   * - ``start_command``
     - |command service_start| Default value: ``nil``.
   * - ``status_command``
     - |command service_status| Default value: ``nil``.
   * - ``stop_command``
     - |command service_stop| Default value: ``nil``.
   * - ``supports``
     - |supports resource service|
