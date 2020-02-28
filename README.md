# homework1
George Stibitz的繼電器計算機
貝爾實驗室成立於1925年，是貝爾系統的基礎研究設施。
因此，這機構，已成為成為物理學、化學和其他現代科學分支的基礎和令人興奮研究的代名詞。
在接下來的幾十年裡，在這個令人興奮的地方將做大量的研究，這將給幾位發明家得到諾貝爾獎。
許多電腦領域的發明也將在這裡被造出來，

我們只提第一個二極體的邏輯數據模型(1942)，點接觸式電晶體(1947),第一台TRADIC電晶體電腦(1955),
第一台數據機(1960),第一台32位元單晶片的處理器(1980),UNIX作業系統 (1969), C語言(1973)和C++(1983)...。

1937年11月的一個深夜，貝爾實驗室的一位研究數學家，George Stibitz,離開工作崗位要回家，
從貝爾儲藏室拿了兩個電話繼電器，幾個手電筒筒燈泡和，一根電線和一個乾電池
在家裡，他坐在廚房桌子後面，用上述部件和開關開始組裝一個簡單的邏輯裝置，用菸草錫盒製成。
他很快做的裝置，被證明是第一個中繼二進制加法器，其中會亮燈泡表示二進位"1"和不會亮燈泡，二進位"0",
他的妻子Dorothea用"廚房桌子"的英文把這裝置命名為K型。
第二天，Stibitz's帶著K型去實驗室向同事們展示，他們推測了在繼電器上建造全尺寸計算機的可能性。
他的同事推斷，製成實用的繼電器電腦，使用二進位算術，可能需要數百個繼電器，
這使得它比當時在實驗室使用的商業機械計算器體積更大，成本更高。

但George Stibitz意識到，繼電器計算機能不只執行一次而且可以執行一系列計算，繼電器電路可以指導順序並根據需要存儲臨時結果。
具體而言，它可以執行執行複數乘法和除法所需的操作序列：貝爾實驗室其他地方的研究人員經常針對遠程電路的濾波器和放大器設計執行兩項數學運算。
在1930年代的實驗室裡，一屋子的人腦使用商業機械計算機計算複雜的數位商和產品。
計算本身非常簡單：複雜的乘法需要大約六個簡單的算數運算，而複雜的計算需要十幾個操作，並且每個需要臨時存儲一下結果。
Stibitz 不知道在柏林，Konrad Zuse幾乎同時做同樣的事情。
然而，Stibitz確實知道，在麻省理工學院讀研究生期間，Claude Shannon 也研究了數理邏輯與二進位中繼電路的對應關係。
Shannon寫了關於這主題的研究生論文（於1938年出版），然後去了貝爾實驗室，在那裡他和Stibit學習彼此的工作。
但是Shannon並未積極參與Stibitz計算機的設計。顯然，使用繼電器實現二進制邏輯的想法在1930年代後期很普遍。 （日本也有類似的發現）。
當Stibitz首次向公司高管展示他的K型電腦時，他們並沒有留下深刻的印象。他後來記得，那裡沒有煙火，沒有香檳。
然而，不到一年之後，貝爾的高層們改變了對Stibitz發明的想法。做出此決定的重要因素是，貝爾尋求解決其日益複雜的數學問題的方法的壓力越來越大。
公司同意資助Stibitz發明的大型實驗模型的建設。
Stibitz於1938年2月完成了設計，該機器的建造工作於1939年4月由貝爾的一位交換工程師Samuel Williams進行。
最終產品在10月準備就緒，並於1940年1月8日首次投入運營，一直使用到1949年。
貝爾實驗室在戰爭期間建造了其他繼電器計算機時，其名稱從最初的“複雜數字計算機”更改為“模型1”。成本約為20000美元。
最初，複數計算機僅執行複雜的乘法和除法，但後來進行了簡單的修改，使其也可以進行加法和減法。
它使用了大約400-450個二進制繼電器，6-8個面板和10個稱為“交叉開關”的多位置，多極繼電器來臨時存儲數字。
機器使用十進制系統，小數點固定在每個數字的開頭。
在內部，四個二進制繼電器對每個數字進行編碼，使用的代碼用n + 3的二進制代碼表示十進制數字n；
這簡化了數字進位和減法的問題（今天，多餘的三個二進制編碼的十進制仍稱為Stibitz碼）。
機器在其寄存器中處理了十位數的數字，但顯示並打印了八位數的答案（範圍為??0.99999999）
它使用“前綴”表示法：也就是說，運算符先將算術運算先輸入鍵，然後再輸入操作數。


例如，要將兩個複數（2 + 3i）乘以（4 + 5i），操作員將鍵入（請參閱鍵盤的上方圖）：
   M +.2 + i .3 +.4 -i .5 =
