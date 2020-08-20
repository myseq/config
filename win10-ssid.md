## Setting the priority for WiFi SSID

1. Open cmd prompt (as administrator)

2. List all the wireless networks 
>netsh wlan show profiles

3. Identify your wireless adapter/interface
> netsh wlan show interfaces

4. Setting the priority with profile and interface
> netsh wlan set profileorder name="SSID" interface="Wi-Fi" priority=1

