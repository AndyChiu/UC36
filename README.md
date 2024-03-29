UC36系列鍵盤-3D列印檔案
=====================

這裡放置了此系列的3D列印檔，因為均使用36鍵，且為手拉線方式處理，所以韌體(RP2040)都可以共用。

預設使用duplex matrix的接線方式，所以一條線可以拉兩條Column，這個部分需要注意。

MCU的部分，建議使用RP2040晶片的MCU。

鍵盤清單(依照開發順序排列):
-------------------------

* [W36](/W36/)
  
  首次嘗試將按鍵減少到36鍵，使用[Willow配列](https://github.com/hanachi-ap/willow64-doc)方式，正式的學習36鍵的鍵盤操作。此為16mm窄間距配置。

  ![36鍵的小Willow鍵盤](https://pbs.twimg.com/media/FsMhAn-WIAIp3Ih?format=jpg&name=360x360)
  
  詳細介紹：[小Willow鍵盤](https://ie321mx.blogspot.com/2023/04/36willow.html)

* [ESR36](/ESR36/)

  嘗試將[Esrille NISSE鍵盤](https://www.esrille.com/keyboard/layouts.en-us.html)的layout拿來測試，發現打起來也沒有太多不適，拇指更外擴，比較符合我的拇指位置。此為16mm窄間距配置。
  
  ![小Esrille NISSE鍵盤](https://pbs.twimg.com/media/Ft5FvEGXwAABVpD?format=jpg&name=360x360)

  詳細介紹：[小Esrille NISSE鍵盤](https://ie321mx.blogspot.com/2023/04/36esrille-nisse.html)

* [Barlette36](/Barlette36/)

  小可愛36鍵盤(Barlette36)之前，還有一系列的UC36鍵盤列印測試，主要是從Esrille NISSE鍵盤改成[立體形狀的Esrille NISSE鍵盤](https://ie321mx.blogspot.com/2023/05/36esrille-nisse-layout.html)，因為使用弧形設計，有許多的變數，經過反覆的測試後，最後定案使用這個弧度，也另外將這鍵盤命名為小可愛36鍵盤(Barlette36)，因為它使用窄間距，十分小巧可愛，因此命名。
  
  ![小可愛36鍵盤(Barlette36)](https://pbs.twimg.com/media/FwkrZbdXwAE78go?format=jpg&name=360x360)

  詳細介紹：[小可愛36鍵盤](https://ie321mx.blogspot.com/2023/05/36bralette36.html)

* [UC36Wing](/UC36Wing/)

  由於Barlette36的設計，還是以少見的窄間距作為設計方針，後來為了嘗試使用一般間距，用來搭配市售的鍵帽大小，又設計了另一把鍵盤，並嘗試將M字板改成L字版，調整手指張開角度與鍵帽水平角度，另外小指處的高度也進行了調整。此為一般間距配置。
  
  ![UC36 Wing鍵盤](https://pbs.twimg.com/media/F8YHPkmaYAA_WtL?format=jpg&name=360x360)

  詳細介紹：[UC36 Wing鍵盤](https://ie321mx.blogspot.com/2023/10/36luc36-wing.html)

* [W36A](/W36A/)

  此為W36的變體，將鍵盤由分離式改成單一鍵盤，最早設計好後，由於3D列印機沒辦法印太大的檔案，所以就沒印出來測試，後來送至[JLCPCB的3D列印服務](https://jlcpcb.com/?from=AndyChiu)進行列印，順便測試了他們的透明材質，視覺衝擊蠻強烈的。
  
  ![非分離式的W36A鍵盤](https://pbs.twimg.com/media/GAJpOeQacAAkW1l?format=jpg&name=360x360)
  
  詳細介紹：[非分離式的W36A鍵盤](https://ie321mx.blogspot.com/2024/01/uc36a.html)

其他零件：
---------

* [IDC](/IDC/) IDC接頭與基座模型檔
* [MCU](/MCU/) MCU的基座模型檔

韌體檔案：
---------

* [UF2](/UF2/) 鍵盤的韌體檔案，目前僅建立適用於RP2040的MCU

