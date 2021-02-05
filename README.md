#麗山高中簡易練習３６題
（以下題目並非都要用迴圈完成，但是幾乎都要用迴圈）
1.題目：求N! （如:5!=1*2*3*4*5）（必須用迴圈完成）

 

2.題目：讀取7個數（1—50）的整數值，每讀取一個值，程序打印出該值個數的＊。 （必須用迴圈完成）

 

3.題目： 輸入一十進位正整數，將期轉換成八進位正整數與十六進位正整數
 

4.題目：求s=a+aa+aaa+aaaa+aa...a的值，其中a是一個數字。例如2+22+222+2222+22222（此時

　　　共有5個數相加），幾個數相加有鍵盤控制。

 

5.題目：四位數中，求0—7所能組成的奇數個數。 （必須用迴圈完成）

 

6.題目：809*??=800*??+9*??+1 其中??代表的兩位數,8*??的結果為兩位數，9*??的結果為3位數。求??代表的兩位數，及809*??後的結果。 （必須用迴圈完成）

 

7.題目：某個公司採用公用電話傳遞數據，數據是四位的整數，在傳遞過程中是加密的，加密規則如下：

　　　每位數字都加上5,然後用和除以10的餘數代替該數字，再將第一位和第四位交換，第二位和第三位交換。

　　　當使用者輸入一數字時，請輸出其加密結果。

 

8.題目：有1、2、3、4個數字，能組成多少個互不相同且無重複數字的三位數？都是多少？ （必須用迴圈完成）

1.程序分析：可填在百位、十位、個位的數字都是1、2、3、4。組成所有的排列後再去

　　　　　　掉不滿足條件的排列。

 

9.題目：企業發放的獎金根據利潤提成。利潤(I)低於或等於10萬元時，獎金可提10%；利潤高

　　　於10萬元，低於20萬元時，低於10萬元的部分按10%提成，高於10萬元的部分，可可提

　　　成7.5%；20萬到40萬之間時，高於20萬元的部分，可提成5%；40萬到60萬之間時高於

　　　40萬元的部分，可提成3%；60萬到100萬之間時，高於60萬元的部分，可提成1.5%，高於

　　　100萬元時，超過100萬元的部分按1%提成，從鍵盤輸入當月利潤I，求應發放獎金總數？

1.程序分析：請利用數軸來分界，定位。注意定義時需把獎金定義成長整型。　　

 

10.題目：一個整數，它加上100後是一個完全平方數，再加上168又是一個完全平方數，請問該數是多少？

1.程序分析：在10萬以內判斷，先將該數加上100後再開方，再將該數加上268後再開方，如果開方後

　　　　　　的結果滿足如下條件，即是結果。（必須用迴圈完成）

 

11.題目：輸入某年某月某日，判斷這一天是這一年的第幾天？ （必須用迴圈完成）

1.程序分析：以3月5日為例，應該先把前兩個月的加起來，然後再加上5天即本年的第幾天，特殊

　　　　　　情況，閏年且輸入月份大於3時需考慮多加一天。

 

12.題目：輸入三個整數x,y,z，請把這三個數由小到大輸出。

1.程序分析：我們想辦法把最小的數放到x上，先將x與y進行比較，如果x>y則將x與y的值進行交換，

　　　　　　然後再用x與z進行比較，如果x>z則將x與z的值進行交換，這樣能使x最小。

 

13.題目：輸出9*9乘法表。 （必須用迴圈完成）

1.程序分析：分行與列考慮，共9行9列，i控制行，j控制列。

 

14.題目：給一個不多於5位的正整數，要求：一、求它是幾位數，二、逆序打印出各位數字。 （必須用迴圈完成）

 

15.題目：古典問題：有一對兔子，從出生後第3個月起每個月都生一對兔子，小兔子長到第三個月

　　　後每個月又生一對兔子，假如兔子都不死，問每個月的兔子總數為多少？ （必須用迴圈完成）

1.程序分析：　兔子的規律為數列1,1,2,3,5,8,13,21....

 16.題目：一個偶數總能表示為兩個質數之和，求輸入一偶數，列印出此兩質數。 （必須用迴圈完成）

 

17.題目：求100之內的質數　（必須用迴圈完成）

 

18.題目：判斷101-200之間有多少個質數，並輸出所有質數。 （必須用迴圈完成）

1.程序分析：判斷質數的方法：用一個數分別去除2到sqrt(這個數)，如果能被整除，

　　　　　　則表明此數不是質數，反之是質數。

 

19.題目：打印出所有的「水仙花數」，所謂「水仙花數」是指一個三位數，其各位數字立方和等於該數

　　　本身。例如：153是一個「水仙花數」，因為153=1的三次方＋5的三次方＋3的三次方。 （必須用迴圈完成）

1.程序分析：利用for循環控制100-999個數，每個數分解出個位，十位，百位。

 

