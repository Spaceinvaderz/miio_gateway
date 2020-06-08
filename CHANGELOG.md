# Changelog

### v.1.4.1

* Preparing for release  

### v.1.4.0

* Reordered files structure and prepared for using in HACS store.

### v1.3.1

* Updated `alarm_control_panel` with `supported_features` to work with HA 0.103 and above.

### v1.3

* Added `restore` param to sensor mapping. Defaults to `false`, will restore pre-HA restart state if set to `true`.

### v1.2

* UDP socket gateway connection rebuilt.
* Supports re-connections now.
* Gateway after-unavailable state is now refreshed.
* Fixed wrong logging params that caused gateway to freeze, thanks @quarcko !

### v1.1

* Changed entity_id and name generation methods.
* Added support for temp/humid/pressure sensors.
* Added support for vibration sensor.
* Added `friendly_name` to sensor definition in config.yml.
* Sensor `class` can be now anything from binary_sensor (door, garage_door, window, motion, moving, opening, smoke, vibration and more).
  Keep in mind that not all Miio events are supported yet! Listed above are supported.
* Sensor `class` can be now anything from sensor (humidity, illuminance, temperature, pressure and more).
  Keep in mind that not all Miio events are supported yet! Listed above are supported.

#### Breaking changes (v1.1)
