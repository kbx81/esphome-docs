LVGL Sensor
===========

.. seo::
    :description: Instructions for setting up an LVGL widget sensor component.
    :image: ../images/lvgl_c_num.png

The ``lvgl`` sensor platform creates a sensor component from an LVGL widget
and requires :doc:`LVGL </docs/components/lvgl/index>` to be configured.

Supported widgets are :ref:`lvgl-widget-arc`, :ref:`lvgl-widget-bar`, :ref:`lvgl-widget-slider` and :ref:`lvgl-widget-spinbox`. A single sensor supports only a single widget; in other words, it's not possible to have multiple widgets associated with a single ESPHome sensor.

Configuration variables:
------------------------

- **widget** (**Required**): The ID of a supported widget configured in LVGL, which will reflect the state of the sensor.
- All other variables from :ref:`Sensor <config-sensor>`.

Example:

.. code-block:: yaml

    sensor:
      - platform: lvgl
        widget: slider_id
        name: LVGL Slider

.. note::

    Widget-specific actions (``lvgl.arc.update``, ``lvgl.bar.update``, ``lvgl.slider.update``, ``lvgl.spinbox.update``, ``lvgl.spinbox.decrement``, ``lvgl.spinbox.increment``) will trigger corresponding component updates to be sent to Home Assistant.

See Also
--------
- :doc:`LVGL Main component </docs/components/lvgl/index>`
- :ref:`Arc widget <lvgl-widget-arc>`
- :ref:`Bar widget <lvgl-widget-bar>`
- :ref:`Slider widget <lvgl-widget-slider>`
- :ref:`Spinbox widget <lvgl-widget-spinbox>`
- :doc:`/docs/components/binary_sensor/lvgl`
- :doc:`/docs/components/switch/lvgl`
- :doc:`/docs/components/select/lvgl`
- :doc:`/docs/components/light/lvgl`
- :doc:`/docs/components/number/lvgl`
- :doc:`/docs/components/text/lvgl`
- :doc:`/docs/components/text_sensor/lvgl`
- :ghedit:`Edit`
