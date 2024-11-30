# Home Assistant
Set up [govee2mqtt](https://github.com/wez/govee2mqtt/blob/main/docs/DOCKER.md) in Home Assistant.
Remember that the MQTT broker is running under server.local, not localhost, since the container is not running in the host network.

Docker Desktop is the enemy, and you'll probably need Docker CE to map /dev devices into the container.
