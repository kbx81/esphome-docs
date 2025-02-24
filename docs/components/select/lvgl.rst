LVGL Select
===========

.. seo::
    :description: Instructions for setting up an LVGL widget select.
    :image: ../images/lvgl_c_sel.png

The ``lvgl`` select platform creates a select from an LVGL widget
and requires :doc:`LVGL </docs/components/lvgl/index>` to be configured.

Supported widgets are :ref:`lvgl-widget-dropdown` and :ref:`lvgl-widget-roller`. A single select supports only a single widget; in other words, it's not possible to have multiple widgets associated with a single ESPHome select component.

Configuration variables:
------------------------

- **widget** (**Required**): The ID of a supported widget configured in LVGL, which will reflect the state of the select.
- All other variables from :ref:`Select <config-select>`.

Example:

.. code-block:: yaml

    select:
      - platform: lvgl
        widget: dropdown_id
        name: LVGL Dropdown

.. note::

    Widget-specific actions (``lvgl.dropdown.update``, ``lvgl.roller.update``) will trigger correspponding component updates to be sent to Home Assistant.

See Also
--------
- :doc:`LVGL Main component </docs/components/lvgl/index>`
- :ref:`Roller widget <lvgl-widget-roller>`
- :ref:`Dropdown widget <lvgl-widget-dropdown>`
- :doc:`/docs/components/binary_sensor/lvgl`
- :doc:`/docs/components/sensor/lvgl`
- :doc:`/docs/components/number/lvgl`
- :doc:`/docs/components/switch/lvgl`
- :doc:`/docs/components/light/lvgl`
- :doc:`/docs/components/text/lvgl`
- :doc:`/docs/components/text_sensor/lvgl`
- :ghedit:`Edit`
