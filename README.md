
# Description

<div class="content"><p>　　DotR (Defense of the Robots) Allstars是一个风靡全球的魔兽地图，他的规则简单与同样流行的地图DotA <br/>
(Defense of the Ancients) Allstars。DotR里面的英雄只有一个属性——力量。他们需要购买装备来提升自己的<br/>
力量值，每件装备都可以使佩戴它的英雄的力量值提高固定的点数，所以英雄的力量值等于它购买的所有装备的力<br/>
量值之和。装备分为基本装备和高级装备两种。基本装备可以直接从商店里面用金币购买，而高级装备需要用基本<br/>
装备或者较低级的高级装备来合成，合成不需要附加的金币。装备的合成路线可以用一棵树来表示。比如，Sange <br/>
and Yasha的合成需要Sange,Yasha和Sange and Yasha Recipe Scroll三样物品。其中Sange又要用Ogre Axe, Belt<br/>
 of Giant Strength和 Sange Recipe Scroll合成。每件基本装备都有数量限制，这限制了你不能无限制地合成某<br/>
些性价比很高的装备。现在，英雄Spectre有M个金币，他想用这些钱购买装备使自己的力量值尽量高。你能帮帮他<br/>
吗？他会教你魔法Haunt（幽灵附体）作为回报的。</p></div>

# Input

<div class="content"><p>　　第一行包含两个整数，N (1 &lt;= n &lt;= 51) 和 m (0 &lt;= m &lt;= 2,000)。分别表示装备的种类数和金币数。装备<br/>
用1到N的整数编号。接下来的N行，按照装备1到装备n的顺序，每行描述一种装备。每一行的第一个<span style="color: rgb(255, 0, 0);">非负整数</span>表示这<br/>
个装备贡献的力量值。接下来的非空字符表示这种装备是基本装备还是高级装备，A表示高级装备，B表示基本装备<br/>
。如果是基本装备，紧接着的两个正整数分别表示它的单价（单位为金币）和数量限制（不超过100）。如果是高<br/>
级装备，后面紧跟着一个正整数C，表示这个高级装备需要C种低级装备。后面的2C个数，依次描述某个低级装备的<br/>
种类和需要的个数。</p></div>

# Output

<div class="content"><p>　　第一行包含一个整数S，表示最多可以提升多少点力量值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">10 59<br/>
5 A 3 6 1 9 2 10 1<br/>
1 B 5 3<br/>
1 B 4 3<br/>
1 B 2 3<br/>
8 A 3 2 1 3 1 7 1<br/>
1 B 5 3<br/>
5 B 3 3<br/>
15 A 3 1 1 5 1 4 1<br/>
1 B 3 5<br/>
1 B 4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">33</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

