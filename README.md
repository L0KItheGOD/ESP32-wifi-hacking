# ESP32-wifi-hacking

 An universal tool for ESP32 platform for implementing various Wi-Fi attacks.
 
 ESP32 2.4g wifi 通用安全測試工具 *(含燒錄工具)*
 
# FEATURES
。PMKID capture

。WPA/WPA2 handshake capture and parsing

。Deauthentication attacks using various methods

。Denial of Service attacks

。Formatting captured traffic into PCAP format

。Parsing captured handshakes into HCCAPX file ready to be cracked by Hashcat

。Passive handshake sniffing

。Easily extensible framework for new attacks implementations

。Management AP for easy configuration on the go using smartphone for example

。And more...

# Usage
1.Build and flash project onto ESP32 (DevKit or module)

2.Power up ESP32

3.Management AP is started automatically after boot

4.Connect to Management AP. By default: *SSID: ManagementAP* and *password: mgmtadmin*

5.Open *192.168.4.1* in you browzer.

# Credit 
The original project & documents: *https://github.com/risinek/esp32-wifi-penetration-tool#readme*
