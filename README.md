# ESP32-wifi-hacking

 An universal tool for ESP32 platform to preform various kinds of Wi-Fi attacks.
 
 ESP32 2.4g 802.11 wifi 通用安全測試工具 *(含燒錄工具)* 。
 
 這是一個基於 ESP32 微控制器的 WiFi 渗透工具，它提供了多種攻擊和測試 WiFi 網絡的方法。
 
 ![EZ_7tplXgAAcXl0](https://user-images.githubusercontent.com/86963505/236613044-1c9fd8f4-cfc7-4aa5-8569-d83dbebbdef3.jpg)

 
# FEATURES

。PMKID capture / PMKID 捕獲

。WPA/WPA2 handshake capture and parsing / 捕獲和解析 WPA/WPA2 握手

。Deauthentication attacks using various methods / 使用多種方法進行去認證攻擊

。Denial of Service attacks / 阻斷服務攻擊

。Formatting captured traffic into PCAP format / 將捕獲的流量格式化為 PCAP 格式

。Parsing captured handshakes into HCCAPX file ready to be cracked by Hashcat / 將捕獲的握手解析為 HCCAPX 文件，以便 Hashcat 破解

。Passive handshake sniffing / 被動式握手嗅探

。Easily extensible framework for new attacks implementations / 易於擴展的框架，用於實現新的攻擊方法

。Easy-to-use for portable devices like smartphones / 易於使用，適用於智能手機等便攜式設備

。And more...

# Usage

1. Download and open up the flash project. Type in the COM port that your ESP32 is currently connected to.

2. Power up your ESP32.

3. Connect to the access point under the name *Management AP* (will start automatically after boot) using any device of your choice.

4. Login *password: mgmtadmin*

5. Open up *192.168.4.1* in you browser to access the control panel .

# Contributing

。Feel free to contribute. Don't hesitate to create a pull request or to submit an issue if you stumble upon any problems.

。如果您想要貢獻或改進此工具，歡迎創建一個 pull request 或者提交問題報告。

# Disclaimer

。This project demonstrates vulnerabilities of Wi-Fi networks and its underlaying 802.11 standard and how ESP32 platform can be utilised to attack on those vulnerable 
spots. Use responsibly against networks you have permission to attack on. ONLY FOR EDUCATIONAL PURPOSES!

。此工具僅用於安全測試和教育目的，請勿用於非法用途

。在使用此工具時，請確保符合當地的法律和法規

。作者不對使用此工具產生的任何後果負責

![1673192238675](https://user-images.githubusercontent.com/86963505/236613184-81d32dea-12b2-4a1a-a24c-0ec238bf196d.jpg)

# License

本工具遵循 MIT 授權協議，請查閱 LICENSE 文件獲取更多詳細信息。
