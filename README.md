George Stibitz 的 繼電計算機


在1925年，貝爾電話實驗室被合併，以作為貝爾系統的基礎研究設施。
因此，他們創始了一個機構，此機構可被稱作為物理、化學及各個現代科學的新領域中兼具基礎且令人興奮的研究的代名詞
在未來的幾十年當中，這個機構將會做出多方的研究，同時也能培養出許多發明家成為諾貝爾得獎者。
諸多關於計算機領域的新發明也在這項機構中被研發，其中包括第一個二極管的邏輯方案 (1942年)、點接觸晶體管 (1947年)、第一台完整的晶體管計算機 (TRADIC ,1955年)、第一台數據機 (1960年)、第一台單晶片32位元處理器(1980年)、UNIX操作系統 (1969年)、C語言 (1973年)以及C++ (1983年)等等。


在1937年11月的某個傍晚，一名貝爾實驗室的數學研究員－George Stibitz，回家前從公司的儲藏室拿了兩個電話繼電器、一對手電筒燈泡、一串電線及一顆乾電池。
到家後，他坐在餐桌前，用帶回來的材料及一個煙草罐製作的開關，組裝了一個簡易的邏輯裝置，裝置中燈泡發亮代表二進位中的 1 ，熄滅的燈泡代表二進位中的 0 ，而這個裝置也被證實為是最早的二進制加法器。
George Stibitz的妻子Dorothea將之取名為K-模型，因為是在餐桌(Kitchen table)上完成的。
隔天，Stibitz夫婦帶著K模型到實驗室展示給同事看，他們便開始估量造出一台未安裝繼電器且完整尺寸的計算機的可能性。
他的同事推測就算是任意一台使用二進位且實際的繼電器計算機，也需要數百台繼電器，因此與當時實驗室使用的工業機械計算機相比，體積更大且更昂貴。


但是，Stibitz發現繼電計算機不只可以顯示0和1，它也可以顯示出計算的順序，繼電電路可以控制出順序並且能根據所需儲存臨時結果。
尤其是它可以執行複數乘法與除法的一系列操作:貝爾實驗室的研究員經常在長距離電路下用過濾器和放大器設計執行兩項數學運算。
在1930年，實驗室有整整一個房間的人類”計算機”用工業機械式計算機運算複數的餘式或商式。
這些計算本身都很直截了當:一個複數的乘法需要6個簡單的運算操作，一個複數除法需要約一打的操作，且每個操作都需要一些暫存的記憶空間來儲存臨時的結果。


Stibitz並不知道在柏林有一人名叫Konrad Zuse也同時在做幾乎一樣的事情。
但是Stibitz確實知道Claude Shannon還在麻省理工學院研究生期間已經研究出符號邏輯語句與二進制繼電器電路的對應關係。Shannon寫了關於此主題的研究論文(1938年出版)，隨後他去了貝爾實驗室，並和Stibitz研究彼此的成品。
但是Shannon並沒有積極的參與Stibitz的計算機設計。
顯然在1930年晚期，使用繼電計算機執行二進制邏輯的想法是很普遍的。(在日本有類似的發現)


當Stibitz第一次向公司上層展示K模型，他們並沒有非常感興趣。
沒有煙火，沒有香檳，就像他後來記得的那樣。
然而，在不到一年間，貝爾公司的高層改變了他們對Stibitz的發明的看法。
其中一個主要影響他們決策的原因是來自於越來越多的複數運算問題對貝爾公司所產生的壓力。
公司同意花大筆錢資助Stibitz的大型模型。
Stibitz在1938年2月完成他的設計，而模型的建造始於1939年4月，由貝爾公司的一個切換工程師Samuel Williams著手建造。
最終的產品完成於8月，首次操作則在1940年1月8號執行，一直使用到1949年。
由於貝爾實驗室建造其他的繼電計算機在戰爭當中，因此它的名字從最初的複數計算機改為模型1號。花了大約2萬美金。


