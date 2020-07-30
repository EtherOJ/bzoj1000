
# Description

<div class="content"><p><span style="font-size: medium">Farmer John 建造了一个美丽的池塘，用于让他的牛们审美和锻炼。这个长方形的池子被分割成了 M 行和 N 列( 1 ≤ M ≤ 30 ; 1 ≤ N ≤ 30 ) 正方形格子的 。某些格子上有惊人的坚固的莲花，还有一些岩石，其余的只是美丽，纯净，湛蓝的水。 贝茜正在练习芭蕾舞，她从一个莲花跳跃到另一个莲花，当前位于一个莲花。她希望在莲花上一个一个的跳，目标是另一个给定莲花。她能跳既不入水，也不到一个岩石上。 令门外汉惊讶的是，贝茜的每次的跳跃像中国象棋的马一样：横向移动1，纵向移动2，或纵向移动1，横向移动2。贝茜有时可能会有多达8个选择的跳跃。 Farmer John 在观察贝茜的芭蕾舞联系，他意识到有时候贝茜有可能跳不到她想去的目的地，因为路上有些地方没有莲花。于是他想要添加几个莲花使贝茜能够完成任务。一贯节俭的Farmer John想添加最少数量的莲花。当然，莲花不能放在石头上。 请帮助Farmer John确定必须要添加的莲花的最少数量。在添加的莲花最少基础上，算出贝茜从起始点跳到目标点需要的最少的步数。最后，还要算出满足添加的莲花的最少数量时，跳跃最少步数的跳跃路径的条数。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第 1 行: 两个整数 M , N </span></p>
<p><span style="font-size: medium">第 2..M + 1 行:第 i + 1 行，第 i + 1 行 有 N 个整数，表示该位置的状态: 0 为水; 1 为莲花; 2 为岩石; 3 为贝茜开始的位置; 4 为贝茜要去的目标位置.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第 1 行: 一个整数: 需要添加的最少的莲花数. 如果无论如何贝茜也无法跳到，输出 -1.</span></p>
<p><span style="font-size: medium"> 第 2 行: 一个整数: 在添加的莲花最少基础上，贝茜从起始点跳到目标点需要的最少的步数。如果第1行输出-1，这行不输出。 第 3 行: 一个整数: 添加的莲花的最少数量时，跳跃步数为第2行输出的值的跳跃路径的条数 如果第1行输出-1，这行不输出。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 8<br/>
0 0 0 1 0 0 0 0<br/>
0 0 0 0 0 2 0 1<br/>
0 0 0 0 0 4 0 0<br/>
3 0 0 0 0 0 1 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
6<br/>
2<br/>
<br/>
输出说明 <br/>
<br/>
至少要添加2朵莲花，放在了&#39;x&#39;的位置。 <br/>
<br/>
  0 0 0 1 0 0 0 0     0 0 0 1 0 0 0 0<br/>
  0 x 0 0 0 2 0 1     0 0 0 0 0 2 0 1<br/>
  0 0 0 0 x 4 0 0     0 0 x 0 x 4 0 0<br/>
  3 0 0 0 0 0 1 0     3 0 0 0 0 0 1 0<br/>
贝茜至少要条6步，有以下两种方案 <br/>
<br/>
  0 0 0 C 0 0 0 0     0 0 0 C 0 0 0 0<br/>
  0 B 0 0 0 2 0 F     0 0 0 0 0 2 0 F<br/>
  0 0 0 0 D G 0 0     0 0 B 0 D G 0 0<br/>
  A 0 0 0 0 0 E 0     A 0 0 0 0 0 E 0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

