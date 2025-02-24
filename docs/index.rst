.. title:: ESPHome

.. seo::
    :description: ESPHome Homepage - Reimagining DIY Home Automation. ESPHome is a framework that
      tries to provide the best possible use experience for using IoT microcontrollers
      for Home Automation. Just write a simple YAML configuration file and get your own customized firmware.
    :image: logo.svg

.. image:: /images/logo-docs.svg

.. _devices:

Supported Microcontrollers
--------------------------

.. imgtable::

    ESP32, docs/components/esp32, esp32.svg
    ESP8266, docs/components/esp8266, esp8266.svg
    RP2040, docs/components/rp2040, rp2040.svg
    BK72xx, docs/components/libretiny, bk72xx.svg
    RTL87xx, docs/components/libretiny, rtl87xx.svg
    Host, docs/components/host, host.svg, dark-invert

Microcontroller Peripherals
---------------------------

Peripherals which directly support the operation of the microcontroller's processor(s).

.. imgtable::

    PSRAM, docs/components/psram, psram.svg
    Deep Sleep, docs/components/deep_sleep, hotel.svg, dark-invert

ESPHome Automations
-------------------

*"When this happens, I want it to do that..."*

Automations are how we customize ESPHome devices to respond/behave exactly how you want them to.

.. imgtable::

    Overview, docs/automations/index, description.svg, dark-invert
    "Actions, Triggers, Conditions", docs/automations/actions, description.svg, dark-invert
    Templates, docs/automations/templates, description.svg, dark-invert

ESPHome Components
------------------

ESPHome-specific components or components supporting ESPHome device provisioning post-installation.

.. imgtable::

    Core, docs/components/esphome, cloud-circle.svg, dark-invert
    Captive Portal, docs/components/captive_portal, wifi-strength-alert-outline.svg, dark-invert
    Copy, docs/components/copy, content-copy.svg, dark-invert
    Demo, docs/components/demo, description.svg, dark-invert
    External Components, docs/components/external_components, external_components.svg, dark-invert
    Globals, docs/components/globals, description.svg, dark-invert
    Improv via BLE, docs/components/esp32_improv, improv.svg, dark-invert
    Improv via Serial, docs/components/improv_serial, improv.svg, dark-invert
    Interval, docs/components/interval, description.svg, dark-invert
    JSON, docs/components/json, json.svg, dark-invert
    XXTEA, docs/components/xxtea, xxtea.svg
    Script, docs/components/script, description.svg, dark-invert

ESPHome Configuration
---------------------

Streamline your ESPHome configuration and/or use components provided by other contributors.

.. imgtable::

    External Components, docs/components/external_components, external_components.svg, dark-invert
    Packages, docs/components/packages, description.svg, dark-invert
    Substitutions, docs/components/substitutions, description.svg, dark-invert

Network Hardware
----------------

.. imgtable::

    WiFi, docs/components/wifi, network-wifi.svg, dark-invert
    ESP32 Ethernet, docs/components/ethernet, ethernet.svg, dark-invert

Network Protocols
-----------------

.. imgtable::

    Network Core, docs/components/network, server-network.svg, dark-invert
    Native API, docs/components/api, server-network.svg, dark-invert
    MQTT, docs/components/mqtt, mqtt.png
    HTTP Request, docs/components/http_request, connection.svg, dark-invert
    mDNS, docs/components/mdns, radio-tower.svg, dark-invert
    WireGuard, docs/components/wireguard, wireguard_custom_logo.svg, dark-invert
    StatsD, docs/components/statsd, connection.svg, dark-invert
    UDP, docs/components/udp, udp.svg

Bluetooth/BLE
-------------

.. imgtable::

    ESP32 BLE Beacon, docs/components/esp32_ble_beacon, bluetooth.svg, dark-invert
    ESP32 BLE Client, docs/components/ble_client, bluetooth.svg, dark-invert
    ESP32 BLE Tracker, docs/components/esp32_ble_tracker, bluetooth.svg, dark-invert
    Bluetooth Proxy, docs/components/bluetooth_proxy, bluetooth.svg, dark-invert
    Improv via BLE, docs/components/esp32_improv, improv.svg, dark-invert

Management and Monitoring
-------------------------

.. imgtable::

    Debug, docs/components/debug, bug-report.svg, dark-invert
    Logger, docs/components/logger, file-document-box.svg, dark-invert
    Prometheus, docs/components/prometheus, prometheus.svg
    StatsD, docs/components/statsd, connection.svg, dark-invert
    Safe Mode, docs/components/safe_mode, restart-alert.svg, dark-invert
    Web Server, docs/components/web_server, http.svg
    ESP32 Camera Web Server, docs/components/esp32_camera_web_server, camera.svg, dark-invert

Update Installation
-------------------

Install updates over-the-air (OTA).

.. imgtable::

    OTA Core, docs/components/ota/index, system-update.svg, dark-invert
    OTA Updates, docs/components/ota/esphome, system-update.svg, dark-invert
    OTA Updates via HTTP Request, docs/components/ota/http_request, system-update.svg, dark-invert

Update Management
-----------------

Create update entities simplifying management of OTA updates.

.. imgtable::

    Update Core, docs/components/update/index, system-update.svg, dark-invert
    Managed Updates, docs/components/update/http_request, system-update.svg, dark-invert

Hardware Peripheral Interfaces/Busses
-------------------------------------

.. imgtable::

    1-Wire, docs/components/one_wire, one-wire.svg
    CAN Bus, docs/components/canbus/index, canbus.svg
    I²C Bus, docs/components/i2c, i2c.svg
    I²S Audio, docs/components/i2s_audio, i2s_audio.svg
    OpenTherm, docs/components/opentherm, opentherm.png
    SPI Bus, docs/components/spi, spi.svg
    UART, docs/components/uart, uart.svg

I/O Expanders/Multiplexers
--------------------------

.. imgtable::

    CH422G, docs/components/ch422g, ch422g.svg
    MAX6956 - I²C Bus, docs/components/max6956, max6956.jpg
    MCP230XX - I²C Bus, docs/components/mcp230xx, mcp230xx.svg
    MCP23SXX - SPI Bus, docs/components/mcp23Sxx, mcp23sxx.svg
    PCA6416A, docs/components/pca6416a, pca6416a.svg
    PCA9554, docs/components/pca9554, pca9554a.jpg
    PCF8574, docs/components/pcf8574, pcf8574.jpg
    SN74HC165, docs/components/sn74hc165, sn74hc595.jpg
    SN74HC595, docs/components/sn74hc595, sn74hc595.jpg
    SX1509, docs/components/sx1509, sx1509.jpg
    TCA9548A I²C Multiplexer, docs/components/tca9548a, tca9548a.jpg
    TCA9555, docs/components/tca9555, tca9555.svg
    WeiKai SPI/I²C UART/IO Expander, docs/components/weikai, wk2168.jpg
    XL9535, docs/components/xl9535, xl9535.svg

CAN Bus
-------

.. imgtable::

    CAN Bus, docs/components/canbus/index, canbus.svg
    ESP32 CAN, docs/components/canbus/esp32_can, esp32.svg
    MCP2515, docs/components/canbus/mcp2515, mcp2515.svg

Sensor Components
-----------------

Sensors are organized into categories; if a given sensor fits into more than one category, it will appear multiple times.

Core
****

