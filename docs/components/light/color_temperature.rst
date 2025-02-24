Color Temperature Light
=======================

.. seo::
    :description: Instructions for setting up Color Temperature lights.
    :image: brightness-medium.svg

The ``color_temperature`` light platform creates a Color Temperature
light from 2 :ref:`float output components <output>`. One channel controls the LED temperature,
and the other channel controls the brightness.

.. code-block:: yaml

    # Example configuration entry
    light:
      - platform: color_temperature
        name: "Livingroom Lights"
        color_temperature: output_component1
        brightness: output_component2
        cold_white_color_temperature: 6536 K
        warm_white_color_temperature: 2000 K

Configuration variables:
------------------------

- **color_temperature** (**Required**, :ref:`config-id`): The id of the float :ref:`output` to use for the color temperature. It returns a float from 0 to 1 in the mired scale. Hereby 0 corresponds to the cold white temperature and 1 to the warm white temperature.
- **brightness** (**Required**, :ref:`config-id`): The id of the float :ref:`output` to use for the brightness. It returns a float from 0 to 1.
- **cold_white_color_temperature** (**Required**, float): The coldest color temperature supported by this light. This
  is the lowest value when expressed in `mireds <https://en.wikipedia.org/wiki/Mired>`__, or the highest value when
  expressed in Kelvin.
- **warm_white_color_temperature** (**Required**, float): The warmest color temperature supported by this light. This
  is the highest value when expressed in `mireds <https://en.wikipedia.org/wiki/Mired>`__, or the lowest value when
  expressed in Kelvin.
- All other options from :ref:`Light <config-light>`.

See Also
--------

- :doc:`/docs/components/output/index`
- :doc:`/docs/components/light/index`
- :doc:`/docs/components/light/cwww`
- :doc:`/docs/components/light/rgb`
- :doc:`/docs/components/light/rgbw`
- :doc:`/docs/components/light/rgbww`
- :doc:`/docs/components/light/rgbct`
- :doc:`/docs/components/power_supply`
- :doc:`/docs/components/output/ledc`
- :doc:`/docs/components/output/esp8266_pwm`
- :doc:`/docs/components/output/pca9685`
- :doc:`/docs/components/output/tlc59208f`
- :apiref:`color_temperature/ct_light_output.h`
- :ghedit:`Edit`
