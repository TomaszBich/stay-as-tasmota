# stay-as-tasmota
Fix the issue with unavailable devices after HA reboot. Tested on Tasmota 10.0.0

ALl the steps you are doing on your own risk

I have seen that many of users have an issue with Tasmota HA integration. 

The issue is that even setoption19 0 has been executed in Tasomta console the devices back to MQTT integration after HA reboot.

All you need to do:

1. Go to configuration --> Restore Configuration --> Browse the config file from my repository ( https://github.com/TomaszBich/stay-as-tasmota/raw/main/Config_26102021_10.0.0.dmp ) --> Start Restore 

![obraz](https://user-images.githubusercontent.com/74622130/138905107-8df8992a-8e86-4b3e-b431-4c24fd42b9da.png)
