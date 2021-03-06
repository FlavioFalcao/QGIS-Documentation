|updatedisclaimer|

.. index::
   single:plugins

.. _plugins:

************
|qg| Plugins
************

|qg| has been designed with a plugin architecture. This allows many new
features/functions to be easily added to the application. Many of the features
in |qg| are actually implemented as plugins.

.. :index::
    single:plugins;managing

.. _managing_plugins:

The Plugins Menus
=================

The menus in the Plugins dialog allow the user to install, uninstall and upgrade plugins in
different ways.

|mActionShowPluginManager| :guilabel:`All`

Here all the plugins available are listed. You can find core and external plugins
here. Use **[Upgrade all]** to look for new versions of the plugins . Furthermore can use **[Install plugin]**
if a plugin is listet but not installed and **[Uninstall plugin]** as well as **[Reinstall plugin]** 
if the plugin is installed. If a plugin is installed it can be de/activated using the checkbox.

.. _figure_plugins_1:

.. only:: html

   **Figure Plugins 1:**

.. figure:: /static/user_manual/plugins/plugins_all.png
   :align: center
   :width: 30em

   The |mActionShowPluginManager| :guilabel:`All` menu |nix|


|plugin_installed| :guilabel:`Installed`

In this menu you can find only the installed plugins. The external plugins can be uninstallled and reinstalled
using the **[Uninstall plugin]** and **[Reinstall plugin]** buttons. You can **[Upgrade all]** here as well.

.. _figure_plugins_2:

.. only:: html

   **Figure Plugins 2:**

.. figure:: /static/user_manual/plugins/plugins_installed.png
   :align: center
   :width: 30em

   The |plugin_installed| :guilabel:`Installed` menu |nix|


|plugin| :guilabel:`Not installed`

This menu lists all plugins available that are not installed. You can use the **[Install plugin]** button
to implement a plugin into |qg|.

.. _figure_plugins_3:

.. only:: html

   **Figure Plugins 3:**

.. figure:: /static/user_manual/plugins/plugins_not_installed.png
   :align: center
   :width: 30em

   The |plugin| :guilabel:`Not installed` menu |nix|


|plugin_upgrade| :guilabel:`Upgradeable`

If you activated |checkbox| :guilabel:`Show also experimental plugins` in the
|mActionTransformSettings| :guilabel:`Settings` menu you can use this menu
to look for more recent plugin versions. This can be done with the **[Upgrade plugin]** or 
**[Upgrade all]** buttons.

.. _figure_plugins_4:

.. only:: html

   **Figure Plugins 4:**

.. figure:: /static/user_manual/plugins/plugins_upgradeable.png
   :align: center
   :width: 30em

   The |plugin_upgrade| :guilabel:`Upgradeable` menu |nix|


|mActionTransformSettings| :guilabel:`Settings` 

In this menu you can use the following options:

* |checkbox| :guilabel:`Check for updates on startup`. Whenever a new plugin or
  a plugin update is available QGIS will inform you 'every time QGIS starts', 'once a day',
  'every 3 days', 'every week', 'every 2 weeks' or 'every month'.
* |checkbox| :guilabel:`Show also experimental plugins` . QGIS will show you 
  plugins in early state of development which are generally unsuitable for production
  use.
* |checkbox| :guilabel:`Show also deprecated plugins`. These plugins are deprecated
  and generally unsuitable for production use.

To add external author repositories, click **[Add...]** in the :guilabel:`Plugin repositories` section.
If you do not want one or more of the added repositories, they can be disabled
via the **[Edit...]** button, or completely removed with the **[Delete]** button.

.. _figure_plugins_5:

.. only:: html

   **Figure Plugins 5:**

.. figure:: /static/user_manual/plugins/plugins_settings.png
   :align: center
   :width: 30em

   The |mActionTransformSettings| :guilabel:`Settings` menu |nix|

The :guilabel:`Search` function is available in nearly every menu (except |mActionTransformSettings| :guilabel:`Settings`).
Here you can look for specific plugins.

.. tip:: **Core and external plugins**
   
   QGIS plugins are implemented either as **Core Plugins** or **External Plugins**.
   **Core Plugins** are maintained by the |qg| Development Team and are
   automatically part of every |qg| distribution. They are written in one of two
   languages: C++ or Python.
   **External Plugins** are currently all written in Python. They are stored in
   external repositories and maintained by the individual authors. 

Detailed documentation about the usage, minimum |qg| version, homepage, authors,
and other important information are provided for the 'Official' |qg| Repository
at http://plugins.qgis.org/plugins/. For other external repositories, they might
be available with the external plugins themselves. In general it is not included
in this manual.