一開始的複數計算機只能處理複數乘法與除法，但不久後則被修改成也可以適用於加法和減法了。
它使用了約400到450個二進制繼電器、6到8個面板以及10個被稱為翹棍的多位置、多極的繼電器當作臨時的數字儲存空間。
這台機器使用了十進制系統，並且有小數點在數字的開頭。
內部有4個二進制繼電器編算各個數字，且使用一個代表十進制數字n的號碼來表示n+3；此機制簡化了加減法的問題(超過三個二進制編碼的十進制數字至今仍然被稱為Stibitz編碼。)
這台機器可以在它的寄存器裡處理一個十個位數的數字，但只能顯示出八個位數的答案。(範圍為0.99999999。)
它使用前綴表示法:意即，操作者輸入操作數，然後才輸入算術運算。
例如，兩個複數相乘(2+3i)*(4+5i)，操作者會輸入(參考上方的鍵盤圖):
M+.2+i.3+.4-i.5=
字母M表示乘號。(字母D則表示除號。)
在四個數字前標記小數點的位置。
機器其實會計算(0.3+0.5i)*(0.4-0.2i)，然後會印出答案0.07000000+i0.22000000。
操作者必須按比例縮放結果(乘以100)。
一個簡單的加法運算需花上約100毫秒的時間，然而一個複數乘法的運算需花上約45秒。


一個計算單元含有4個寄存器，它們是一個特別的終端且輸出與輸入單元被完全分離(參考左圖)。
電腦本身被存放在實驗室裡偏僻的房間內，只有很少人看過。
操作者使用三台中的一台被改造過的電傳打字機(鍵盤和一個列印裝置)遠端控制，用多線總線連接到處理器後將之移至他處，但這並不能同時的運作。


Stibitz進一步發展了更多遠端遙控、多重存取計算機的點子。
在1940年9月11日，美國數學學會在坐落於新罕布什爾州漢諾威市的達特茅斯學院舉辦會議，那裡距離紐約貝爾實驗室，也就是複數計算機的所在處，以北約數百英里。
Stibitz安排用電話線(28條線的電傳打字線纜)將計算機連接到安裝在其中的電傳打字設備。
複數計算機運作得很順利，毫無疑問地，使用過的人都大為讚嘆。
許多參加美國傑出數學家和對計算機有重要貢獻的人也都出席了這場會議。(如:
John von Neumann、 John Mauchly、Norbert Wiener和Garrett Birkhoff。)
達特茅斯學院展示了遠端計算在現代的預兆，但這種遠端存取型態在十年後並沒有延續下去。


複數計算機不可編譯。
繼電電路的結合能永久地控制一系列的操作。
那些繼電器與用來處理數字的繼電器是同一種樣式的，但是機器沒有明確地分開定義用來控制計算機序列的部件。(後來貝爾實驗室做到了。)
在複數計算機被建造後，貝爾實驗室才出現了可編程性的概念，
因為它的建造者看見它的基礎計算元素被其結合的過份限制，無法與控制電路連接起來，只能將其與複雜的運算連接在一起。
(除了複數運算，他們嘗試用機器去執行多項式運算，其中的複數運算是一個特別的例子，但機器對於多項式的限制特別多。)


複數計算機的成功鼓舞了Stibitz提出更多大膽的設計，包括了使用穿孔磁帶去修改計算機的操作。
起初，實驗室拒絕了他的提議，但由於美國在1941年12月參與第二次世界大戰，貝爾實驗室轉移了重心，投入了比平時研究更多的計算量去執行軍事計畫。
他們大部分的戰時成就都在模擬計算機的設計當中。
但他們也因為軍事用途建造了5台數位繼電計算機，還有多造了一台在戰爭結束後當作自用計算機，因此總共建造了7台的複數計算機。


最初的軍用計算機是繼電插值器，它在1943年被安裝在華盛頓，也是往後人們熟知的模型2號(Model II)。
它耗材440台繼電器以及7位數的記憶容量。
乘法運算的速度是4秒鐘(它是用重複的加法來運算乘法)。
它主要是用來解決指導防空火力有關的問題，這些算術運算對通過紙帶提供給機器的功能值進行插值。
就像是複數計算機一樣，它是一個有特別目的機器；
不過，它的運算序列不是永久連接的繼電計算機，而是由黏成一圈的公式膠帶(五通道的紙膠帶)所供給的。
不同的膠帶可以使用不同的插值方法。
模型2號除了插值法外並沒有很多其他的用途，但是由於插值法是一個解決許多科學與工程問題的過程，因此這台機器在戰爭過後仍被其他政府機構頻繁使用。


