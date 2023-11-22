# Hassio

## Sänd MQTT från knapp i Lovelace

```console
show_name: true
show_icon: true
type: button
tap_action:
  action: call-service
  service: mqtt.publish
  service_data:
    topic: cmnd/b9/test/pool/ledpower
    payload: TOGGLE
name: cmnd/b9/test/pool
show_state: true
icon: mdi:led-outline
icon_height: 50px
```

