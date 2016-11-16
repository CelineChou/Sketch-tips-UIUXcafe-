##Sketch 實作內容

###工具列 Toolbar

最一開始有幾個小建議，第一是不要將Sketch調到全螢幕，因為Sketch會很常用到最上面的工具列，如果將螢幕放到最大的話，Mac會把最上方的工具列隱藏起來，這樣要找東西的時候會稍微慢一點。

接下來再打開Sketch的時候，Sketch也有自己的 Toolbar，請在那邊點一下右鍵，選擇 `Customize Toolbar`

![Alt text](/SketchPracticepics/toolbar.png)

通常建議先加入 `Rotate Copies`和 `Make Grid`，因為以後會很常用到，如果個人使用習慣什麼的話以後都可以再自己加

![Alt text](/SketchPracticepics/toolbar-1.png)



###畫布 Artboard

一切設定好之後，我們可以開啟Sketch的畫布，點選左上角 `Insert` 可以找到 `Artboard`，建議大家以快捷鍵 `A`操做。
點開後我們可以看到右側就會出現一大堆目前作業系統的各種尺寸，這邊建議可以選跟你現在手邊的device相同的畫布即可（課堂以iPhone6示範，筆者個人以SE操作）



###畫布尺寸

尺寸是一個說來話長的故事，主要是因為iPhone從4到5的過程中螢幕尺寸的改變，為了使螢幕尺寸可以符合各種大小的螢幕，蘋果發明了 `point`這個概念，詳細的資料可以參考這個網站：[https://www.paintcodeapp.com/news/ultimate-guide-to-iphone-resolutions](https://www.paintcodeapp.com/news/ultimate-guide-to-iphone-resolutions)

Dix在課堂上主要是建議大家可以將畫布的尺寸調成兩倍，一是因為這樣在畫線（divider）的時候，就不需要再手動將0.5px調成1px，二不建議調成三倍大小的原因是因為調成三倍的時候其實尺寸已經和平板很接近了，容易搞混現在到底是在畫平板還是手機。



###圖層命名

圖層命名是一個好的設計稿的最最最基本功，圖層命名得好，除了編輯方便，和工程師溝通的時候也可以大大降低成本，這邊 Dix有個小建議：可以試著用工程師習慣的用法來稱呼這個圖層，簡單來說就是學工程師命名就對了，例如一個個的橫向欄位通常叫`Cell`，而一整個頁面通常叫`Table View`，分隔線（Divider）通常叫`div`。

關於圖層命名的方式，網路文章其實很多，這邊就不再贅述。



###Symbol

Sketch的核心就是 Symbol !!!!!!!

Symbol其實可以把它想成模組化的東西，一個介面只要有任何可能重複的元素，其實就可以做成 Symbol，包含文字也可以做成 Symbol。
只要好好設計，幾乎頁面上全部的東西都可以變成Symbol。

建立 Symbol很簡單，只要把你想要的元素選起來，點擊左上角的`Create Symbol`![Alt text](/SketchPracticepics/createsymbol.png)後，就會看到`Page`多了一頁放置Symbol。

點進去 Symbol的那個頁面就可以直接在這裡編輯Symbol囉。

![Alt text](/SketchPracticepics/symbolpage.png)


重點來了，Symbol的好處到底在哪？

Symbol的這個頁面裡，只要裡編輯這裡的Symbol，你的設計稿上的所有元件都會一起更動。例如：客戶有可能常常更改你的設計稿，可能字型不對、顏色想要微調、位置更動等等，以前沒有 Symbol的時候只要一更動就是悲劇，但是現在有了 Symbol的輔助，管客戶怎麼修改，設計師都可以在最短的時間內搞定，把寶貴的時間拿來想更重要的設計，完全是設計師的福音！

再舉個例子，我們可以一開始在設計稿上「無腦地」拉出一個我們想要的元件，「無腦地」選一個顏色後，點選`Create Symbol`就可以把醜醜的板先排好，再點進Symbol慢慢修改設計稿就好，這樣就可以在最短的時間內先給出一個概要，就不用等細部的設計稿全部出來後才能和 PM與工程師溝通了。



###Create New Shared Style

當我們建立好畫布（這邊以 iPhone）、設定好尺寸後就可以開始實作啦～課程以 "iPhone的聯絡人頁面"為範例，我們要從零開始把它畫出來。

在前面講完 Symbol的概念後，我們就可以「無腦地」拉出一個方形 `Rectangle` `快捷鍵command+r`，如果要畫正方形的話要先按住 `Shift`。很醜沒關係，我們再去 Symbol內修就好。
這邊可以先記一下圓形是 `o`，同理先按住 `Shift`就會畫出正圓形。

>在 Sketch中使用快捷鍵的時候，一定要先把鍵盤切換到英文才有用喔
>
>快捷鍵其實可以去找 [Sketch Cheat Sheet](https://dribbble.com/shots/1522880-Sketch-3-Cheat-Sheet)，有很多快捷鍵可以記，這次上課也會新增很多快捷鍵。

通常我們畫完圖形後，如果要拖曳的話有點不方便（因為游標還沒變），這個時後只要按 `esc`，游標就會從十字形變回一般游標，就可以拖曳圖片了。

畫完圖形後，我們點選畫面右側的 `Create New Shared Sytle` 

![Alt text](/SketchPracticepics/sharedstyle.png)

接著在框框寫 `@P-50`

![Alt text](/SketchPracticepics/sharedstyle-1.png)