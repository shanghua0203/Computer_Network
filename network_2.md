Ethernet 乙太網路
===
### 沿革
- 第一個乙太網路系統  
  1.1973年發展  
  2.傳輸數度2.94Mbps
- 1980年9月  
  1.Dgital、Intel、Xerox三間公司：10Mbps
  >使乙太網路相容於不同電腦系統中  
  
  2.稱為DIX(Dgital-Intel-Xerox)乙太網路  
    
- 1982年 Xerox放棄商標
- 1995年 IEEE802.3u
- 1998年 IEEE802.3z
- 2003年 IEEE802.3ae
- 2006年 10GBaseT標準規格 IEEE802.3an
  >T為雙絞線的意思
- 2010年 40Gpbs、100Gbps IEEE802.3ba

### 架構
#### 樹狀架構

### 無線網路分類
  1. 無線廣域網路 WWAN;Wireless Wide Area Network  
  >LoRaWAN、智慧城市、智慧農場
  2. 無線區域網路 WLAN
  >校園網路、社區網路，**光罩上網技術(Li-Fi)**
  3. 無線個人網路 WPAN
  >智慧家居


### 各種無線網路
   - LoRa  
     低功號、低速率  
     傳輸速率:0.3~27Kbps  
     傳輸距離:大於10KM

   - 802.11(WiFi)  
     1. ![802.11](image\802.11.png)
     2. MIMO 802.11n、802.11ac、802.11ax  
     多天線，多重輸入輸出
   - Bluetooth  
     802.15.1
   - ZigBee  
     802.15.4
      

## 無線區域網路架設

  ### 傳送距離&資訊安全
  - 空曠場所可達100M~150M
  - 半開放有隔間
  - 安全機制  
    1. WEP
    2. WPA
    3. WPA2
    4. WPA3
    
  ### 無線網路架構
   1. Ad Hoc  
     對等式(Peer-to-Peer)
   2. Infrastructure  
     主從式(Master/Slave)

   - Ad Hoc  
    不需要存取點(AP:Access Point)設備  
    不同SSID電腦不能互傳  
    IBSS


   - Infrastructure  
     AP節點的中繼中心  
     以SSID對網路進行辨識  
     節點傳至AP，AP再傳給目的節點

   - 中繼模式(Repeater Mode)  
     ![repeater](image\repeater.png)
   - 解決距離問題
   - 速度剩一半

   - 無線網路漫遊
     ![Wireless_network_roaming](image\Wireless_network_roaming.png)

   - 橋接模式(Bredge Mode)  
     ![]()
