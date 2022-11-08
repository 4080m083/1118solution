# OSI 模型與TCP/IP protocal suite

### OSI有七層?簡述其功能

    (一)實體層 (Physical Layer) 設備裝置之間位元資料傳輸

    (二)資料鏈結層 (Data-Link Layer) 針對相同網路(LAN)的兩個裝置之間的資料傳輸

    (三)網路層 (Network Layer) 針對位於不同網路(WAN)的兩個裝置之間的資料傳輸

    (四)傳輸層 (Transport Layer) 處理流量控制和錯誤控制。

    (五)交談層 (Session Layer) 建立網絡連線、管理、及終止兩個通訊主機的對話

    (六)表現層 (Presentation Layer) 負責轉譯、加密和壓縮資料

    (七)應用層 (Application Layer) 資訊整合，提供使用者介面

    OSI其功能：開放式網路架構所制定的電腦互連標準

### 底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy
    - Hub 實體層（Physical）
    - switch 資料鏈結層 (Data-Link)
    - router 網路層 (Network)
    - L4-switch 網路層 (Network)

### TCP/IP有那些層?寫出與OSI七層模型的對應!
    TCP 傳輸層 (Transport)
    
    IP 網路層 (Network)

# 簡述底下應用層協定(英文全名與簡單功能說明):
### HTTP vs HTTPs
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

### DNS vs DNSsec
    - DNS
        - 域名系統
        - 網域名稱系統（英語：Domain Name System，縮寫：DNS）
        - 網際網路的一項服務
        - 作為將域名和IP位址相互對映的一個分散式資料庫
        - DNS使用TCP和UDP埠53
  -------------------------------------------------------------
  
    - DNSsec
        - 域名系統安全擴充
        - 域名系統安全擴充（英語：Domain Name System Security Extensions，縮寫為DNSSEC）
        - Internet工程任務組 （IETF）的對確保由域名系統 （DNS）中提供的關於網際網路協定（IP）網路使用特定類型的資訊規格套件。
        - 對DNS提供給DNS客戶端（解析器）的DNS資料來源進行認證
        - 驗證不存在性和校驗資料完整性驗證，但不提供機密性和可用性。

### telnet vs ssh
    - telnet 
        - 應用層協議
        - 使用於網際網路及區域網中
        - 使用虛擬終端機的形式
        - 提供雙向、以文字字串為主的命令列介面互動功能。
        - 屬於TCP/IP協議族的其中之一
  ------------------------------------------------------------- 
  
    - ssh
        - 安全外殼協定（Secure Shell Protocol，簡稱SSH）
        - 一種加密的網路傳輸協定
        - 可在不安全的網路中為提供安全的傳輸環境。
        - SSH通過在網路中建立安全隧道
        - 實現SSH客戶端與伺服器之間的連接 
        
### ftp vs sftp
    - ftp
        - 檔案傳輸協定(File Transfer Protocol)
        - 用戶端與伺服器之間進行檔案傳輸的應用層協定。
        - 檔案傳送 和檔案存取 之間前者由FTP提供，後者由NFS等應用系統提供
        - FTP是一個8位元的客戶端
        - 一般執行在20和21兩個埠。
        
  ------------------------------------------------------------- 
    
    - sftp
        - 安全檔案傳輸協定(Secure File Transfer Protocol)
        - 利用一組公用設施
        - 遠端電腦提供安全訪問
        - 安全的網絡的加密方法
        - 與FTP幾乎一樣的語法和功能
        
### smtp , pop3
    - smtp
        - 簡單郵遞傳送協定（英語：Simple Mail Transfer Protocol，縮寫：SMTP）
        - 簡易郵件傳輸通訊協定
        - 透過網路傳輸電子郵件的技術標準
        - 允許電腦和伺服器交換資料
        - 傳送和接收電子郵件的資訊
    
  ------------------------------------------------------------- 
  
    - pop3
        - 電子郵件之標準協定(Post Office Protocol – Version 3)
        - 是TCP/IP協定族中的一員
        - 使用客戶端遠端管理在伺服器上的電子郵件
        - 提供了SSL加密
        - POP支援離線郵件處理

### SNMP
    - 簡單網路管理協定（SNMP，Simple Network Management Protocol）
    - 網路管理系統
    - 被管理的裝置
    - 代理者（agent）的軟體元件
    - 有一或多個系統在管理它們

# 簡述底下傳輸層協定(英文全名與簡單功能說明):

### TCP vs UDP
    -TCP
        - 傳輸控制協定（英語：Transmission Control Protocol，縮寫：TCP）
        - 連接導向的、可靠的、基於位元組流的傳輸層通信協定
        - 屬『端點對端點』(End-to-End)
        - 在簡化的電腦網路OSI模型中
        - 完成第四層傳輸層所指定的功能
 ------------------------------------------------------------- 
  
    -UDP
        - 使用者資料包協定（英語：User Datagram Protocol，縮寫：UDP)
        - 簡單的面向資料包的通信協定
        - 位於OSI模型的傳輸層
        - 效率為主要訴求
        - 缺乏可靠性且屬於無連接協定
        
### reliable(可靠的) vs unreliable(不可靠的)
    -reliable
        - 可靠通信協定 (reliable protocol)
        - 是屬於『同步傳輸』的協定
        - 雙向資料傳輸協定
        - 不會因其他因素而造成封包遺失
        - 複雜的傳輸協定
------------------------------------------------------------- 
          
    -unreliable
        - 不可靠通訊協定 (unreliable protocol)。
        - 不可靠的無連接數據報協議
        - 不能保證數據的可靠傳輸
        - 開銷低
        - 傳輸速度快，容易擴展
      

### TCP three-way handshaking(三項交握)
    - 建立虛擬連線 (virtual connection) 
    - 三次訊息的交換
    - 於TCP是一個連線導向( connection oriented )的傳輸協定
    - 就是透過主動要求連線的『客戶端』，與被動要求連線的『伺服端』
    - 經過三次封包交換達成連線協議

### TCP syn flood attack
    - SYN flood或稱SYN洪水、SYN洪泛
    - 一種阻斷服務攻擊
    - 於攻擊者傳送一系列的SYN請求到目標系統。
    - 使用者端透過傳送SYN同步（synchronize）
    - 資訊到伺服器要求建立連線。 
  
# 簡述底下網路層協定(英文全名與簡單功能說明):

### IP
    - IP位址（英語：IP Address，全稱Internet Protocol Address）
    - 網際協定位址、網際網路協定位址。
    - 於標識傳送或接收資料報的裝置的一串數字。
    - 通過IP位址，裝置間可以互相通訊
    - 標識裝置或網路和定址

### ICMP
    - 網際網路控制訊息協定（英語：Internet Control Message Protocol，縮寫：ICMP）
    - 網際網路協定套組的核心協定之一。
    - 於網際網路協定（IP）中傳送控制訊息
    - 在通訊環境中的各種問題回饋。
    - 使管理者可以對問題作出診斷，然後採取適當的措施解決。
    
    
