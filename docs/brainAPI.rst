
.. _BrainClass:

Main *Brain* class inputs
~~~~~~~~~~~~~~~~~~~~~~~~~

.. currentmodule:: visbrain

.. autoclass:: Brain

    .. rubric:: Methods

    .. autosummary::

        ~Brain.show
        ~visbrain.Brain.rotate
        ~visbrain.Brain.background_color
        ~visbrain.Brain.screenshot
        ~visbrain.Brain.load_config
        ~visbrain.Brain.save_config

        ~visbrain.Brain.brain_control
        ~visbrain.Brain.brain_list
        ~visbrain.Brain.add_mesh

        ~visbrain.Brain.sources_control
        ~visbrain.Brain.sources_display
        ~visbrain.Brain.sources_fit_to_vertices
        ~visbrain.Brain.sources_to_convex_hull

        ~visbrain.Brain.cortical_projection
        ~visbrain.Brain.cortical_repartition

        ~visbrain.Brain.time_series_control

        ~visbrain.Brain.pictures_control

        ~visbrain.Brain.connect_control

        ~visbrain.Brain.cbar_control
        ~visbrain.Brain.cbar_select
        ~visbrain.Brain.cbar_list
        ~visbrain.Brain.cbar_export
        ~visbrain.Brain.cbar_autoscale


.. ##########################################################################
..                                    GUI
.. ##########################################################################

GUI functions and settings
~~~~~~~~~~~~~~~~~~~~~~~~~~

Set of functions for an interactive control of the graphical user interface elements.

Show graphical interface
++++++++++++++++++++++++
.. automethod:: visbrain.Brain.show

Rotation
++++++++
.. automethod:: visbrain.Brain.rotate

Background color
++++++++++++++++
.. automethod:: visbrain.Brain.background_color

Screenshot
++++++++++
.. automethod:: visbrain.Brain.screenshot

.. _LoadSaveConfig:

Load and save GUI configuration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Load an existing configuration
++++++++++++++++++++++++++++++
.. automethod:: visbrain.Brain.load_config

Save the current configuration
++++++++++++++++++++++++++++++
.. automethod:: visbrain.Brain.save_config

.. ##########################################################################
..                                    BRAIN
.. ##########################################################################

.. _BrainApi:

Brain methods
~~~~~~~~~~~~~

Set of functions for an interactive control of the main brain object. Use the methods below to define which brain template or hemisphere to display, the transparency level...

Control the brain
+++++++++++++++++
.. automethod:: visbrain.Brain.brain_control

List of available templates
+++++++++++++++++++++++++++
.. automethod:: visbrain.Brain.brain_list


Add mesh to the scene
+++++++++++++++++++++
.. automethod:: visbrain.Brain.add_mesh

.. ##########################################################################
..                                 SOURCES
.. ##########################################################################

.. _SourcesApi:

Sources methods
~~~~~~~~~~~~~~~

Set of functions for an interactive control of sources object. Use the methods below to pass some data to sources, to control the transparency level, to run the cortical projection / repartition...

Control sources
+++++++++++++++
.. automethod:: visbrain.Brain.sources_control

Select sources
++++++++++++++
.. automethod:: visbrain.Brain.sources_display

Fit to an object
++++++++++++++++
.. automethod:: visbrain.Brain.sources_fit_to_vertices

Convert into convex hull
++++++++++++++++++++++++
.. automethod:: visbrain.Brain.sources_to_convex_hull

.. _CortProj:

Cortical projection
+++++++++++++++++++

.. automethod:: visbrain.Brain.cortical_projection

.. _CortRepart:

Cortical repartition
++++++++++++++++++++
.. automethod:: visbrain.Brain.cortical_repartition

.. ##########################################################################
..                               TIME-SERIES
.. ##########################################################################

.. _TimeSeriesApi:

Time-series methods
~~~~~~~~~~~~~~~~~~~

Time-series control
+++++++++++++++++++
.. automethod:: visbrain.Brain.time_series_control


.. ##########################################################################
..                                PICTURES
.. ##########################################################################

.. _PicturesApi:

Pictures methods
~~~~~~~~~~~~~~~~

Pictures control
++++++++++++++++
.. automethod:: visbrain.Brain.pictures_control

.. ##########################################################################
..                           CONNECTIVITY
.. ##########################################################################

.. _ConnectApi:

Connectivity methods
~~~~~~~~~~~~~~~~~~~~

Set of functions for an interactive control of connectivity object. Use the methods below to pass some data to connectivity, to control the transparency level...

Control Connectivity
++++++++++++++++++++
.. automethod:: visbrain.Brain.connect_control

.. ##########################################################################
..                              COLORBAR
.. ##########################################################################

.. _CbarApi:

Colorbar methods
~~~~~~~~~~~~~~~~

Colorbar control
++++++++++++++++
.. automethod:: visbrain.Brain.cbar_control

Select a colorbar
+++++++++++++++++
.. automethod:: visbrain.Brain.cbar_select

List of available colorbars
+++++++++++++++++++++++++++
.. automethod:: visbrain.Brain.cbar_list

Export colorbar
+++++++++++++++
.. automethod:: visbrain.Brain.cbar_export

Auto-scaling
++++++++++++
.. automethod:: visbrain.Brain.cbar_autoscale