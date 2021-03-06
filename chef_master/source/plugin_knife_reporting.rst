=====================================================
knife reporting
=====================================================

.. include:: ../../includes_plugin_knife/includes_plugin_knife_reporting.rst

.. note:: Review the list of `common options <http://docs.opscode.com/knife_common_options.html>`_ available to this (and all) |knife| subcommands and plugins.

Install this plugin
=====================================================
.. include:: ../../step_plugin_knife/step_plugin_knife_reporting_install_rubygem.rst


runs list
=====================================================
.. include:: ../../includes_plugin_knife/includes_plugin_knife_reporting_runs_list.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_plugin_knife/includes_plugin_knife_reporting_runs_list_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_plugin_knife/includes_plugin_knife_reporting_runs_list_options.rst

Examples
-----------------------------------------------------
For example:

.. code-block:: bash

   $ knife runs list

will return a list of |chef client| runs by organization, i.e. a list of all |chef client| runs that took place for every single node managed by the |chef server|.

And

.. code-block:: bash

   $ knife runs list foo

will return a list of |chef client| runs that occurred for a node named "foo".

And

.. code-block:: bash

   $ knife runs list foo 30077269-59d0-4283-81f6-8d23cbed3a7a

will return details about that specific |chef client| run.

runs show
=====================================================
.. include:: ../../includes_plugin_knife/includes_plugin_knife_reporting_runs_show.rst

Syntax
-----------------------------------------------------
.. include:: ../../includes_plugin_knife/includes_plugin_knife_reporting_runs_show_syntax.rst

Options
-----------------------------------------------------
.. include:: ../../includes_plugin_knife/includes_plugin_knife_reporting_runs_show_options.rst

Examples
-----------------------------------------------------
For example:

.. code-block:: bash

   $ knife runs show foo

will return a detailed list of all |chef client| runs that occurred on a node named "foo".

And:

.. code-block:: bash

   $ knife runs show bar 30077269-59d0-4283-81f6-8d23cbed3a7a

will return details about a specific |chef client| run that occurred on a node named "bar".
