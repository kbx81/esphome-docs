LVGL Text
=========

.. seo::
    :description: Instructions for setting up an LVGL Text component.
    :image: ../images/lvgl_c_txt.png

The ``lvgl`` text platform creates an editable text component from an LVGL textual widget and requires :doc:`LVGL </docs/components/lvgl/index>` to be configured.

Supported widgets are :ref:`lvgl-widget-label` and :ref:`lvgl-widget-textarea`. A single text supports only a single widget; in other words, it's not possible to have multiple widgets associated with a single ESPHome text component.

Configuration variables:
------------------------

- **widget** (**Required**): The ID of a ``textarea`` widget configured in LVGL, which will reflect the state of the text component.
- All other variables from :ref:`Text <config-text>`.

Example:

.. code-block:: yaml

    text:
      - platform: lvgl
        widget: textarea_id
        name: "Textarea 1 text"

.. note::

    Widget-specific actions (``lvgl.label.update``, ``lvgl.textarea.update``) will trigger correspponding component updates to be sent to Home Assistant.

See Also
--------
- :doc:`LVGL Main component </docs/components/lvgl/index>`
- :ref:`Label widget <lvgl-widget-label>`
- :ref:`Textarea widget <lvgl-widget-textarea>`
- :doc:`/docs/components/binary_sensor/lvgl`
- :doc:`/docs/components/sensor/lvgl`
- :doc:`/docs/components/number/lvgl`
- :doc:`/docs/components/switch/lvgl`
- :doc:`/docs/components/light/lvgl`
- :doc:`/docs/components/select/lvgl`
- :doc:`/docs/components/text_sensor/lvgl`
- :ghedit:`Edit`
