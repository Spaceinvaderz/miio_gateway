# Miio Gateway

## What for?

In general, it allows (modified) devices like `lumi.gateway.mieu01` to be controlled via LAN **instead of Xiaomi Cloud**.

Once you replace original `miio_client` with modified one – you won't be able to control gateway via Mi Home app.
But... why you would? ;)

Please check the repository for [the repository](https://github.com/Spaceinvaderz/miio_gateway/blob/master/README.md) and usage instructions.

## What is supported

* Built-in LED as `light.miio_gateway` component.
  > With brightness and colors.
* The built-in speaker and sounds library as `media_player.miio_gateway` component.
  > With play, stop, mute, set_volume and play_media with ringtone ID as media ID.
* Built-in luminescence sensor (yes, there's one) as `sensor.miio_gateway_illuminance` component.
  > Sensor shows readings in lumens.
* Built-in alarm functionality as `alarm_control_panel.miio_gateway` component.
  > Arm, disarm; night/home/away modes supported via alarm volumes: 5/15/70.

* Child sensors as `binary_sensor`.
  > Currently, supported are:
  > * motion sensors,
  > * door/window sensors,
  > * leak sensors,
  > * smoke sensors,
  > * buttons.

* Child sensors as `sensor`.
  > Currently, supported are:
  > * temperature sensors,
  > * humidity sensors,
  > * pressure sensors.

## Not supported yet

Not supported but **likely to work** with:

* Occupancy detectors.
* Plug switches.
* Locks.
* Smart Cubes.
* Remotes(?).
* Relays(?).
* Curtains(?).