.. imgtable::

    Sensor Core, docs/components/sensor/index, folder-open.svg, dark-invert
    Template Sensor, docs/components/sensor/template, description.svg, dark-invert
    Home Assistant, docs/components/sensor/homeassistant, home-assistant.svg, dark-invert
    MQTT Subscribe, docs/components/sensor/mqtt_subscribe, mqtt.png
    Uptime Sensor, docs/components/sensor/uptime, timer.svg, dark-invert
    WiFi Signal Strength, docs/components/sensor/wifi_signal, network-wifi.svg, dark-invert

Air Quality
***********

.. imgtable::

    AGS10, docs/components/sensor/ags10, ags10.jpg, Volatile Organic Compound Sensor
    AirThings BLE, docs/components/sensor/airthings_ble, airthings_logo.png, Radon, CO2, Volatile organics
    CCS811, docs/components/sensor/ccs811, ccs811.jpg, CO2 & Volatile organics
    EE895, docs/components/sensor/ee895, EE895.png,  CO2 & Temperature & Pressure
    ENS160, docs/components/sensor/ens160, ens160.jpg, CO2 & Air Quality
    GCJA5, docs/components/sensor/gcja5, gcja5.svg, Particulate
    GP2Y1010AU0F, docs/components/sensor/gp2y1010au0f, gp2y1010au0f.png, Particulate
    Grove Multichannel Gas V2, docs/components/sensor/grove_gas_mc_v2, grove-gas-mc-v2.png, NO2 & CO & Ethanol & Volatile organics
    HM3301, docs/components/sensor/hm3301, hm3301.jpg, Particulate
    iAQ-Core, docs/components/sensor/iaqcore, iaqcore.jpg, CO2 & Volatile organics
    MH-Z19, docs/components/sensor/mhz19, mhz19.jpg, CO2 & Temperature
    MiCS-4514, docs/components/sensor/mics_4514, mics_4514.jpg, Gas concentration
    PM1006 Sensor, docs/components/sensor/pm1006, pm1006.jpg, Particulate
    PMSA003I, docs/components/sensor/pmsa003i, pmsa003i.jpg, Particulate
    PMSX003, docs/components/sensor/pmsx003, pmsx003.svg, Particulate
    RadonEye BLE, docs/components/sensor/radon_eye_ble, radon_eye_logo.png, Radon
    SCD30, docs/components/sensor/scd30, scd30.jpg, CO2 & Temperature & Humidity
    SCD4X, docs/components/sensor/scd4x, scd4x.jpg, CO2 & Temperature & Humidity
    SDS011 Sensor, docs/components/sensor/sds011, sds011.jpg, Particulate
    SEN0321, docs/components/sensor/sen0321, sen0321.jpg, Ozone
    SEN5x, docs/components/sensor/sen5x, sen54.jpg, Temperature & Humidity & Volatile organics & NOx
    SenseAir, docs/components/sensor/senseair, senseair_s8.jpg, CO2
    SFA30, docs/components/sensor/sfa30, sfa30.jpg, Formaldehyde
    SGP30, docs/components/sensor/sgp30, sgp30.jpg, CO2 & Volatile organics
    SGP4x, docs/components/sensor/sgp4x, sgp40.jpg, Volatile organics & NOx
    SM300D2, docs/components/sensor/sm300d2, sm300d2.jpg, Air quality
    SPS30, docs/components/sensor/sps30, sps30.jpg, Particulate
    T6613/15, docs/components/sensor/t6615, t6615.jpg, CO2
    ZyAura, docs/components/sensor/zyaura, zgm053.jpg, CO2 & Temperature & Humidity

Analogue
********

.. imgtable::

    ADC, docs/components/sensor/adc, flash.svg, ESP internal, dark-invert
    ADC128S102, docs/components/sensor/adc128s102, adc128s102.png , 8-channel ADC
    ADS1115, docs/components/sensor/ads1115, ads1115.jpg, 4-channel ADC
    ADS1118, docs/components/sensor/ads1118, ads1118.jpg, 4-channel ADC
    CD74HC4067, docs/components/sensor/cd74hc4067, cd74hc4067.jpg, 16-channel analog multiplexer
    MCP3008, docs/components/sensor/mcp3008, mcp3008.jpg, 8-channel ADC
    MCP3204 / MCP3208, docs/components/sensor/mcp3204, mcp3204.jpg, 4-channel ADC
    NAU7802, docs/components/sensor/nau7802, nau7802.jpg, ADC
    Resistance, docs/components/sensor/resistance, omega.svg, dark-invert

Bluetooth Low Energy (BLE)
**************************

.. imgtable::

    Alpha3, docs/components/sensor/alpha3, alpha3.jpg
    AM43, docs/components/sensor/am43, am43.jpg, Lux & Battery level
    BLE Client Sensor, docs/components/sensor/ble_client, bluetooth.svg, dark-invert
    BLE RSSI, docs/components/sensor/ble_rssi, bluetooth.svg, dark-invert
    HHCCJCY10 (MiFlora Pink), docs/components/sensor/xiaomi_hhccjcy10, xiaomi_hhccjcy10.jpg, Soil moisture & Temperature & Light
    Inkbird IBS-TH1 Mini, docs/components/sensor/inkbird_ibsth1_mini, inkbird_isbth1_mini.jpg, Temperature & Humidity
    Mopeka Pro Check LP, docs/components/sensor/mopeka_pro_check, mopeka_pro_check.jpg, Tank level
    Mopeka Standard Check LP, docs/components/sensor/mopeka_std_check, mopeka_std_check.jpg, Tank level
    RuuviTag, docs/components/sensor/ruuvitag, ruuvitag.jpg, Temperature & Humidity & Accelerometer
    Xiaomi BLE, docs/components/sensor/xiaomi_ble, xiaomi_mijia_logo.jpg, Various

Digital Signals
***************

.. imgtable::

    Duty Cycle, docs/components/sensor/duty_cycle, percent.svg, dark-invert
    Pulse Counter, docs/components/sensor/pulse_counter, pulse.svg, dark-invert
    Pulse Meter, docs/components/sensor/pulse_meter, pulse.svg, dark-invert
    Pulse Width, docs/components/sensor/pulse_width, pulse.svg, dark-invert

Distance
********

.. imgtable::

    A01NYUB, docs/components/sensor/a01nyub, a01nyub.jpg, Acoustic distance
    A02YYUW, docs/components/sensor/a02yyuw, a02yyuw.jpg, Acoustic distance
    HRXL MaxSonar WR, docs/components/sensor/hrxl_maxsonar_wr, hrxl_maxsonar_wr.jpg, Acoustic distance
    JSN-SR04T, docs/components/sensor/jsn_sr04t, jsn-sr04t-v3.jpg, Acoustic distance
    TOF10120, docs/components/sensor/tof10120, tof10120.jpg, IR optical distance
    Ultrasonic Sensor, docs/components/sensor/ultrasonic, ultrasonic.jpg, Acoustic distance
    VL53L0x, docs/components/sensor/vl53l0x, vl53l0x.jpg, IR optical distance
    Zio Ultrasonic Sensor, docs/components/sensor/zio_ultrasonic, zio_ultrasonic.jpg, Acoustic distance

Electricity
***********

