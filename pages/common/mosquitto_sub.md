# mosquitto_sub

> Subscribe to MQTT topics.

- Subscribe to a topic:

`mosquitto_sub -h {{broker.example.com}} -t {{topic}}`

- Subscribe to a topic with authentication:

`mosquitto_sub -h {{broker.example.com}} -t {{topic}} -u {{username}} -P {{password}}

- Subscribe to a topic with a quality of service level:

`mosquitto_sub -h {{broker.example.com}} -t {{topic}} -q 1`

- Use a specific version of the MQTT protocol:

`mosquitto_sub -h {{broker.example.com}} -t {{topic}} -V mqttv311`
