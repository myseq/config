## Review the Wi-Fi SSID password

1. Open cmd prompt (as administrator)

2. List all the wireless networks 
> netsh wlan show profiles

3. Show the key content in clear
> netsh wlan show profile <ssid> key=clear


