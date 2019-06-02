# ESP8266_Deepsleep_MQTT
This sketch reads the temperature from a DS18b20 and publishes it to the MQTT broker
It then deep sleeps for 900 seconds

Deep saves some power if on battery but a 500mah battery only lasts a little over 3 days, still working to see if more power can be saved or if I should try something different.  Deep sleep with RF_CAL is supposed to help but it seems broken
