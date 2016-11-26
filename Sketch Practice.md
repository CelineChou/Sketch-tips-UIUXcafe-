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

新增完成後，就會在右側列表中看見我們剛剛新增的`@P-50`，我們在其他的色塊也可以使用這個顏色，如果這個顏色變更時，所有套用的顏色也會一起變更，也是一個 Symbol的概念。


這邊把名字取為`@P-50`的原因，是因為當我們命名很多顏色，卻還按照原本圖層方式命名的話會有點混亂，我們可以參考 [Google Color palette](https://material.google.com/style/color.html#) 的命名，所以這裡`@P-50` `百分之五十的粉色`。




###畫出一個聯絡人資訊的Cell###

現在畫布上畫出一個長方形，隨意拉出一些文字的輸入匡然後做成 Symbol。

如果我們要調整文字匡的位置，除了拖曳之外，還可以按住 `Option`就可以看到框框附近出現了尺寸，此時再以上下左右鍵調整即可。如果我們要移動的距離比較大，可以按住 `Option + Command`讓框框一次可以移動 10pt。

接下來我們要畫聯絡人資訊的icon，這邊建議可以用一個圓形中間加上一個文字匡直接寫 i。
把聯絡人資訊i畫好後，我們可以在這個 Symbol中，再將這個i和圓形再匡起來變成一個 Symbol。

接下來要畫 iPhone電話號碼前面的電話icon，直接去找網路上的 icon有非常多的 icon圖庫，不需要再費太多心思畫。
課程中推薦了一個網站叫 [Noun Project](https://thenounproject.com/) 可以到這邊下載圖片，記得點選 `SVG`格式的檔案。新增到 Sketch之後，在圖層的地方點開它的圖片資料夾，將不必要的圖層刪除，就可以乾淨的使用電話的 icon了。


接著我們需要在聯絡資訊的最左側加上一個聯絡人的頭像（畫出一個圓形），再匯入我們需要的圖片。

方法一：我們可以將 FB大頭貼的資訊下載下來後，回到 Sketch點擊剛剛畫的圓形，再點擊右側 `Fills`，點擊上排有一個和 iPhone上方的相簿 icon相似的圖，就可以選擇匯入的圖片了。

方法二：其實直接將大頭貼從 FB直接拖曳到 `Fill`中即可。

![Alt text](/SketchPracticepics/profile.png)

畫好之後，大概會長得像這樣：

![Alt text](/SketchPracticepics/contactcell.png)


###複製許多個聯絡人資訊###

當我們將一個cell編輯好後，再回到畫布的頁面：

![Alt text](/SketchPracticepics/homepage.png)

如果我們需要讓這個頁面出現很多一樣的聯絡人資訊，只需要把這個 cell選起來，然後找到我們一開始在最上面的工具列增加的 `Make Grid`，設定好你要增加的個數，就可以看到畫布上成功複製了。

![Alt text](/SketchPracticepics/gridtool.png)

成功後可以看到這樣的畫面：

![Alt text](/SketchPracticepics/homepage-1.png)


雖然這個方法很迅速，但還是免不了需要一個個填寫不同的聯絡人資訊。這個時候我們可以使用一個外掛叫做 `Craft`![Alt text](/SketchPracticepics/craft.png)，這是一個 invision出的 Sketch外掛。

詳細的下載與使用方式在這裡：[https://github.com/CelineChou/Sketch-tips-UIUXcafe-/blob/master/SketchPlugins.md](https://github.com/CelineChou/Sketch-tips-UIUXcafe-/blob/master/SketchPlugins.md)

下載安裝後可以看到 Sketch在畫布和右側控制列的中間出現了四個不同的圖示:

![Alt text](/SketchPracticepics/craft-1.png)

當我們把資料格式設定好後（資料格式設定請見 Skethc外掛篇），回到畫布，再點擊第四個圖示就可以設定要複製幾個資訊。

我們使用了這個外掛後，可以將每個欄位核對到 Craft中，當我們複製下拉這個 cell的時候， Craft就會自動幫你把資訊填進去這個欄位裡，我們就不用絞盡腦汁想說要填哪些假資料了。

確定後，就可以看到以下資訊：
![Alt text](/SketchPracticepics/homepage-2.png)

到這邊，我們的聯絡人資訊就大致上完成了。