.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

This resource has the following attributes:

.. list-table::
   :widths: 150 450
   :header-rows: 1

   * - Attribute
     - Description
   * - ``group``
     - |windows group_identifier|
   * - ``inherits``
     - |windows| only. |inherits windows security| Default value: ``true``.
   * - ``mode``
     - |mode resource_directory|
       
       The behavior is different depending on the platform.
       
       |unix|- and |linux|-based systems: |mode *nix|
       
       |windows|: |mode windows security|
   * - ``owner``
     - |owner windows security|
   * - ``path``
     - |path directory| Default value: the ``name`` of the resource block (see Syntax section above).
   * - ``provider``
     - Optional. |provider resource_parameter|
   * - ``recursive``
     - |recursive directory| Default value: ``false``.
   * - ``rights``
     - |windows| only. |rights windows security|
