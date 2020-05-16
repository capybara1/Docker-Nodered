# Node-RED for Docker

This is basically a [Dockerfile](./Dockerfile) containing customization of the vanilla [Node-RED image](https://hub.docker.com/r/nodered/node-red).

The customization includes:

- Preinstalled [passport module for authentication via Keycloak](https://github.com/exlinc/keycloak-passport)
- Preinstalled [Node-RED module for interaction with Home Assistant](https://github.com/zachowj/node-red-contrib-home-assistant-websocket)
