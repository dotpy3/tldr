# mosquitto_pub

> Publish to MQTT topics.

- Publish to a topic:

`mosquitto_pub -h {{broker.example.com}} -t {{topic}} -m {{message}}`

- Publish to a topic with authentication:

`mosquitto_pub -h {{broker.example.com}} -t {{topic}} -u {{username}} -P {{password}} -m {{message}}`

- Use a specific version of the MQTT protocol:

`mosquitto_pub -h {{broker.example.com}} -t {{topic}} -V mqttv311`
