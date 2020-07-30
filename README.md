
# Description

<div class="content">有一个掷骰子游戏。玩家掷一个骰子（6个面，标号1到6）多次并统计点数和。玩家可以随时结束，但是至少要掷一次。如果点数和超过21，玩家就输了。当玩家结束后，庄家（庄家就是赌场老大）按一样的规则掷骰子。设玩家的点数和为Sp，庄家的点数和为Sc，玩家赢了当且仅当(Sp ≤ 21 and (Sc &gt; 21 or Sc &lt; Sp))。最优的庄家策略，让赌场的胜率超过了2/3。但是Andrew发现了提高他赢的概率的方法。他会和Big Man一起玩。Big Man每场游戏会押X欧元，Andrew每场押1欧元。赢家可以得到他的押注的双倍（包括他押下去的那份，即实际上只赢了一份），输的就会失去他的押注。
游戏的规则如下：
1.	Big Man先手，会在最优策略后停下来（该最优策略会无视Andrew）。
2.	然后轮到Andrew，Andrew知道Big Man掷的点数和。Andrew是个聪明的男孩，他知道庄家的最优策略是最大化赌场的收入。所以，Andrew会利用这些事实，实现自己的最优策略。
3.	最后轮到庄家。就像上面提到的，庄家也会用最优策略。
所谓的最优策略即最大化自己的收入。如果某人掷骰子之后的期望收入和当前的期望收入一样，那么他会选择掷骰子。
Andrew计算了下，如果X足够大，自己有将近50%的概率赢。
</div>

# Input

<div class="content">输入包含一个数X (0 ≤ X ≤ 1000)。
</div>

# Output

<div class="content">输出一个数字—Andrew赢的概率。精确到10-5。


</div>

# Sample Input

<div class="content"><span class="sampledata">1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.345634<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

