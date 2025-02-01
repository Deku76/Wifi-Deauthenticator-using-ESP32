# Wifi-Deauthenticator-using-ESP32

# How it Works
Deauthentication Frame: The code constructs a deauthentication frame (type 0xC0) with the target AP and station MAC addresses.

Promiscuous Mode: The ESP32 is initialized in promiscuous mode to send raw 802.11 frames.

Sending Frames: The esp_wifi_80211_tx() function sends the deauthentication frame repeatedly.

# Requirements
ESP32 Board: Ensure you have an ESP32 board (e.g., ESP32 DevKit).

Arduino IDE: Install the ESP32 board support in the Arduino IDE.

Wi-Fi Library: The code uses the ESP32's built-in Wi-Fi library.

#Things to keep in mind while using it 
Legality: Unauthorized use of this code is illegal and unethical. Only use it on networks you own or have explicit permission to test.

Ethics: Always follow ethical guidelines when working with networking tools.

Detection: Deauthentication attacks are easily detectable by modern Wi-Fi equipment and security systems