.. imgtable::

    ADE7880, docs/components/sensor/ade7880, ade7880.svg, Voltage & Current & Power
    ADE7953, docs/components/sensor/ade7953, ade7953.svg, Power
    ATM90E26, docs/components/sensor/atm90e26, atm90e26.jpg, Voltage & Current & Power
    ATM90E32, docs/components/sensor/atm90e32, atm90e32.jpg, Voltage & Current & Power
    BL0906, docs/components/sensor/bl0906, bl0906.png, Voltage & Current & Power & Energy
    BL0939, docs/components/sensor/bl0939, bl0939.png, Voltage & Current & Power & Energy
    BL0940, docs/components/sensor/bl0940, bl0940.png, Voltage & Current & Power
    BL0942, docs/components/sensor/bl0942, bl0942.png, Voltage & Current & Power
    CS5460A, docs/components/sensor/cs5460a, cs5460a.png, Voltage & Current & Power
    CSE7761, docs/components/sensor/cse7761, cse7761.svg, Voltage & Current & Power
    CSE7766, docs/components/sensor/cse7766, cse7766.svg, Voltage & Current & Power
    CT Clamp, docs/components/sensor/ct_clamp, ct_clamp.jpg, Alternating Current (AC)
    Daly BMS, docs/components/sensor/daly_bms, daly_bms.jpg, Voltage & Current & Power
    DSMR, docs/components/sensor/dsmr, dsmr.svg, Electrical counter
    HLW8012, docs/components/sensor/hlw8012, hlw8012.svg, Voltage & Current & Power
    INA219, docs/components/sensor/ina219, ina219.jpg, Direct Current (DC)
    INA226, docs/components/sensor/ina226, ina226.jpg, Direct Current (DC) & Power
    INA228, docs/components/sensor/ina2xx, ina228.jpg, DC Voltage & Current & Power & Charge
    INA229, docs/components/sensor/ina2xx, ina2xx.jpg, DC Voltage & Current & Power & Charge
    INA237, docs/components/sensor/ina2xx, ina2xx.jpg, DC Voltage & Current & Power
    INA238, docs/components/sensor/ina2xx, ina2xx.jpg, DC Voltage & Current & Power
    INA239, docs/components/sensor/ina2xx, ina2xx.jpg, DC Voltage & Current & Power
    INA260, docs/components/sensor/ina260, ina260.jpg, DC Current & Power
    INA3221, docs/components/sensor/ina3221, ina3221.jpg, 3-Ch DC current
    Kamstrup KMP, docs/components/sensor/kamstrup_kmp, kamstrup_kmp.jpg, District Heating Meter
    MAX9611, docs/components/sensor/max9611, max9611.jpg, Voltage & Current & Power & Temperature
    PZEM AC, docs/components/sensor/pzemac, pzem-ac.jpg, Voltage & Current & Power
    PZEM DC, docs/components/sensor/pzemdc, pzem-dc.jpg, Voltage & Current & Power
    PZEM004T, docs/components/sensor/pzem004t, pzem004t.svg, Voltage & Current & Power
    SDM Meter, docs/components/sensor/sdm_meter, sdm220m.jpg, Modbus energy monitor
    Selec Meter, docs/components/sensor/selec_meter, selec_meter_em2m.jpg, Modbus energy monitor
    Teleinfo, docs/components/sensor/teleinfo, teleinfo.jpg, Electrical counter
    Total Daily Energy, docs/components/sensor/total_daily_energy, sigma.svg, dark-invert

Environmental
*************

.. imgtable::

    Absolute Humidity, docs/components/sensor/absolute_humidity, water-drop.svg, dark-invert
    AHT10 / AHT20 / AHT21 / DHT20, docs/components/sensor/aht10, aht10.jpg, Temperature & Humidity
    AirThings BLE, docs/components/sensor/airthings_ble, airthings_logo.png, Temperature & Humidity & Pressure
    AM2315C, docs/components/sensor/am2315c, am2315c.jpg, Temperature & Humidity
    AM2320, docs/components/sensor/am2320, am2320.jpg, Temperature & Humidity
    b-parasite, docs/components/sensor/b_parasite, b_parasite.jpg, Moisture & Temperature & Humidity & Light
    BME280, docs/components/sensor/bme280, bme280.jpg, Temperature & Humidity & Pressure
    BME68x via BSEC2, docs/components/sensor/bme68x_bsec2, bme680.jpg, Temperature & Humidity & Pressure & Gas
    BME680 via BSEC, docs/components/sensor/bme680_bsec, bme680.jpg, Temperature & Humidity & Pressure & Gas
    BME680, docs/components/sensor/bme680, bme680.jpg, Temperature & Humidity & Pressure & Gas
    BMP085, docs/components/sensor/bmp085, bmp180.jpg, Temperature & Pressure
    BMP280, docs/components/sensor/bmp280, bmp280.jpg, Temperature & Pressure
    BMP388 and BMP390, docs/components/sensor/bmp3xx, bmp388.jpg, Temperature & Pressure
    BMP581, docs/components/sensor/bmp581, bmp581.jpg, Temperature & Pressure
    Dallas DS18B20, docs/components/sensor/dallas_temp, dallas.jpg, Temperature
    DHT, docs/components/sensor/dht, dht.jpg, Temperature & Humidity
    DHT12, docs/components/sensor/dht12, dht12.jpg, Temperature & Humidity
    DPS310, docs/components/sensor/dps310, dps310.jpg, Temperature & Pressure
    EMC2101, docs/components/emc2101, emc2101.jpg, Temperature
    ENS160, docs/components/sensor/ens160, ens160.jpg, CO2 & Air Quality
    ENS210, docs/components/sensor/ens210, ens210.jpg, Temperature & Humidity
    HDC1080, docs/components/sensor/hdc1080, hdc1080.jpg, Temperature & Humidity
    HHCCJCY10 (MiFlora Pink), docs/components/sensor/xiaomi_hhccjcy10, xiaomi_hhccjcy10.jpg, Soil moisture & Temperature & Light
    Honeywell ABP, docs/components/sensor/honeywellabp, honeywellabp.jpg, Pressure & Temperature
    Honeywell ABP2 I2C, docs/components/sensor/honeywellabp2_i2c, honeywellabp.jpg, Pressure & Temperature
    Honeywell HIH I2C, docs/components/sensor/honeywell_hih_i2c, honeywellhih.jpg, Temperature & Humidity
    HTE501, docs/components/sensor/hte501, HTE501.png, Temperature & Humidity
    HTU21D / Si7021 / SHT21, docs/components/sensor/htu21d, htu21d.jpg, Temperature & Humidity
    HTU31D, docs/components/sensor/htu31d, htu31d.jpg, Temperature & Humidity
    Hydreon Rain Sensor, docs/components/sensor/hydreon_rgxx, hydreon_rg9.jpg, Rain
    HYT271, docs/components/sensor/hyt271, hyt271.jpg, Temperature & Humidity
    Inkbird IBS-TH1 Mini, docs/components/sensor/inkbird_ibsth1_mini, inkbird_isbth1_mini.jpg, Temperature & Humidity
    Internal Temperature, docs/components/sensor/internal_temperature, thermometer.svg, Temperature, dark-invert
    MCP9808, docs/components/sensor/mcp9808, mcp9808.jpg, Temperature
    MH-Z19, docs/components/sensor/mhz19, mhz19.jpg, CO2 & Temperature
    MLX90614, docs/components/sensor/mlx90614, mlx90614.jpg, Temperature
    MPL3115A2, docs/components/sensor/mpl3115a2, mpl3115a2.jpg, Temperature & Pressure
    MS5611, docs/components/sensor/ms5611, ms5611.jpg, Pressure
    MS8607, docs/components/sensor/ms8607, ms8607.jpg, Temperature & Humidity & Pressure
    NPI-19, docs/components/sensor/npi19, npi19.jpg, Pressure
    NTC Thermistor, docs/components/sensor/ntc, ntc.jpg, Temperature
    PMWCS3, docs/components/sensor/pmwcs3, pmwcs3.jpg, Soil moisture & Temperature
    QMP6988, docs/components/sensor/qmp6988, qmp6988_env3.png, Temperature & Pressure
    RadonEye BLE, docs/components/sensor/radon_eye_ble, radon_eye_logo.png, Radon
    RuuviTag, docs/components/sensor/ruuvitag, ruuvitag.jpg, Temperature & Humidity & Accelerometer
    SCD30, docs/components/sensor/scd30, scd30.jpg, CO2 & Temperature & Humidity
    SCD4X, docs/components/sensor/scd4x, scd4x.jpg, CO2 & Temperature & Humidity
    SDP3x / SDP800 Series, docs/components/sensor/sdp3x, sdp31.jpg, Pressure
    SFA30, docs/components/sensor/sfa30, sfa30.jpg, Formaldehyde
    SHT3X-D, docs/components/sensor/sht3xd, sht3xd.jpg, Temperature & Humidity
    SHT4X, docs/components/sensor/sht4x, sht4x.jpg, Temperature & Humidity
    SHTCx, docs/components/sensor/shtcx, shtc3.jpg, Temperature & Humidity
    SMT100, docs/components/sensor/smt100, smt100.jpg, Moisture & Temperature
    STS3X, docs/components/sensor/sts3x, sts3x.jpg, Temperature
    TC74, docs/components/sensor/tc74, tc74.jpg, Temperature
    TEE501, docs/components/sensor/tee501, TEE501.png, Temperature
    TE-M3200, docs/components/sensor/tem3200, tem3200.jpg, Temperature & Pressure
    TMP102, docs/components/sensor/tmp102, tmp102.jpg, Temperature
    TMP1075, docs/components/sensor/tmp1075, tmp1075.jpg, Temperature
    TMP117, docs/components/sensor/tmp117, tmp117.jpg, Temperature
    XGZP68xx Series, docs/components/sensor/xgzp68xx, 6897d.jpg, Differential Pressure

