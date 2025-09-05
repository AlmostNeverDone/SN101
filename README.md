# Exploring Cryptographic Tools with OpenSSL
使用 OpenSSL 探索加密工具

---------

<h2>Outline 簡介</h2>

This project demonstrates the practical use of the OpenSSL toolkit for cryptographic operations. Include checking OpenSSL configuration, exploring supported algorithms, generating random keys, and writing a simple Bash script for automation.

此專題演示了 OpenSSL 工具包在加密操作中的實際應用。包括檢查 OpenSSL 配置、探索支援的演算法、產生隨機金鑰以及編寫簡單的 Bash 腳本以實現自動化操作。

---------
<h2>Objectives 目標</h2>

* Verify installation and environment.<br/>
  (確認安裝環境與 OpenSSL 版本)</b>
  <br/>

* Explore supported algorithms.<br/>
  (探索 OpenSSL 支援的演算法)</b>
  <br/>

* Generate secure random keys.<br/>
  (產生具隨機性的加密金鑰)</b>
  <br/>

* Automate tasks using Bash scripting.<br/>
  (利用 Bash 腳本自動化隨機數產生流程)</b>
  <br/>

* Build hands-on cryptographic understanding.<br/>
  (建立加密作業的實務理解，並為進一步資訊安全研究奠定基礎)</b>
  <br/>

---------

<h2>Tools and Concepts Covered 涵蓋工具與概念</h2>

<div align="center">
</p>

| Aspect <br/>(面向) | Learning content and purpose <br/>(學習內容與目的) |
| ----------------- | ----------------------------------------------- |
| Cryptographic toolkit <br/>(加密工具) | Learn the usage of OpenSSL for cryptographic operations. <br/>(學習使用 OpenSSL 進行加密作業) |
| Algorithm exploration <br/>(演算法探索) | Explore digest and cipher algorithms supported by OpenSSL. <br/>(探索 OpenSSL 支援的雜湊與加密演算法) |
| Random key generation <br/>(隨機金鑰生成) | Generate and view cryptographic random numbers using OpenSSL. <br/>(透過 OpenSSL 產生與檢視隨機金鑰) |
| Automation with scripting <br/>(腳本自動化) | Write a Bash script to automate random number generation. <br/>(撰寫 Bash 腳本以自動化產生亂數金鑰) |
</div>
<br/>

---------


<h2>Materials and Methods 材料與方法</h2>

[Environment]
* Oracle VM VirtualBox (VirtualBox 虛擬機)</b>
* Kali Linux OS (Kali Linux 作業系統)</b>

[Tasks]
* Check OpenSSL Version (檢查 OpenSSL 版本)</b>
* Explore Supported Commands and Algorithms (探索支援的指令與演算法)</b>
* Generate Random Numbers (產生隨機數字)</b>
* Automate with Bash Script (使用 Bash 腳本自動化)</b>

---------

<h2>Practice 實踐</h2>

<p align="center">
<b>Task 1: Install Snort 3<br/>(安裝 Snort 3)</b><br/>
<img src="https://i.imgur.com/AcDYaXN.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 2: Verify Snort Installation<br/>(確認安裝)</b><br/>
<img src="https://i.imgur.com/wZEG9at.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 3: Create a Custom Rule File<br/>(建立自訂規則檔)</b><br/>
<img src="https://i.imgur.com/gYm5K22.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 4: Configure snort.lua<br/>(設定 snort.lua)</b><br/>
<img src="https://i.imgur.com/nxOOOIs.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 5: Run Snort with Configuration<br/>(執行 Snort)</b><br/>
<img src="https://i.imgur.com/nXQoLa0.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 6: Test the Rule<br/>(測試規則)</b><br/>
<img src="https://i.imgur.com/WCj2tLW.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

---------

<h2>Results 成果展示</h2>

* Successfully installed and verified Snort 3 on Kali Linux.<br/>
  (成功在 Kali Linux 上安裝並驗證 Snort 3)

* Configured custom ICMP detection rules in icmp.rules and integrated them into snort.lua.<br/>
  (在 icmp.rules 中設定 自訂 ICMP 偵測規則，並整合至 snort.lua)
  
* Executed Snort with console output and confirmed real-time alerts triggered by ICMP packets (ping).<br/>
  (使用終端機輸出模式執行 Snort，並確認 即時警示 在 ICMP 封包   (ping) 時觸發)
  
* Demonstrated understanding of Snort 3 rule structure and differences from Snort 2 configuration.<br/>
  (展示對 Snort 3 規則結構及其與 Snort 2 組態差異的理解)


---------

<h2>Reference 參考</h2>

[UniSQ] [CSC8520 - Securing Networks](https://handbook-guide.unisq.edu.au/course/2025/CSC8520)
<br/>
