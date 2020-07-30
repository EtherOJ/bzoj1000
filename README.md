
# Description

<div class="content">撞啊撞，撞啊撞，DP终于在规定时间内撞完了所有的石头。轰的一声，一扇厚重的石门上升了，露出一个门，大家激动地冲了进去，却发现是另外一个巨大的迷宫。。。。。。
又经过N轮天翻地覆的巨响之后，DP终究还是把头转昏了，幸好的是他撞完了最后一个迷宫。在DP昏厥之际，也正是谜题解开之际。就在最后的一个小石洞里面，记录了这里N光年前的历史。原来在那个时候，也发生了一次巨大的变动，当时的KD同样是为了维护世界的和平而战死沙场。后来它的朋友们十分的悼念它，所以其中一部分便开始进行对自然法术的研究，经过了漫长的岁月之后，复活圣地终于问世，可惜的是KD的残骸早就不知道丢哪去了。
因为自然的力量过于强大，所以研究者不得不将它封印在地底，经历天地轮回之后，希望它在需要被用到的时候再次被召唤出来，避免悲剧的再次发生。
当知道有复活圣地这种东西存在的时候，大伙都伴随着惊讶和兴奋，立即将KD和其他阵亡战士的GC抬出地面，此时地面早已发生了翻天覆地的变化，战争过后破烂的土地已不复存在，只能看见由光构成的网格状平台覆盖着地面，圣地中心清晰可见。但是自然的力量实在过于强大，导致根本无法靠生物做功而将盒子送至中心，爱因斯坦理论空前乏力，牛顿力学受到极大的挑战。难道只能依靠说明中介绍的控制地来操纵自然力量转移盒子了么，但是它是什么，它在哪，大伙一脸茫然。
话说另外一处，临时组成的寻找F小队还在墓地内四处搜索，却一无所获。而在地面裂开的时候，F就已落入了墓地层下层的地下水系了。此时，F在某处被冲上了岸，碰巧的是，正好冲到了传说中的控制地。F醒来之后，发现四周死寂一片，不得不朝仅有的一处光源靠近。而光源处，除了一个奇怪的控制器以外什么都没有，别无选择，F只能一头雾水地按照控制地的说明进行操作，期望能找到回到地面的方法。
以KD盒子所在的格子为中心，控制地的投光屏上建立了平面直角坐标系，圣地中心在X，Y处。现在的任务就是使用各种咒语，将KD的盒子移动到圣地中心。由于这个控制器年代太久远了，说明上的字被自然所磨损，所以F现在能看清楚的只有X咒语和十咒语。
每念一次咒语，可以选择某坐标格为中心，扩展出一个长度为L的X形状或者十形状，并且顺时针或者逆时针旋转90度，每个格子上的东东会被一起旋转。详细描述如图，红色格子为中心，4个方向扩展出的格子数包括中心格子为长度，箭头表示物品的转移路径。
为了尽快完成任务找到回地面的方法，所以F想知道，至少要念多少个咒语才能完成任务，但是似乎扳蹄子数不出来，所以只好求助于过去世界的你。
</div>

# Input

<div class="content">第一行一个正整数T，表示一共有T组需要计算的坐标及长度。
接下来T行每行3个整数X、Y、L，表示圣地中心坐标为X，Y，咒语中扩展出的X形状和十形状的长度为L，当然咒语不可能白念，所以L&gt;1。
</div>

# Output

<div class="content">对于每组输入数据输出一个整数ANS，表示至少要念ANS个咒语才能完成任务。
如果无法完成任务，请输出“Poor F！”
</div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
12 20 5<br/>
14 22 5<br/>
0 1 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
5<br/>
Poor F！<br/>
</span></div>

# Hint

<div class="content"><p>对于10%的数据，X、Y、L的绝对值&lt;=10^2，T&lt;=5；<br/>
    对于40%的数据，X、Y、L的绝对值&lt;=10^16，T&lt;=100；<br/>
    对于100%的数据，X、Y、L的绝对值&lt;=10^500，T&lt;=1000；<br/>
注意事项：<br/>
每个数都没有前导0。<br/>
<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=HNOI2009集训Day8">HNOI2009集训Day8</a></p></div>