字母M代表乘法（鍵盤上的字母D代表除法）。請注意小數點的位置在四個數字中的每個數字之前。
機器實際上將計算（0.3 + 0.5i）x（0.4-0.2i），並輸出答案0.07000000 + i 0.22000000。操作員將不得不相應地縮放結果（乘以100）。
一個簡單的加法運算大約需要100毫秒，而將2個複數相乘大約需要45秒。
計算單元有4個暫存器，並且與作為特殊端子的輸入/輸出單元完全分開（請參見附近的照片）。
計算機本身被保存在實驗室的一間偏僻房間中，很少有人見過。
操作員可以使用三種改良的電傳打字機（鍵盤和打印設備）之一遠程訪問它，通過多線總線連接到處理器，並放置在其他位置，但是不能同時工作。
Stibitz進一步發展了遠程，多重存取計算機的想法。
1940年9月11日，美國數學學會在漢諾威的Dartmouth 學院會面，新罕布什爾州，在紐約貝爾實驗室大樓以北幾百英里處，複數計算機在那裡。
Stibitz安排通過電話線（28有線電傳打字電纜）將計算機連接到安裝在其中的有電傳打字設備。
複數計算機運行良好，毫無疑問，它給使用它的人留下了深刻的印象。
許多美國最傑出的數學家以及後來領導重要計算項目的人（例如John von Neumann, John Mauchly, Norbert Wiener and Garrett Birkhoff）參加了會議。
Dartmouth 示範預示了遠程計算的現代時代，但是這種類型的遠程訪問再過十年都沒有重複。
複數計算機無法編譯。繼電器電路的組合可永久控制其操作順序。
這些繼電器與用於處理數字的繼電器具有相同的類型，但是機器沒有單獨的，定義明確的部分來處理計算序列的“控制”。（後來的貝爾實驗室計算機採用了這種方法。）
只有在復雜數字計算機建成之後，貝爾實驗室才出現了可編程性的概念，因為它的建造者看到其基本計算元素受到其結合的過分限制，
無法與控制電路聯繫起來，只能將其與復雜的算術聯繫在一起。 
（除了複數算法外，他們還嘗試使機器執行多項式算術，其中復數算術是一種特例。但是，這對機器來說太受限制了。）
複數計算機的成功鼓勵了Stibitz提出更具雄心的設計，其中包括可以通過穿孔的磁帶修改計算器的操作。
起初，實驗室拒絕了他的提議，但隨著美國在1941年12月加入第二次世界大戰，貝爾實驗室將其優先重點轉移到了軍事項目上，該項目所涉及的計算量超過其和平時期的研究。
他們大部分的戰時成就都在模擬計算機的設計中。
但是他們還建造了五台用於軍事目的的數字中繼計算機，並在戰爭結束後又建造了一台供自己使用的數字中繼計算機，從而使總共七台數字計算機計算出了複數計算機。
這些用於軍事用途的計算器中的第一個是中繼插值器，該插值器於1943年安裝在華盛頓特區，後來稱為Model II。
它由440個繼電器構成，存儲容量為7個數字。乘法速度為4秒（通過重複加法乘法）。
它主要通過執行一系列算術運算來解決與指揮防空炮有關的問題，這些算術運算對通過打孔帶提供給機器的功能值進行插值。
像複數計算機一樣，它是一台專用計算機。但是，其算術序列不是永久連接的中繼計算器，而是由膠合成環路的“公式膠帶”（五孔鑿孔紙條）提供的。
因此，不同的磁帶允許人們採用不同的插值方法。 Model II除了插值以外，無能為力，但是由於插值法可以解決科學和工程學中的許多問題，
因此戰爭結束後很長一段時間內，其他政府機構就一直忙於處理機器。
接下來由Stibitz設計的兩台機器是相同的機器，分別是彈道計算機和錯誤檢測器Mark 22（後來稱為Model III和IV），
第一次安裝是在1944年在德克薩斯州的布利斯堡，第二次是在1945年初在華盛頓（每個花費65000美元）。
它們包含約1400個繼電器，並具有10個數字的存儲容量。乘法速度為1秒（通過查表乘法）。這些機器還將紙帶用於數據和公式輸入，其算術序列由打孔帶循環提供。
與模型II一樣，模型III和IV也解決了與高射砲瞄準和跟踪有關的問題。
但是，它們是更複雜的機器，不僅具有執行插值的能力，而且還能夠評估描述目標飛機和防空砲彈路徑的彈道方程。附加的打孔帶指示機器要評估哪些功能。
因此，Model III和Model N是Bell Labs中第一個具有一定程度的通用可編譯性的數字計算器，儘管它們都不是完全通用的計算器。
他們的記憶體和算術單元具有適度的功能：精度只有十進制的十進制數字，每台機器只能存儲十個數字。
這是系列中最大的計算機，也是最後一部由Stibitz設計的計算機是Model V，貝爾實驗室在1946年和1947年為軍方製造了兩台計算機。
這是一台巨大的機器（重10噸），非常昂貴（500000美元）。每個繼電器包含九千多個繼電器，並以科學計數法表示處理的數字。
該商店最多可以容納三十個數字，並且紙帶閱讀器可以同時輸入程序步驟和數字數據。乘法速度0.8秒。
V型設計最有趣的方面是它具有兩個獨立的算術單元，每個算術單元都可以作為具有自己的記憶體寄存器和輸入輸出設備的獨立計算機進行操作。
小型問題可以在計算機上成對運行，從而節省時間，而較大的問題可以接管兩個處理器。與每個處理器相關聯（使用現代術語）是15個存儲寄存器，整個機器總共有30個。
主控制單元根據其可用性將指令定向到一個或兩個處理器。該控制單元與處理器中控制算術，存儲器和輸入/輸出操作順序的控制單元是分開的。它可以控制控件，可以這麼說。 
(Stibitz稱其為“超級分支”功能。）因此，從真正的意義上講，Model V具有所謂的“操作系統”，即控制和管理通過計算機的工作流程的控制單元。
除了編程能力，後來的貝爾計算機還強調了非凡的可靠性。用作邏輯和存儲器操作的基本元素的繼電器有間歇性故障的趨勢。
如果在兩個繼電器觸點之間有灰塵積聚，則該電路將發生故障，儘管繼電器的其餘部分都可以。
幾次循環後，灰塵顆粒可能會自行晃動，然後一切恢復正常。因此，整個計算可能會偏離，而在診斷會話期間不會出現任何機器故障。
貝爾的工程師設計了計算機電路，可以在計算的每個步驟進行自我檢查。電路的設計不僅要增加，減去，存儲數字等等。
他們還被設計為檢查自己是否正確完成了這些操作，否則將機器停止。
貝爾的工程師還以其設計電話電路的經驗為指導，這些電話電路必須在經常處於不利環境的情況下長時間無人值守。
這些電路設計為由半熟練的技術人員進行維修；如果每次電話線掉線或客戶的電話壞了時都要打電話給工程師，電話服務的成本將非常高。 
Bell Labs II至VI模型使用的系統中，每個十進制數字編碼的不是四個而是七個二進制繼電器。它們分為兩組，每組兩個和五個繼電器；十進制代碼如下：

Decimal digit
Relays
0	01	00001
1	01	00010
2	01	00100
3	01	01000
4	01	10000
5	10	00001
6	10	00010
7	10	00100
8	10	01000
9	10	10000

貝爾實驗室稱此系統為“二元”表示法，因為繼電器的權重為一或五。實際上，它不是這些數字基礎的組合；
而是一個七位混合十進制代碼。所有的貝爾實驗室中繼計算機都以十進制算法工作。
一個特殊的電路檢查發現每個十進制數字有兩個，只有兩個繼電器通電。
另一個電路檢查了每個組中只有一個繼電器的接通狀態，這防止了兩個單獨的錯誤相互抵消，儘管某些異常組合可能無法檢測到。
incorporated 
a.  根據法律組成的公司, 公司
institution  
n.  機構, 慣例, 制度
synonymous  
a.  同義詞的, 同義的
fundamental  
n.  基本原理, 原則, 基波
a.  基本的, 重要的, 原音的
branch  
n.  樹枝, 支店, 支流, 分部
field  
n.  領域, 田地, 場地, 戰場, 場, 域
mention  
n.  提到
scheme  
n.  方案, 計劃
relay  
n.  驛馬, 替班, 中繼
assemble  
vt.  集合
tobacco  
n.  煙草
practical  
a.  實際的
arithmetic 
n.  算術
sequence  
n.  序列
straightforward 
a.  筆直的
temporary  
a.  暫時的, 臨時的
intermediate 
n.  中間物, 調停者, 中級
a.  中間的
correspondence  
n.  相符
involved  
a.  難懂的
subtract  
vt.  減去
multipole  
a.  多極的
storage  
n.  存儲器
multiply  
vt.  繁殖
accordingly  
ad.  相應地
remotely  
ad.  極小地
modify  
vt.  修正
simultaneously  
ad.  同時發生
foreshadow  
vt.  成為前兆
encourage  
vt.  鼓勵
military  
n.  軍隊
a.  軍事的
antiaircraft  
a.  防空的
agency  
n.  代理機構
target  
n.  目標
notation  
n.  記號
combination  
n.  組合
separate  
n.  獨立件
malfunction 
n.  故障



