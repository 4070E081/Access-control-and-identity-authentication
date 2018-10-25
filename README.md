# Access-control-and-identity-authentication
## 存取控制的基本需求
```
安全性:組織政策要確保只有得到授權的人可以讀取機密的資訊；只有得到授權的人可以修改資料或程式；並確保使用者不會輕易的造成系統無法運作。

可用性:存取控制的機制應讓使用者易於瞭解，並且儘量不影響他們的正常工作方式與習慣。存取控制的機制要能夠每次都如預期的運作。

擴展性:當一個組織的人員、系統或工作量增加時，存取控制的機制不應隨之變為過度複雜，以致影響系統效能與行政效率。
```
## 存取控制的主要概念
```
責任分擔 (separation of duties):應該避免讓一個人完整的知道或持有一個秘密的資訊或流程。

最低權限 (least privilege):每人只擁有足以完成工作的最低權限。

知的必要性 (need-to-know):每人對秘密資訊「知的權利」端視其所負責業務的需要性。

資訊分類 (information classification):使用者(人)與被使用者(系統或資料)間應有清楚的權限對應關係。
```
## 存取控制的類別
```
預防性:

偵測性:

指導性:

嚇阻性:

復原性:
```
## 存取控制的威脅
```
拒絕服務 (denial of service)
緩衝區溢位 (buffer overflow)
惡意程式 (malware)
密碼破解 (password cracker)
欺騙 (spoofing)
中間監看 (sniffer)
垃圾搜尋 (dumpster diving)
窺視 (shoulder surfing)
未經授權之資料探勘 (unauthorized data mining)
電子訊號外洩 (emanation)
物件重用 (object reuse)
資料剩磁 (data remanence)
```
## 實體與虛擬的威脅
```
偷竊:偷竊是存取控制的最大威脅。
入侵:入侵可能是實體或虛擬的，也可能兩者結合。	
社交工程:社交工程也常結合實體與虛擬的詐欺。
```
## 系統存取控制
```
身分:讓使用者擁有一個唯一、可電子讀取的名稱，電腦系統以此識別使用者身分。
身分認證:確認使用該電子身分者為使用者本人。
授權:系統通過身分認證後，授予使用者的讀、寫、執行、刪除等權限。
責任歸屬:能讓已經授權的使用者對自己在系統上的行為負責。
```
## 身份
```
電子世界中「身分」的類型：
使用者名稱 (username)，
各種電子識別證、智慧卡、提款卡等，
銀行的帳戶號碼 (account number) 等，
將在後面細談的生物特徵 (biometrics) 也是一種電子身分。
身分應有以下特性：
在一個存取控制系統中，每位使用者的身分應為唯一。有助於身分認證的進行與責任歸屬的釐清。
身分資料應保持最新，離職員工或已不使用的身分應立刻刪除。
機構內應有選定使用者名稱的政策，以免重複使用或在名稱上洩漏太多訊息。
```
## 資料存取控制
```
強制存取控制 (mandatory access control, MAC)
任意存取控制 (discretionary access control, DAC)
存取控制目錄 (access control list, ACL)
規則基準存取控制 (rule-based access control)
角色基準存取控制 (role-based access control)
```