Health/Safety
*************

.. imgtable::

    Seeed Studio MR60BHA2 mmWave, docs/components/seeed_mr60bha2, seeed_mr60bha2.jpg, Breathing & heartbeat detection
    Seeed Studio MR60FDA2 mmWave, docs/components/seeed_mr60fda2, seeed_mr60fda2.jpg, Presence & Fall detection

Light
*****

.. imgtable::

    AM43, docs/components/sensor/am43, am43.jpg, Lux
    APDS9306, docs/components/sensor/apds9306, apds9306.png, Lux
    APDS9960, docs/components/sensor/apds9960, apds9960.jpg, Colour & Gesture
    AS7341, docs/components/sensor/as7341, as7341.jpg, Spectral Color Sensor
    BH1750, docs/components/sensor/bh1750, bh1750.jpg, Lux
    LTR301, docs/components/sensor/ltr501, ltr501.jpg, Lux
    LTR303, docs/components/sensor/ltr_als_ps, ltr303.jpg, Lux
    LTR329, docs/components/sensor/ltr_als_ps, ltr329.jpg, Lux
    LTR390, docs/components/sensor/ltr390, ltr390.jpg, Lux & UV
    LTR501, docs/components/sensor/ltr501, ltr501.jpg, Lux & Proximity
    LTR553, docs/components/sensor/ltr_als_ps, ltr-ps.jpg, Lux & Proximity
    LTR556, docs/components/sensor/ltr_als_ps, ltr-ps.jpg, Lux & Proximity
    LTR558, docs/components/sensor/ltr501, ltr501.jpg, Lux & Proximity
    LTR559, docs/components/sensor/ltr_als_ps, ltr559.jpg, Lux & Proximity
    LTR659, docs/components/sensor/ltr_als_ps, ltr-ps.jpg, Proximity
    MAX44009, docs/components/sensor/max44009, max44009.svg, Lux
    TCS34725, docs/components/sensor/tcs34725, tcs34725.jpg, Lux & RGB colour
    TSL2561, docs/components/sensor/tsl2561, tsl2561.jpg, Lux
    TSL2591, docs/components/sensor/tsl2591, tsl2591.jpg, Lux
    VEML3235, docs/components/sensor/veml3235, veml3235.jpg, Lux
    VEML6030, docs/components/sensor/veml7700, veml6030.jpg, Lux
    VEML7700, docs/components/sensor/veml7700, veml7700.jpg, Lux

Magnetic
********

.. imgtable::

    AS5600, docs/components/sensor/as5600, as5600.jpg, 12-Bit Magnetic Position Sensor
    ESP32 Hall Sensor, docs/components/sensor/esp32_hall, magnet.svg, ESP internal, dark-invert
    HMC5883L, docs/components/sensor/hmc5883l, hmc5883l.jpg, 3-Axis magnetometer
    MLX90393, docs/components/sensor/mlx90393, mlx90393.jpg, 3-Axis magnetometer
    MMC5603, docs/components/sensor/mmc5603, mmc5603.jpg, 3-Axis magnetometer
    MMC5983, docs/components/sensor/mmc5983, mmc5983.jpg, 3-Axis magnetometer
    QMC5883L, docs/components/sensor/qmc5883l, qmc5883l.jpg, 3-Axis magnetometer

Miscellaneous
*************

.. imgtable::

    AS3935, docs/components/sensor/as3935, as3935.jpg, Storm lightning
    b-parasite, docs/components/sensor/b_parasite, b_parasite.jpg, Moisture & Temperature & Humidity & Light
    Binary Sensor Map, docs/components/sensor/binary_sensor_map, binary_sensor_map.jpg, Map binary to value
    Combination, docs/components/sensor/combination, function.svg, dark-invert
    Duty Time, docs/components/sensor/duty_time, timer-play-outline.svg, dark-invert
    EZO sensor circuits, docs/components/sensor/ezo, ezo-ph-circuit.png, (pH)
    FS3000, docs/components/sensor/fs3000, fs3000.jpg, Air velocity
    GDK101, docs/components/sensor/gdk101, gdk101.jpg, Radiation
    Growatt Solar, docs/components/sensor/growatt_solar, growatt.jpg, Solar rooftop
    Havells Solar, docs/components/sensor/havells_solar, havellsgti5000d_s.jpg, Solar rooftop
    Integration, docs/components/sensor/integration, sigma.svg, dark-invert
    Kuntze pool sensor, docs/components/sensor/kuntze, kuntze.jpg
    LVGL widget, docs/components/sensor/lvgl, lvgl_c_num.png
    M5Stack Unit 8 Angle, docs/components/sensor/m5stack_8angle, m5stack_8angle.png
    MAX17043, docs/components/sensor/max17043, max17043.jpg, Battery
    MicroNova pellet stove, docs/components/micronova, micronova.svg
    Modbus Sensor, docs/components/sensor/modbus_controller, modbus.png
    Nextion, docs/components/sensor/nextion, nextion.jpg, Sensors from display
    Person Sensor (SEN21231), docs/components/sensor/sen21231, sen21231.png
    Resol VBus, docs/components/vbus, resol_deltasol_bs_plus.jpg
    Rotary Encoder, docs/components/sensor/rotary_encoder, rotary_encoder.jpg
    SMT100, docs/components/sensor/smt100, smt100.jpg, Moisture & Temperature
    Tuya Sensor, docs/components/sensor/tuya, tuya.png
    TX20, docs/components/sensor/tx20, tx20.jpg, Wind speed & Wind direction
    uFire EC sensor, docs/components/sensor/ufire_ec, ufire_ec.png, EC & Temperature
    uFire ISE sensor, docs/components/sensor/ufire_ise, ufire_ise.png, pH & Temperature
    WireGuard, docs/components/wireguard, wireguard_custom_logo.svg, dark-invert

Motion
******