20.題目：將一個正整數分解質因數。例如：輸入90,打印出90=2*3*3*5。 （必須用迴圈完成）

程序分析：對n進行分解質因數，應先找到一個最小的質數k，然後按下述步驟完成：

(1)如果這個質數恰等於n，則說明分解質因數的過程已經結束，打印出即可。

(2)如果n<>k，但n能被k整除，則應打印出k的值，並用n除以k的商,作為新的正整數你n,

　重複執行第一步。

(3)如果n不能被k整除，則用k+1作為k的值,重複執行第一步。

 

21.題目：利用條件運算符的嵌套來完成此題：假設有10位同學，請利用程式來判斷，當使用者輸入一學生的學習成績，如果學習成績>=90分的同學用A表示，60-89分之間的用B表示，60分以下的用C表示。 （必須用迴圈完成）

1.程序分析：這是條件運算符的基本例子。

 

22.題目：輸入兩個正整數m和n，求其最大公因數和最小公倍數。 （必須用迴圈完成）

1.程序分析：利用輾轉相除法。

 

23.題目：一個數如果恰好等於它的因子之和，這個數就稱為「完美數(Perfect Number)」。例如6=1＋2＋3.編程

　　　找出1000以內的所有完美數(Perfect Number)。 （必須用迴圈完成）

 

24.題目：一球從100米高度自由落下，每次落地後反跳回原高度的一半；再落下，求它在

　　　第10次落地時，共經過多少米？第10次反彈多高？ （必須用迴圈完成）

 

25.題目：猴子吃桃問題：猴子第一天摘下若干個桃子，當即吃了一半，還不癮，又多吃了一個

　　　第二天早上又將剩下的桃子吃掉一半，又多吃了一個。以後每天早上都吃了前一天剩下

　　　的一半零一個。到第10天早上想再吃時，見只剩下一個桃子了。求第一天共摘了多少。 （必須用迴圈完成）

1.程序分析：採取逆向思維的方法，從後往前推斷。

 

26.題目：兩個乒乓球隊進行比賽，各出三人。甲隊為a,b,c三人，乙隊為x,y,z三人。已抽籤決定

　　　比賽名單。有人向隊員打聽比賽的名單。a說他不和x比，c說他不和x,z比，請編程序找出

　　　三隊賽手的名單。

1.程序分析：判斷質數的方法：用一個數分別去除2到sqrt(這個數)，如果能被整除，

　　　　　　則表明此數不是質數，反之是質數。 　　

 

27.題目：打印出如下圖案（菱形） （必須用迴圈完成）

*

***

******

********

******

***

*

1.程序分析：先把圖形分成兩部分來看待，前四行一個規律，後三行一個規律，利用雙重

　　　　　　for循環，第一層控制行，第二層控制列。 （必須用迴圈完成）

 

28.題目：有一分數序列：2/1，3/2，5/3，8/5，13/8，21/13...求出這個數列的前20項之和。 （必須用迴圈完成）

1.程序分析：請抓住分子與分母的變化規律。

 

29.題目：求1+2!+3!+...+10!的和 （必須用迴圈完成）

1.程序分析：此程序只是把累加變成了累乘。 (將變數宣告為float即可紀錄期總和)

 

30.題目：一個5位數，判斷它是不是回文數。即12321是回文數，個位與萬位相同，十位與千位相同。 （必須用迴圈完成）

    2012/03/05修改：.題目：一個整數（<2147483647），判斷它是不是回文數。即12321是回文數，個位與萬位相同，十位與千位相同。 （必須用迴圈完成）

31.題目：輸入10個正整數，由小到大列印出來 （需要會陣列，不會請跳過）（必須用迴圈完成）

 

32.題目：求一個3*3矩陣對角線元素之和 （必須用迴圈完成）

1.程序分析：利用雙重for循環控制輸入二維數組，再將a[i][i]累加後輸出。

 

33.題目：打印出PASCAL三角形（要求打印出10行如下圖）　　（必須用迴圈完成）　

1.程序分析：

　　　 　　 1

　　　　　　1 　1

　　　　　　1 　2 　1

　　　　　　1　 3 　3　 1

　　　　　　1　 4　 6 　4 　1

　　　　　　1　 5　 10　10　5 　1　

 

34.題目：輸入3個數a,b,c，按大小順序輸出。　（必須用指標，不會請跳過！）　　

1.程序分析：利用指標方法。

 

35.題目：有n個人圍成一圈，順序排號。從第一個人開始報數（從1到3報數），凡報到3的人退出

　　　圈子，問最後留下的是原來第幾號的那位。 （必須用迴圈完成）

 

36.題目：編寫一個函數，輸入n為偶數時，呼叫函數求1/2+1/4+...+1/n，當輸入n為奇數時，呼叫函數求

　　　1/1+1/3+...+1/n(利用指針函數) （必須用迴圈、函數完成）

 