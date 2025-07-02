# hoas
McZlik's custom Home Assistant settings and modules and stuff

Based on: https://github.com/matt8707/hass-config

## Docker HOAS
```bash
docker run -d --name homeassistant-dev --privileged --restart=unless-stopped -e TZ=Europe/Amsterdam -v /PATH/TO/CONFIG:/config -p 8123:8123 ghcr.io/home-assistant/home-assistant:stable
```