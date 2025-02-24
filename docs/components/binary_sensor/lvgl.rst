LVGL Binary Sensor
==================

.. seo::
    :description: Instructions for setting up an LVGL widget binary sensor.
    :image: ../images/lvgl_c_bns.png

The ``lvgl`` binary sensor platform creates a binary sensor from an LVGL widget
and requires :doc:`LVGL </docs/components/lvgl/index>` to be configured.

Supported widget is :ref:`lvgl-widget-button`. A single binary sensor supports only a single widget; in other words, it's not possible to have multiple widgets associated with a single ESPHome binary sensor component.

Configuration variables:
------------------------

- **widget** (**Required**): The ID of a supported widget configured in LVGL, which will reflect the state of the binary sensor.
- All other variables from :ref:`Binary Sensor <config-binary_sensor>`.

Example:

.. code-block:: yaml

    binary_sensor:
      - platform: lvgl
        widget: btn_id
        name: LVGL push button

See Also
--------
- :doc:`LVGL Main component </docs/components/lvgl/index>`
- :ref:`Button widget <lvgl-widget-button>`
- :doc:`/docs/components/sensor/lvgl`
- :doc:`/docs/components/number/lvgl`
- :doc:`/docs/components/switch/lvgl`
- :doc:`/docs/components/select/lvgl`
- :doc:`/docs/components/light/lvgl`
- :doc:`/docs/components/text/lvgl`
- :doc:`/docs/components/text_sensor/lvgl`
- :ghedit:`Edit`
