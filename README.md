# linkIt7697-env-setup
## LinkIt7697 
### 簡介
* 聯發科技於2017 年最新推出的「物聯網開發板」

* LinkIt 7697使用 MT7697 作為主控制器，該晶片核心為主流的 ARM Cortex-M4（含浮點運算器），運行時脈為192MHz

* 提供 Wi-Fi 和 BLE（低功耗藍芽）兩種通訊最主要的通訊功能

* 軟體部分採用最為廣泛地FreeRTOS為作業系統，同時也提供 Arduino 開發環境，為目前學習開發物聯網應用的最佳開發平台之一。

![圖片1](https://user-images.githubusercontent.com/93152909/139596386-a1f0e823-c49a-4468-a05f-5ca9de69c509.png)
### 優點
* 使用Arduino開發環境

* 內建 Wi-Fi / BLE，並包裝成好用的函式庫，能輕鬆連結雲端和手機

* 足夠的內存（352K RAM /4MB Flash），可運行更複雜的應用

* 官網內容相當豐富，聯發科技的工程師也會在粉絲頁提供技術問題解答
### 開發環境
LinkIt 7697針對不同族群的開發者，提供了三種開發環境：
* Arduino IDE：  
 提供給Maker/教育教學者的開發環境，完全相容於Arduino的程式語法，並包含LinkIt 7697獨家功能，例如LWIFI、LBLE、MCS（MediaTek Cloud Sandbox）、LFlash、LRTC及LRemote 等好用函式庫，大幅降低各種物聯網應用的開發門檻。
 
* BlocklyDuino :  
 提供物聯網入門開發者的視覺化積木開發環境，透過簡單的積木拖拉就可組合出各種邏輯應用。BlocklyDuino 會將積木轉換成 Arduino 程式，也可作為從視覺化積木轉換至Arduino程式語言的學習工具。

* LinkIt SDK :  
 提供給專業物聯網產品開發者的開發除錯環境，直接使用SDK進行開發，擁有最佳開發彈性且能優化出最佳效能。

#### 環境比較圖
||![image](https://user-images.githubusercontent.com/93152909/139596556-0bea2495-7e45-448b-97c3-e342814dd6a6.png) |![image](https://user-images.githubusercontent.com/93152909/139596570-1eba3fab-5ccf-4cee-94f2-00f2624b40ce.png)|![image](https://user-images.githubusercontent.com/93152909/139596590-72550c4b-95d4-4dc0-af7a-a66ad5066b80.png)|
|:-----:|:-----:|:-----:|:-----:|
|名稱|Arduino IDE|Blocklyduino|LinkIt SDK|
|對象|Maker/教育工作者|教育工作者|專業開發者|
|工具|文字式|圖像式|文字式|
|特性|豐富的軟硬周邊資源<br>封裝過好用的函式庫|簡易使用|最高彈性<br>最高效能<br>開發複雜度較高|
### 參考網址
* https://blog.cavedu.com/2018/06/11/linkit-7697
* https://reurl.cc/WXbxeZ
## Arduino 、 Arduino IDE 與 Arduino程式 簡介
![image](https://user-images.githubusercontent.com/93152909/139592666-c06a4e90-9b37-440f-88d6-b1de15fd1d0e.png)
### Arduino
* 提供開源硬體和開源軟體的公司，兼有專案和使用者社群

* 同時也是一個開源嵌入式硬體平台，供使用者製作可互動式的嵌入式專案
### Arduino IDE ( 1.x )
* 一個跨平台的Integrated Development Environment應用程式

* 用於撰寫Arduino程式，並提供了一個程式「avrdude」用來轉換可執行檔成為能夠燒寫入Arduino硬體的韌體

* 使用Arduino Software IDE編寫的程式被稱為「sketch」

### Arduino程式
* 是否視為一種程式語言尚有爭議，但IEEE 2021前十大嵌入式程式語言中，Arduino 算是一個語言
![tempsnip](https://user-images.githubusercontent.com/93152909/139594674-11fa2312-83e6-4be0-83bd-0663dcd7d71a.png)

* 一種 “類C語言“，使用與C語言和C++相仿的語法
 
* 一個典型的Arduino 程式會包含兩個函式，它們會在編譯後合成為main()函式：

  * setup()：在程式執行開始時會執行一次，用於初始化設定
  
  * loop()：直到Arduino硬體關閉前會重複執行函式放的程式碼

### 