.. imgtable::

    APDS9960, docs/components/sensor/apds9960, apds9960.jpg, Colour & Gesture
    BMI160, docs/components/sensor/bmi160, bmi160.jpg, Accelerometer & Gyroscope
    LD2410, docs/components/sensor/ld2410, ld2410.jpg, Motion & Presence
    LD2420, docs/components/sensor/ld2420, ld2420.jpg, Motion & Presence
    MPU6050, docs/components/sensor/mpu6050, mpu6050.jpg, Accelerometer & Gyroscope
    MPU6886, docs/components/sensor/mpu6886, mpu6886.jpg, Accelerometer & Gyroscope
    RuuviTag, docs/components/sensor/ruuvitag, ruuvitag.jpg, Temperature & Humidity & Accelerometer
    Seeed Studio MR24HPC1 mmWave, docs/components/seeed_mr24hpc1, seeed-mr24hpc1.jpg, Motion & Presence

Thermocouple
************

.. imgtable::

    KMeterISO, docs/components/sensor/kmeteriso, kmeteriso.jpg, K-Type,
    MAX31855, docs/components/sensor/max31855, max31855.jpg, K-Type
    MAX31856, docs/components/sensor/max31856, max31856.jpg, All types
    MAX31865, docs/components/sensor/max31865, max31865.jpg, Platinum RTD
    MAX6675, docs/components/sensor/max6675, max6675.jpg, K-Type,
    MCP9600, docs/components/sensor/mcp9600, mcp9600.jpg, All types

Weight
******

.. imgtable::

    HX711, docs/components/sensor/hx711, hx711.jpg, Load cell amplifier
    Xiaomi Miscale, docs/components/sensor/xiaomi_miscale, xiaomi_miscale1&2.jpg


Looking for a sensor that outputs its values as an analog voltage? Have a look at the
:doc:`ADC Sensor </docs/components/sensor/adc>` together with a formula like in the `TEMT6000
configuration <https://devices.esphome.io/devices/temt6000>`__.


Binary Sensor Components
------------------------

Binary Sensors are organized into categories; if a given sensor fits into more than one category, it will appear multiple times.

Core
****

.. imgtable::

    Binary Sensor Core, docs/components/binary_sensor/index, folder-open.svg, dark-invert
    Template Binary Sensor, docs/components/binary_sensor/template, description.svg, dark-invert
    GPIO, docs/components/binary_sensor/gpio, gpio.svg
    Home Assistant, docs/components/binary_sensor/homeassistant, home-assistant.svg, dark-invert
    Status, docs/components/binary_sensor/status, server-network.svg, dark-invert
    Switch, docs/components/binary_sensor/switch, electric-switch.svg, dark-invert
    Host SDL2, docs/components/binary_sensor/sdl, sdl.png

Capacitive Touch
****************

.. imgtable::

    CAP1188 Capacitive Touch Sensor, docs/components/binary_sensor/cap1188, cap1188.jpg
    ESP32 Touch Pad, docs/components/binary_sensor/esp32_touch, touch.svg, dark-invert
    MPR121  Capacitive Touch Sensor, docs/components/binary_sensor/mpr121, mpr121.jpg
    TTP229, docs/components/binary_sensor/ttp229, ttp229.jpg

Mechanical
**********

.. imgtable::

    Matrix Keypad, docs/components/matrix_keypad, matrix_keypad.jpg
    TM1637, docs/components/display/tm1637, tm1637.jpg
    TM1638, docs/components/display/tm1638, tm1638.jpg

NFC/RFID
********

Often known as "tag" or "card" readers within the community.

.. imgtable::

    NFC Tag, docs/components/binary_sensor/nfc, nfc.png, dark-invert
    PN532, docs/components/binary_sensor/pn532, pn532.jpg
    PN7150, docs/components/pn7150, pn7150.jpg
    PN716X, docs/components/pn7160, pn716x.jpg
    RC522, docs/components/binary_sensor/rc522, rc522.jpg
    RDM6300, docs/components/binary_sensor/rdm6300, rdm6300.jpg
    Wiegand Reader, docs/components/wiegand, wiegand.jpg

Touchscreen
***********

.. imgtable::

    Touchscreen Core, docs/components/touchscreen/index, touch.svg, dark-invert
    FT5X06, docs/components/touchscreen/ft5x06, indicator.jpg
    GT911, docs/components/touchscreen/gt911, esp32_s3_box_3.png
    Nextion Binary Sensor, docs/components/binary_sensor/nextion, nextion.jpg
    TT21100, docs/components/touchscreen/tt21100, esp32-s3-korvo-2-lcd.png
    LVGL widget, docs/components/binary_sensor/lvgl, lvgl_c_bns.png

Presence Detection
******************

.. imgtable::

    AT581X, docs/components/at581x, at581x.png
    DFRobot mmWave Radar, docs/components/dfrobot_sen0395, dfrobot_sen0395.jpg
    LD2410, docs/components/sensor/ld2410, ld2410.jpg
    LD2420, docs/components/sensor/ld2420, ld2420.jpg
    Seeed Studio MR24HPC1 mmWave, docs/components/seeed_mr24hpc1, seeed-mr24hpc1.jpg

Miscellaneous
*************

.. imgtable::

    Analog Threshold, docs/components/binary_sensor/analog_threshold, analog_threshold.svg, dark-invert
    ESP32 BLE Presence, docs/components/binary_sensor/ble_presence, bluetooth.svg, dark-invert
    Hydreon Rain Sensor Binary Sensor, docs/components/binary_sensor/hydreon_rgxx, hydreon_rg9.jpg
    Modbus Binary Sensor, docs/components/binary_sensor/modbus_controller, modbus.png
    PipSolar - compatible PV Inverter, docs/components/pipsolar, pipsolar.jpg
    Pylontech Batteries, docs/components/pylontech, pylontech.jpg
    Qwiic PIR Motion, docs/components/binary_sensor/qwiic_pir, qwiic_pir.jpg
    Resol VBus, docs/components/vbus, resol_deltasol_bs_plus.jpg
    Tuya Binary Sensor, docs/components/binary_sensor/tuya, tuya.png
    WireGuard, docs/components/wireguard, wireguard_custom_logo.svg, dark-invert

Alarm Control Panel Components
------------------------------

.. imgtable::

    Alarm Control Panel Core, docs/components/alarm_control_panel/index, alarm-panel.svg, dark-invert
    Template Alarm Control Panel, docs/components/alarm_control_panel/template, description.svg, dark-invert

Audio ADC Components
--------------------

.. imgtable::

    Audio ADC Core, docs/components/audio_adc/index, audio_adc.svg
    ES7210, docs/components/audio_adc/es7210, es7210.svg
    ES7243E, docs/components/audio_adc/es7243e, es7243e.svg

Audio DAC Components
--------------------

.. imgtable::

    Audio DAC Core, docs/components/audio_dac/index, audio_dac.svg
    AIC3204, docs/components/audio_dac/aic3204, aic3204.svg
    ES8156, docs/components/audio_dac/es8156, es8156.svg
    ES8311, docs/components/audio_dac/es8311, es8311.svg

Button Components
-----------------

.. imgtable::

    Button Core, docs/components/button/index, folder-open.svg, dark-invert
    Template Button, docs/components/button/template, description.svg, dark-invert
    Factory Reset Button, docs/components/button/factory_reset, restart-alert.svg, dark-invert
    Generic Output Button, docs/components/button/output, upload.svg, dark-invert
    Restart Button, docs/components/button/restart, restart.svg, dark-invert
    Safe Mode Button, docs/components/button/safe_mode, restart-alert.svg, dark-invert
    Shutdown Button, docs/components/button/shutdown, power_settings.svg, dark-invert
    UART Button, docs/components/button/uart, uart.svg
    Wake-on-LAN, docs/components/button/wake_on_lan, power_settings.svg, dark-invert