還有另外兩個Stibitz設計的機器，分別是彈道計算機(Ballistic Computer)和馬克22偵錯機(Error Detector Mark 22)(即後來的模型3號和模型4號)，他們是相似的機器，前者於1944年被安裝在德州布利斯堡，後者則在1945年早期被安裝於華盛頓(此二台造價各約65000美金)。
他們擁有約1400台繼電器以及10個位數的記憶容量。
運算乘法的速度為1秒鐘(它是用查表的方式來運算乘法)。
這些機器也使用紙膠帶輸入資料及公式，以環繞的紙膠帶供給運算序列。
模型3號及4號就像是模型2號，同樣可以解決瞄準與追蹤防空武器的問題。
但它們是更複雜的機器，不只能執行插值法，更能推算彈道後寫出目標飛機的軌跡以及防空炮的軌跡。還有一個附加的紙帶指示機器要使用哪些功能。
因此模型3號和模型N是貝爾實驗室中最早擁有普通可編輯性程度的數位計算機，雖然他們都不是完整的一般用途的計算機。
它們的記憶及運算單元僅有最少的容量:精度只有十進制的6位數，每台機器只有十個位數的容量。


Stibitz設計最大的計算機也是此系列最後一個叫做模型5號，在1946和1947年貝爾實驗室也建造了兩台同樣的軍用機。
它是一台非常巨大(重10噸)且昂貴(要價500000美金)的機器。
每台皆含有超過9000個繼電器，並以科學記號表示處理的數字。
儲存空間可以容納三十個數，紙帶讀取機可以同時輸入程式步驟及數字數據。
乘法運算也只需0.8秒。
模型5號最有趣的地方是它擁有兩個分開的運算單元，每個操作能力就像是獨立且擁有自己的記憶寄存器和輸入及輸出的裝置的電腦。
簡單的問題可以在機器中的兩個單元同時運作，非常省時，而較複雜的問題可以同時使用兩個處理器。
關於處理器(使用現代詞彙)，每個處理器有15個記憶寄存器，總共30個存在於此機器中。
主控單元根據其可用性將指令定向到一個或兩個處理器。
這個控制單元是從處理器中的控制單元被分離出來的，它可以定向一系列的運算、記憶存取和輸入及輸出的操作；可以說它控制了控制器。(Stibitz稱它為一個超級分支的能力。)因此模型5號是真正意義的操作系統－是一透過計算機監測及管制工作流向的控制單元。


除了編譯程式的能力外，後期的貝爾計算機強調不凡的可靠性。
用來當作邏輯操作和記憶存取的基礎元素的繼電器，有間歇故障的趨勢。
如果在兩個繼電器連接處有灰塵累積，電路很可能會故障，雖然其他的繼電器不會有事。
經過了幾次的循環，灰塵的粒子可能會自己晃動，然後會恢復正常。因此整個計算可能會有誤差，但卻不是因為機器故障。


貝爾公司的工程師設計了一個可以自行偵測每個計算步驟的計算機電路。
這個電路不只可以做加減法、儲存數字還有很多功能；它們更設計了一個功能可以自行檢測機器是否正確執行操作，否則將自行停止運作。
貝爾的工程師還以他們設計電話電路的經驗為指導，這些電話電路還必須在無人值守且在惡劣的環境下長時間運作。
那些電路被設計成可以被半熟練的技術員修復的狀態，不然電話裝置會變得非常昂貴每當電話線故障或是顧客的手機當機都要打電話給工程師。
貝爾實驗室的模型2號到4號使用的系統中，每個十進制編碼的並非4個繼電器而是7個二進制繼電器。他們被分為兩個繼電器及五個繼電器的組別；十進制編碼如下圖:


貝爾實驗室稱這個系統為二五進制計數法，因為繼電器的重量為一和五。
事實上，它並不是那些數字基礎的結合，而是一個7位元和十進制編碼混合而成。
所有貝爾實驗室的繼電計算機使用十進制演算法運作。一個特別的電路檢查發現每個十進制數字有兩個繼電器，並且只有兩個繼電器被充能。
另一個電路負責檢查是否每個組別中只有一個繼電器被啟動－如此一來則可以防止兩個分開的錯誤被相互抵消，雖然有些異常的故障組合可能無法被偵測到。




單字

Incorporated 合併
Institution 機構、制度
Synonymous 同義的
Frontiers 邊疆、前沿
Scheme 方案、格式
Diodes 二極管
point transistor 點接觸晶體管
modem 數據機
tobacco 煙草
arithmetic 算術
 interim 臨時
circuits 電路
amplifier 放大器
modification 修改
panel 面板
registers 寄存器
prefix 前綴
terminal 終端
teletype 電傳打字
foreshadowed 預兆
unduly 過分地
perforated 穿孔
antiaircraft fire 防空火力
sophisticated 複雜的
intermittently 間歇地
malfunctions 故障
