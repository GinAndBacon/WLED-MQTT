# WLED-MQTT
Using WLED via MQTT in Home Assistant (useful to sync multiple strips) 

1 - WLED needs to be configured to connect to your MQTT broker (mosquito or EMQX) under Config>Sync Settings via the wled web interface 
2 - The device will not show up inder MQTT since Discovery was disabled but will show up in development tools. it shows up under rhe light domain