Climate Components
------------------

.. imgtable::

    Climate Core, docs/components/climate/index, folder-open.svg, dark-invert
    Anova Cooker, docs/components/climate/anova, anova.png
    Bang Bang Controller, docs/components/climate/bang_bang, air-conditioner.svg, dark-invert
    BedJet Climate System, docs/components/climate/bedjet, bedjet.png
    Haier Climate, docs/components/climate/haier, haier.svg
    IR Remote Climate, docs/components/climate/climate_ir, air-conditioner-ir.svg, dark-invert
    Midea, docs/components/climate/midea, midea.svg
    PID Controller, docs/components/climate/pid, function.svg, dark-invert
    Thermostat Controller, docs/components/climate/thermostat, air-conditioner.svg, dark-invert
    Tuya Climate, docs/components/climate/tuya, tuya.png
    Uponor Smatrix Base Pulse Underfloor Heating, docs/components/uponor_smatrix, uponor.svg

Cover Components
----------------

.. imgtable::

    Cover Core, docs/components/cover/index, folder-open.svg, dark-invert
    Template Cover, docs/components/cover/template, description.svg, dark-invert
    AM43 Cover, docs/components/cover/am43, am43.jpg
    Current-Based Cover, docs/components/cover/current_based, flash.svg, dark-invert
    Endstop Cover, docs/components/cover/endstop, electric-switch.svg, dark-invert
    Feedback Cover, docs/components/cover/feedback, feedback_cover.svg, dark-invert
    HE60R Cover, docs/components/cover/he60r, he60r.jpg
    Time-Based Cover, docs/components/cover/time_based, timer.svg, dark-invert
    Tuya Cover, docs/components/cover/tuya, tuya.png

Datetime Components
-------------------

.. imgtable::

    Datetime Core, docs/components/datetime/index, clock-outline.svg, dark-invert
    Template Datetime, docs/components/datetime/template, description.svg, dark-invert

Display Components
------------------

.. imgtable::

    Display Core, docs/components/display/index, folder-open.svg, dark-invert
    Font Renderer, docs/components/font, format-font.svg, dark-invert
    Graph, docs/components/graph, chart-line.svg, dark-invert
    QR Code, docs/components/qr_code, qr-code.svg, dark-invert
    Image, docs/components/image, image-outline.svg, dark-invert
    Animation, docs/components/animation, image-multiple-outline.svg, dark-invert
    Online Image, docs/components/online_image, image-sync-outline.svg, dark-invert
    Display Menu Core, docs/components/display_menu/index, folder-open.svg, dark-invert
    Graphical Display Menu, docs/components/display_menu/graphical_display_menu, graphical_display_menu.png
    LCD Menu, docs/components/display_menu/lcd_menu, lcd_menu.png
    LVGL Graphics, docs/components/lvgl/index, lvgl.png

.. _display-hw:

Display Hardware Platforms
--------------------------

.. imgtable::

    Addressable Light, docs/components/display/addressable_light, addressable_light.jpg
    ILI9xxx, docs/components/display/ili9xxx, ili9341.jpg
    ILI9341, docs/components/display/ili9xxx, ili9341.svg
    ILI9342, docs/components/display/ili9xxx, ili9342.svg
    ILI9481, docs/components/display/ili9xxx, ili9481.svg
    ILI9486, docs/components/display/ili9xxx, ili9341.jpg
    ILI9488, docs/components/display/ili9xxx, ili9488.svg
    WSPICOLCD, docs/components/display/ili9xxx, ili9488.svg
    Inkplate, docs/components/display/inkplate6, inkplate6.jpg
    LCD Display, docs/components/display/lcd_display, lcd.jpg
    MAX7219 Dot Matrix, docs/components/display/max7219digit, max7219digit.jpg
    MAX7219, docs/components/display/max7219, max7219.jpg
    Nextion, docs/components/display/nextion, nextion.jpg
    PCD8544 (Nokia 5110/ 3310), docs/components/display/pcd8544, pcd8544.jpg
    PVVX MiThermometer, docs/components/display/pvvx_mithermometer, ../components/sensor/images/xiaomi_lywsd03mmc.jpg
    Quad SPI Displays, docs/components/display/qspi_dbi, t4-s3.jpg
    RPI_DPI_RGB, docs/components/display/rpi_dpi_rgb, waveshare_touch-s3.jpg
    SSD1306, docs/components/display/ssd1306, ssd1306.jpg
    SSD1322, docs/components/display/ssd1322, ssd1322.jpg
    SSD1325, docs/components/display/ssd1325, ssd1325.jpg
    SSD1327, docs/components/display/ssd1327, ssd1327.jpg
    SSD1331, docs/components/display/ssd1331, ssd1331.jpg
    SSD1351, docs/components/display/ssd1351, ssd1351.jpg
    ST7567, docs/components/display/st7567, st7567.jpg
    ST7701S, docs/components/display/st7701s, indicator.jpg
    ST7735, docs/components/display/st7735, st7735.jpg
    ST7789V, docs/components/display/st7789v, st7789v.jpg
    ST7796, docs/components/display/ili9xxx, st7796.svg
    ST7920, docs/components/display/st7920, st7920.jpg
    TM1621, docs/components/display/tm1621, tm1621.jpg
    TM1637, docs/components/display/tm1637, tm1637.jpg
    TM1638, docs/components/display/tm1638, tm1638.jpg
    TM1651 Battery Display, docs/components/tm1651, tm1651_battery_display.jpg
    Waveshare E-Paper, docs/components/display/waveshare_epaper, waveshare_epaper.jpg
    Host SDL2 display, docs/components/display/sdl, sdl.png

Electromechanical
-----------------

.. imgtable::

    Atlas Scientific Peristaltic Pump, docs/components/ezo_pmp, ezo-pmp.jpg
    Grove TB6612FNG, docs/components/grove_tb6612fng, motor.png, dark-invert
    Matrix Keypad, docs/components/matrix_keypad, matrix_keypad.jpg
    RTTTL Buzzer, docs/components/rtttl, buzzer.jpg
    Servo, docs/components/servo, servo.svg
    Stepper, docs/components/stepper/index, stepper.svg

Energy/Solar Management
-----------------------

.. imgtable::

    PipSolar-compatible PV Inverter, docs/components/pipsolar, pipsolar.jpg
    Power Supply, docs/components/power_supply, power.svg, dark-invert
    Resol VBus, docs/components/vbus, resol_deltasol_bs_plus.jpg
    SML, docs/components/sml, sml.svg
    SUN-GTIL2 inverter, docs/components/sun_gtil2, sun_1000g2.png

Event Components
----------------

.. imgtable::

    Event Core, docs/components/event/index, folder-open.svg, dark-invert
    Template Event, docs/components/event/template, description.svg, dark-invert

Fan Components
--------------

.. imgtable::

    Fan Core, docs/components/fan/index, folder-open.svg, dark-invert
    Template Fan, docs/components/fan/template, description.svg, dark-invert
    Binary Fan, docs/components/fan/binary, fan.svg, dark-invert
    H-bridge Fan, docs/components/fan/hbridge, fan.svg, dark-invert
    Speed Fan, docs/components/fan/speed, fan.svg, dark-invert
    Tuya Fan, docs/components/fan/tuya, tuya.png

Home Assistant Components
-------------------------

Components specifically for interacting with Home Assistant.

