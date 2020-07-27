
# Description

<div class="content"><p><span style="font-size: 12pt">   </span><span style="font-size: 12pt">佳佳有许多黑色和白色的小珠子，他最喜欢用它们穿成一串串漂亮的项链了。他的每条项链都是由不超过</span><i><span style="font-size: 12pt">n</span></i><span style="font-size: 12pt">个小珠子串在一起的环（称项链上的珠子数为项链的长度），每条项链至少有一个珠子。每做完一条项链就在其中的某一个珠子上贴一个标签，从贴有标签的那颗珠子开始</span><span style="font-size: 12pt">, </span><span style="font-size: 12pt">顺时针记录每个珠子的颜色（白色用</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">表示，黑色用</span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">表示）。标签上写着这种记录。</span></p>
<p></p><p></p>
<p></p>
<p></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">佳佳发现，这样做，每条项链都可以用多个标签来表示，例如图</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">(a)</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的项链，当标签分别贴在珠子</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">2</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">3</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">4</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的时候，标签上应分别写作</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">0100</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1000</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">0001</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">0010</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。在这样的情况下，佳佳总是选择字典序最小的一个串写在标签上。例如图</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">(a)</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的项链</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">, </font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">在珠子</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">3</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">处帖上标签</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">0001</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-spacerun: yes"><font face="Times New Roman">    </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">再考虑图</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">(b)</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">所示的项链，最小字典序的标签串是</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">0101</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，可是标签应该贴在哪颗珠子上呢？珠子</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">上还是珠子</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">3</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">上呢？佳佳不希望出现这样的情况。所以他在做项链的时候格外小心，保证做出来的项链是<b>合法的</b>（也就是不会出现标签位置不唯一的情况）。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-spacerun: yes"><font face="Times New Roman">    </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">这样，标签上的记录就可以标识一个串。根据标签上串的字典序就可以对项链进行排序，例如图</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">(c)</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的项链比图</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">(d)</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的小，因为</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">00101</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的字典序比</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">0011</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">小。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">任务一：新年快到了，佳佳决定给自己的两个双胞胎表妹一人做一条项链。刚做完其中一条项链后，佳佳突然有了一个绝妙的想法：既然是送给孪生姐妹，为什么不做一对“孪生项链”呢？换句话说，如果把所有可能的项链排好顺序，“孪生项链”的位置应当是相邻的，姐姐的项链标签的字典序要比妹妹的大。佳佳想把已经做好的一条项链送给妹妹，那么姐姐的项链应该是什么样子的呢？</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">任务二：佳佳还想知道所有<b>合法的</b>项链中长度恰好为</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">k</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的有多少条，你能告诉他吗？</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行包含三个整数</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">n</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">、</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">m</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><font face="Times New Roman"><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt">k</span></i><span lang="EN-US" style="font-size: 12pt">(1&lt;=<i style="mso-bidi-font-style: normal">m</i>,<i style="mso-bidi-font-style: normal"> k</i>&lt;=<i style="mso-bidi-font-style: normal">n</i>)</span></font><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，相邻整数用一个空格隔开，其中</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">n</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">表示每条项链的珠子数上限；</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">m</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">表示任务一中妹妹的项链长度；</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">k</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">表示任务二中的项链长度。第</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">2</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行包括一个长度为</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">m</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">01</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">串，表示妹妹的项链上的标签。输入数据保证无误。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt"><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21.75pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行有一个正<span style="color: black">整</span>数</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">t</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示长度恰好为</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">k</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的项链有</span><i style="mso-bidi-font-style: normal"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">t</font></span></i><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">条；第</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">2</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行包括一个</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">01</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">串，表示姐姐的项链上的标签。输入数据保证姐姐的项链一定可以做出来。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 5<br/>
00101<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
0011<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">100%</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的数据：</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1&lt;=<i style="mso-bidi-font-style: normal">n</i>&lt;=200,000 100%</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的数据：</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1&lt;=<i style="mso-bidi-font-style: normal">k</i>&lt;=1000</font></span></p><br/>
<p><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman"><o:p></o:p></font></span><br/>
</p><p></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"></p><br/>
<p></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">项链可能有以下</span><span lang="EN-US" style="font-size: 12pt">14</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">种：</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt">0, 00001, 0001, 00011, 001, 00101, 0011, 00111, 01, 01011, 011, 0111, 01111, 1<o:p></o:p></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">其中长度为</span><span lang="EN-US" style="font-size: 12pt">1, 2, 3, 4, 5</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的项链分别有</span><span lang="EN-US" style="font-size: 12pt">2, 1, 2, 3, 6</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

