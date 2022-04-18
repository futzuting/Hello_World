# HackMD期中作業筆記
---

### *HackMD隨堂作業*
1. [我的第一個hackmd筆記](https://hackmd.io/@futzuting/SJZBijag9)
2. [色塊強調](https://hackmd.io/@futzuting/HJSnJNeGc)
3. [將文字畫上螢光筆](https://hackmd.io/@futzuting/S15KHLYfq)
4. [表格練習](https://hackmd.io/@futzuting/B1k4G5GXc)
5. [程式碼](https://hackmd.io/@futzuting/SyIhA6sXq)

## 計算機概論:
### :computer:*電腦組成與架構*
:::success
早期的電腦是一種相當複雜、難以操作的機器，為了讓電腦變得新力改良電腦架構，心力改良電腦架構，歷經無數次的變更，發展出一個可供遵循的藍圖，為現代電腦奠定良好的基礎。

使用電腦來處理資料，也需經過輸入、處理、輸出等過程，這些過程是透過組成電腦基本架構的五大單元來完成。本節將介紹電腦的五大單元，以及電腦運作過程中用來傳遞資料或訊號的匯流排。
:::
### :computer:*硬體五大單元*
**電腦硬體**的架構是根據*范紐曼*所提出的五大單元架構，分為<font color=EA0000>記憶單元、算術/邏輯單元、控制單元、輸入單元、輸出單元</font>等。

![](https://i.imgur.com/kXw7Cmo.png)

- 輸入單元（Input Unit，IU）
是==電腦接收指令及輸出資料的管道==。鍵盤、讀卡機、滑鼠、掃描器均屬輸入單元的設備。
- 控制單元（Control Unit，CU）
用來==控制及協調電腦各單元間的運作==。電腦指令的解碼、資料的傳遞、及與電腦各單元間的協調等工作，皆須在本單元的監督下進行。
- 算術/邏輯單元（ Arithmetic/Logic Unit，ALU）
==負責資料的運算與邏輯判斷==。
:::info
控制單元（CU）+算術/邏輯單元(ALU）=中央處理單元(CPU)
:::
- 記憶單元（Memory Unit，MU）
是電腦存放程式與資料的地方。可分成主記憶體與輔助記憶體兩類:
1. <font color=EA0000>主記憶體</font>:容量較小，存取速度快，多用來存放處理中的指令和資料(如暫存器、隨機存取記憶體)
2. <font color=EA0000>輔助記憶體</font>:容量較大，存取速度慢，用於儲存大量的程式和資料
- 輸出單元（Output Unit，OU）
==電腦輸出運算結果的管道==。顯示器、印表機、喇叭:sound:等設備均屬輸出單元的設備。
### :computer:*匯流排*
:::success
**匯流排(Bus)** 是電腦各單元間進行資料或訊號傳送的管道；在電腦的運作過程中，不論是要處理的指令、資料，或是運算後的結果，都必須透過匯流排來傳送，通常會依線路所傳輸的訊號類型分為三種類型:
:::
- 控制匯流排
主要作用為傳送CPU發出的控制訊號(如讀取、寫入、重置等)，是單向傳輸的排線。
- 位置匯流排
用來傳送資料在主記憶體中的位址，是單向傳輸的排線，匯流排的排線愈多主記憶體容量愈大。
- 資料匯流排
主要負責各單元間傳送資料或指令的通道，是雙向傳輸的排線，匯流排的排線愈多表示每次能夠傳送的資料愈多。

![](https://i.imgur.com/ZuQVpS0.png)

{%youtube wg2CCsj-bVU %}

### :computer:*CPU的運作*
:::success
**CPU**執行一個指令的過程稱為一個機器週期（machine cycle），主要包含擷取、解碼、執行、儲存等4個步驟。其中擷取及解碼的步驟合稱為指令週 期（Instruction cycle），又稱擷取週期（fetch cycle）；執行及儲存的步驟則合稱為執行週期（Execution cycle）。
:::
![](https://i.imgur.com/arZes2I.png)

每一個機器週期的執行時間，通常只需幾百萬分之一秒（甚至更短），因此也有人使用MIPS（Million of Instructions Per Second，每秒百萬個指令）為單位， 來表示CPU每秒可執行多少百萬個指令。MIPS值越高，表示CPU執行的速度越快。

### :computer:*快速鍵*


|   快速鍵   |     描述     |   快速鍵    |       描述       |
|:----------:|:------------:|:-----------:|:----------------:|
| 滑鼠+SHIFT | 選取連續檔案 |  滑鼠+CTRL  | 選取非連續性檔案 |
|   CTRL+A   |     全選     | CTRL+SHIFT  |    切換輸入法    |
|   CTRL+C   |     複製     |   CTRL+X    |       剪下       |
|   CTRL+V   |     貼上     | SHIFT+SPACE |  切換全形與半形  |


### :computer:*程式碼*
HTML語法
```htmlembedded=59
<!DOCTYPE html>
<title>Title</title>

<style>body {width: 500px;}</style>

<script type="application/javascript">
  function $init() {return true;}
</script>

<body>
  <p checked class="title" id='title'>Title</p>
  <!-- here goes the rest of the page -->
</body>
```
C#語法
 ```c#=+
using System.IO.Compression;

#pragma warning disable 414, 3021

namespace MyApplication
{
    [Obsolete("...")]
    class Program : IInterface
    {
        public static List<int> JustDoIt(int count)
        {
            Span<int> numbers = stackalloc int[length];
            Console.WriteLine($"Hello {Name}!");
            return new List<int>(new int[] { 1, 2, 3 })
        }
    }
}