.. imgtable::

    Binary Sensor, docs/components/binary_sensor/homeassistant, home-assistant.svg, dark-invert
    Bluetooth Proxy, docs/components/bluetooth_proxy, bluetooth.svg, dark-invert
    micro Wake Word, docs/components/micro_wake_word, voice-assistant.svg, dark-invert
    Number, docs/components/number/homeassistant, home-assistant.svg, dark-invert
    Sensor, docs/components/sensor/homeassistant, home-assistant.svg, dark-invert
    Switch, docs/components/switch/homeassistant, home-assistant.svg, dark-invert
    Text Sensor, docs/components/text_sensor/homeassistant, home-assistant.svg, dark-invert
    Voice Assistant, docs/components/voice_assistant, voice-assistant.svg, dark-invert

Light Components
----------------

.. imgtable::

    Light Core, docs/components/light/index, folder-open.svg, dark-invert
    Beken SPI, docs/components/light/beken_spi_led_strip, color_lens.svg, dark-invert
    Binary Light, docs/components/light/binary, lightbulb.svg, dark-invert
    Cold+Warm White Light, docs/components/light/cwww, brightness-medium.svg, dark-invert
    Color Temperature Light, docs/components/light/color_temperature, brightness-medium.svg, dark-invert
    ESP32 RMT, docs/components/light/esp32_rmt_led_strip, color_lens.svg, dark-invert
    FastLED Light, docs/components/light/fastled, color_lens.svg, dark-invert
    H-bridge Light, docs/components/light/hbridge, brightness-medium.svg, dark-invert
    Light Partition, docs/components/light/partition, color_lens.svg, dark-invert
    LightWaveRF, docs/components/lightwaverf, brightness-medium.svg, dark-invert
    LVGL widget, docs/components/light/lvgl, lvgl_c_lig.png
    Monochromatic Light, docs/components/light/monochromatic, brightness-medium.svg, dark-invert
    NeoPixelBus Light, docs/components/light/neopixelbus, color_lens.svg, dark-invert
    RGB Light, docs/components/light/rgb, rgb.png
    RGBCT Light, docs/components/light/rgbct, rgbw.png
    RGBW Light, docs/components/light/rgbw, rgbw.png
    RGBWW Light, docs/components/light/rgbww, rgbw.png
    RP2040 PIO, docs/components/light/rp2040_pio_led_strip, color_lens.svg, dark-invert
    Shelly Dimmer, docs/components/light/shelly_dimmer, shellydimmer2.jpg
    Sonoff D1 Dimmer, docs/components/light/sonoff_d1, sonoff_d1.jpg
    SPI LED Strips, docs/components/light/spi_led_strip, apa102.jpg
    Status Led, docs/components/light/status_led, led-on.svg, dark-invert
    Tuya Dimmer, docs/components/light/tuya, tuya.png

**Looking for WS2811 and similar individually addressable lights?** For the ESP32 and its variants, we
recommend the :doc:`components/light/esp32_rmt_led_strip` or :doc:`components/light/spi_led_strip`; for
other processors, have a look at the :doc:`FastLED Light </docs/components/light/fastled>`.

Lock Components
---------------

.. imgtable::

    Lock Core, docs/components/lock/index, folder-open.svg, dark-invert
    Template Lock, docs/components/lock/template, description.svg, dark-invert
    Generic Output Lock, docs/components/lock/output, upload.svg, dark-invert

Media Player Components
-----------------------

.. imgtable::

    Media Player Core, docs/components/media_player/index, folder-open.svg, dark-invert
    DFPlayer, docs/components/dfplayer, dfplayer.svg, dark-invert
    I2S Audio, docs/components/media_player/i2s_audio, i2s_audio.svg
    Speaker, docs/components/media_player/speaker, speaker.svg

Microphone Components
---------------------

.. imgtable::

    Microphone Core, docs/components/microphone/index, microphone.svg, dark-invert
    I2S Microphone, docs/components/microphone/i2s_audio, i2s_audio.svg

Number Components
-----------------

.. imgtable::

    Number Core, docs/components/number/index, folder-open.svg, dark-invert
    Template Number, docs/components/number/template, description.svg, dark-invert
    Home Assistant, docs/components/number/homeassistant, home-assistant.svg, dark-invert
    LVGL widget Number, docs/components/number/lvgl, lvgl_c_num.png
    Modbus Number, docs/components/number/modbus_controller, modbus.png
    Tuya Number, docs/components/number/tuya, tuya.png

Output Components
-----------------

.. imgtable::

    Output Core, docs/components/output/index, folder-open.svg, dark-invert
    Template Output, docs/components/output/template, description.svg, dark-invert
    AC Dimmer, docs/components/output/ac_dimmer, ac_dimmer.svg, dark-invert
    BLE Binary Output, docs/components/output/ble_client, bluetooth.svg, dark-invert
    BP1658CJ, docs/components/output/bp1658cj, bp1658cj.svg
    BP5758D, docs/components/output/bp5758d, bp5758d.svg
    DAC7678, docs/components/output/dac7678, dac7678.svg
    EMC2101, docs/components/emc2101, emc2101.jpg
    ESP32 DAC, docs/components/output/esp32_dac, dac.svg
    ESP32 LEDC, docs/components/output/ledc, pwm.png
    ESP8266 Software PWM, docs/components/output/esp8266_pwm, pwm.png
    GP8403, docs/components/output/gp8403, gp8403.svg
    GPIO Output, docs/components/output/gpio, gpio.svg
    LibreTiny PWM, docs/components/output/libretiny_pwm, pwm.png
    MCP4725, docs/components/output/mcp4725, mcp4725.jpg
    MCP4728, docs/components/output/mcp4728, mcp4728.jpg
    MCP47A1, docs/components/output/mcp47a1, mcp47a1.svg
    Modbus Output, docs/components/output/modbus_controller, modbus.png
    MY9231/MY9291, docs/components/output/my9231, my9231.svg
    PCA9685, docs/components/output/pca9685, pca9685.jpg
    Sigma-Delta Output, docs/components/output/sigma_delta_output, sigma-delta.svg, dark-invert
    Slow PWM, docs/components/output/slow_pwm, pwm.png
    SM16716, docs/components/output/sm16716, sm16716.svg
    SM2135, docs/components/output/sm2135, sm2135.svg
    SM2235, docs/components/output/sm2235, sm2235.svg
    SM2335, docs/components/output/sm2335, sm2335.svg
    TLC59208F, docs/components/output/tlc59208f, tlc59208f.jpg
    TLC5947, docs/components/output/tlc5947, tlc5947.jpg
    TLC5971, docs/components/output/tlc5971, tlc5971.jpg
    X9C Potentiometer, docs/components/output/x9c, x9c.jpg

Select Components
-----------------

.. imgtable::

    Select Core, docs/components/select/index, folder-open.svg, dark-invert
    Template Select, docs/components/select/template, description.svg, dark-invert
    LVGL widget Select, docs/components/select/lvgl, lvgl_c_sel.png
    Modbus Select, docs/components/select/modbus_controller, modbus.png
    Tuya Select, docs/components/select/tuya, tuya.png

Speaker Components
------------------

.. imgtable::

    Speaker Core, docs/components/speaker/index, speaker.svg, dark-invert
    I2S Speaker, docs/components/speaker/i2s_audio, i2s_audio.svg
    Mixer Speaker, docs/components/speaker/mixer, mixer.svg
    Resampler Speaker, docs/components/speaker/resampler, waveform.svg, dark-invert

Switch Components
-----------------

