
# Description

<div class="content"><p>Orez很喜欢玩游戏，他最近发明了一款硬币游戏。他在桌子的边缘上划分出2*n个位置并按顺时针把它们标号为1，2，……，2n，然后把n个硬币放在标号为奇数的位置上。接下来每次按如下操作：在任意两个硬币之间放上一个硬币，然后将原来的硬币拿走；所放硬币的正反面由它两边的两个硬币决定，若两个硬币均为正面朝上或反面朝上，则所放硬币为正面朝上，否则为反面朝上。 那么操作T次之后桌子边缘上硬币的情况会是怎样的呢？</p></div>

# Input

<div class="content"><p>文件的第一行包含两个整数n和T。 接下的一行包含n个整数，表示最开始桌面边缘的硬币摆放情况，第i个整数ai表示第i个硬币摆放在2*i-1个位置上，ai=1表示正面朝上，ai=2表示反面朝上。</p></div>

# Output

<div class="content"><p>文件仅包含一行，为2n个整数，其中第i个整数bi桌面边缘的第i个位置上硬币的情况，bi=1表示正面朝上，bi=2表示反面朝上，bi=0表示没有硬币。</p></div>

# Sample Input

<div class="content"><span class="sampledata">10 5<br/>
2 2 2 1 1 1 1 1 1 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 1 0 1 0 1 0 1 0 2 0 1 0 2 0 1 0 1 0 1<br/>
<br/>
数据范围<br/>
30%的数据  n≤1000  T≤1000<br/>
100%的数据  n≤100000  T≤2^60<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

