# OSI 模型與TCP/IP protocal suite

## OSI有七層?簡述其功能

(一)實體層 (Physical Layer) 定義設備裝置之間位元資料傳輸

(二)資料鏈結層 (Data-Link Layer) 針對相同網路(LAN)的兩個裝置之間的資料傳輸

(三)網路層 (Network Layer) 針對位於不同網路(WAN)的兩個裝置之間的資料傳輸

(四)傳輸層 (Transport Layer) 負責處理流量控制和錯誤控制。

(五)交談層 (Session Layer) 負責建立網絡連線、管理、及終止兩個通訊主機的對話

(六)表現層 (Presentation Layer) 負責轉譯、加密和壓縮資料

(七)應用層 (Application Layer) 資訊整合，提供使用者介面

OSI其功能：開放式網路架構所制定的電腦互連標準

## 底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy
    - Hub 實體層（Physical）
    - switch 資料鏈結層 (Data-Link)
    - router 網路層 (Network)
    - L4-switch 網路層 (Network)

## TCP/IP有那些層?寫出與OSI七層模型的對應!
TCP 傳輸層 (Transport)
IP 網路層 (Network)

# 簡述底下應用層協定(英文全名與簡單功能說明):
## HTTP vs HTTPs
     - HTTP：
    - 超文本傳輸協定（英語：HyperText Transfer Protocol，縮寫：HTTP）
    - 分佈式、協作式和超媒體訊息系統的應用層協定
    - 全球資訊網的數據通信的基礎
    - 客戶端（使用者）和伺服器端（網站）之間請求和應答的標準
    - 由提姆·柏內茲-李於1989年在歐洲核子研究組織（CERN）所發起
   -------------------------------------------------------------
   
    - HTTPs：
    - 超文本傳輸安全協定（英語：HyperText Transfer Protocol Secure，縮寫：HTTPS)
    - 常稱為HTTP over TLS、HTTP over SSL或HTTP Secure
    - 是一種透過計算機網路進行安全通訊的傳輸協定。
    - HTTPS經由HTTP進行通訊，利用SSL/TLS來加密封包
    - 對網站伺服器的身分認證，保護交換資料的隱私與完整性。

## DNS vs DNSsec
    -DNS
        -域名系統
        -網域名稱系統（英語：Domain Name System，縮寫：DNS）
        -網際網路的一項服務
        -作為將域名和IP位址相互對映的一個分散式資料庫
        -使人更方便地存取網際網路
        -DNS使用TCP和UDP埠53
  -------------------------------------------------------------
  

## telnet vs ssh

## ftp vs sftp

## smtp, pop3

## SNMP

## 簡述底下傳輸層協定(英文全名與簡單功能說明):

## TCP vs UDP

## reliable(可靠的) vs unreliable(不可靠的)

## TCP three-way handshaking(三項交握)


## TCP syn flood attack

## 簡述底下網路層協定(英文全名與簡單功能說明):

## IP

## ICMP