.. imgtable::

    Switch Core, docs/components/switch/index, folder-open.svg, dark-invert
    Template Switch, docs/components/switch/template, description.svg, dark-invert
    BLE Client Switch, docs/components/switch/ble_client, bluetooth.svg, dark-invert
    Factory Reset Switch, docs/components/switch/factory_reset, restart-alert.svg, dark-invert
    Generic Output Switch, docs/components/switch/output, upload.svg, dark-invert
    GPIO Switch, docs/components/switch/gpio, gpio.svg
    H-bridge Switch, docs/components/switch/hbridge, hbridge-relay.jpg
    LVGL Widget, docs/components/switch/lvgl, lvgl_c_swi.png
    Modbus Switch, docs/components/switch/modbus_controller, modbus.png
    Nextion Switch, docs/components/switch/nextion, nextion.jpg
    Restart Switch, docs/components/switch/restart, restart.svg, dark-invert
    Safe Mode Switch, docs/components/switch/safe_mode, restart-alert.svg, dark-invert
    Shutdown Switch, docs/components/switch/shutdown, power_settings.svg, dark-invert
    Tuya Switch, docs/components/switch/tuya, tuya.png
    UART Switch, docs/components/switch/uart, uart.svg
    Home Assistant, docs/components/switch/homeassistant, home-assistant.svg, dark-invert

Text Components
---------------

.. imgtable::

    Text Core, docs/components/text/index, folder-open.svg, dark-invert
    Template Text, docs/components/text/template, description.svg, dark-invert
    LVGL textarea Text, docs/components/text/lvgl, lvgl_c_txt.png

Text Sensor Components
----------------------

.. imgtable::

    Text Sensor Core, docs/components/text_sensor/index, folder-open.svg, dark-invert
    Template Text Sensor, docs/components/text_sensor/template, description.svg, dark-invert
    BLE Scanner, docs/components/text_sensor/ble_scanner, bluetooth.svg, dark-invert
    Ethernet Info, docs/components/text_sensor/ethernet_info, ethernet.svg, dark-invert
    Home Assistant, docs/components/text_sensor/homeassistant, home-assistant.svg, dark-invert
    LibreTiny, docs/components/text_sensor/libretiny, libretiny.svg
    LVGL textarea Text Sensor, docs/components/text_sensor/lvgl, lvgl_c_txt.png
    Modbus Text Sensor, docs/components/text_sensor/modbus_controller, modbus.png
    MQTT Subscribe Text, docs/components/text_sensor/mqtt_subscribe, mqtt.png
    Nextion Text Sensor, docs/components/text_sensor/nextion, nextion.jpg
    Tuya Text Sensor, docs/components/text_sensor/tuya, tuya.png
    Version, docs/components/text_sensor/version, new-box.svg, dark-invert
    WiFi Info, docs/components/text_sensor/wifi_info, network-wifi.svg, dark-invert
    WireGuard, docs/components/wireguard, wireguard_custom_logo.svg, dark-invert
    WL-134 Pet Tag Sensor , docs/components/text_sensor/wl_134, fingerprint.svg, dark-invert

Time Components
---------------

.. imgtable::

    Time Core, docs/components/time/index, clock-outline.svg, dark-invert
    DS1307 RTC, docs/components/time/ds1307, clock-outline.svg, dark-invert
    GPS Time, docs/components/time/gps, crosshairs-gps.svg, dark-invert
    Home Assistant Time, docs/components/time/homeassistant, home-assistant.svg, dark-invert
    PCF85063 RTC, docs/components/time/pcf85063, clock-outline.svg, dark-invert
    PCF8563 RTC, docs/components/time/pcf8563, clock-outline.svg, dark-invert
    SNTP, docs/components/time/sntp, clock-outline.svg, dark-invert

Touchscreen Components
----------------------

.. imgtable::

    Touchscreen Core, docs/components/touchscreen/index, folder-open.svg, dark-invert
    AXS15231, docs/components/touchscreen/axs15231, axs15231.svg
    CST226, docs/components/touchscreen/cst226, t4-s3.jpg
    CST816, docs/components/touchscreen/cst816, cst816.jpg
    EKTF2232, docs/components/touchscreen/ektf2232, ektf2232.svg, Inkplate 6 Plus
    FT63X6, docs/components/touchscreen/ft63x6, wt32-sc01.png
    GT911, docs/components/touchscreen/gt911, esp32_s3_box_3.png
    Lilygo T5 4.7", docs/components/touchscreen/lilygo_t5_47, lilygo_t5_47_touch.jpg
    TT21100, docs/components/touchscreen/tt21100, esp32-s3-korvo-2-lcd.png
    XPT2046, docs/components/touchscreen/xpt2046, xpt2046.jpg

Valve Components
----------------

.. imgtable::

    Valve Core, docs/components/valve/index, folder-open.svg, dark-invert
    Template Valve, docs/components/valve/template, description.svg, dark-invert

Wireless Communication
----------------------

Used for creating infrared (IR) or radio frequency (RF) remote control transmitters and/or receivers, or to connect
ESPHome to cellular networks. **Does not encompass Wi-Fi.**

.. imgtable::

    IR Remote Climate, docs/components/climate/climate_ir, air-conditioner-ir.svg, dark-invert
    Remote Receiver, docs/components/remote_receiver, remote.svg, dark-invert
    Remote Transmitter, docs/components/remote_transmitter, remote.svg, dark-invert
    RF Bridge, docs/components/rf_bridge, rf_bridge.jpg
    SIM800L, docs/components/sim800l, sim800l.jpg

Miscellaneous Components
------------------------

.. imgtable::

    ESP32 Camera, docs/components/esp32_camera, camera.svg, dark-invert
    Exposure Notifications, docs/components/exposure_notifications, exposure_notifications.png
    GPS, docs/components/gps, crosshairs-gps.svg, dark-invert
    Grow Fingerprint Reader, docs/components/fingerprint_grow, fingerprint.svg, dark-invert
    Modbus Controller, docs/components/modbus_controller, modbus.png
    Sprinkler, docs/components/sprinkler, sprinkler-variant.svg, dark-invert
    Status LED, docs/components/status_led, led-on.svg, dark-invert
    Sun, docs/components/sun, weather-sunny.svg, dark-invert
    Tuya MCU, docs/components/tuya, tuya.png

.. _cookbook:

Cookbook
--------

.. imgtable::

    Lambda Magic: Tips and Tricks, docs/cookbook/lambda_magic, head-lightbulb-outline.svg, dark-invert
    LVGL Recipes, docs/cookbook/lvgl, lvgl.png
    Garage Door Template Cover, docs/cookbook/garage-door, garage-variant.svg, dark-invert
    Time & Temperature on OLED Display, docs/cookbook/display_time_temp_oled, display_time_temp_oled_2.jpg
    ESP32 Water Leak Detector, docs/cookbook/leak-detector-m5stickC, leak-detector-m5stickC_main_index.jpg
    BME280 Environment extras, docs/cookbook/bme280_environment, bme280.jpg
    Non-Invasive Power Meter, docs/cookbook/power_meter, power_meter.jpg
    Sonoff Fishpond Pump, docs/cookbook/sonoff-fishpond-pump, cookbook-sonoff-fishpond-pump.jpg
    Arduino Port Extender, docs/cookbook/arduino_port_extender, arduino_logo.svg
    EHMTX a matrix status/text display, docs/cookbook/ehmtx, ehmtx.jpg

Contributing
------------

Do you have other awesome automations or cool setups? Please feel free to add them to the
documentation for others to copy. See :doc:`Contributing </docs/guides/contributing>`.

.. toctree::
    :hidden:

    web-api/index
    automations/index
    components/index
    cookbook/index
    guides/index
