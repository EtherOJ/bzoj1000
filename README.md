
# Description

<div class="content">Famous biologist Herbert Greenstuff recently discovered a new kind of a plant, the graphius vulgaris, which is apparently endemic to the Pezinska Baba National Wilderness in western Slovakia. This plant is quite peculiar. On the first sight it looks just like a normal bush. However, on the second sight you may notice that its structure is far more complicated. When two branches of the bush touch each other they are able to grow together. In fact, they often do. The result is a bush that is incredibly twisted and dense. (If Herbert were not a biologist but a computer scientist instead, he would notice that when you consider the plant as a graph, it is no longer a tree but a general undirected connected graph.) 
A few days later the bushes were discovered for the second time by two computer science students, Alice and Bob. You probably know them, they are famous for playing games (and executing cryptographic protocols) day and night. They were in the middle of a simple game of NIM when Alice noticed the bushes. Immediately the simple NIM was forgotten. These bushes were an ideal opportunity to play a far more interesting game. 
Given is a connected graph (the bush) on N vertices. The vertices are numbered from 1 to N. Edges represent branches of the bush, vertex 1 represents the ground. Players alternate in making moves, Alice moves first. A move consists of two steps. In the first step the player selects an edge and removes it from the graph. In the second step he/she removes all the edges that are no longer connected to the ground. (The player cuts a branch of the bush and removes the part of the bush he cut away.) The first player who has no legal move (nothing to cut) loses. You may assume that both Alice and Bob play optimally. 
Your task is so simple you probably expect it already. You have to save the bushes before Alice and Bob destroy them. For each of the bushes you have to find out who will win if they play their game on it. After you tell them the results you will spoil them all the fun and they&#39;ll leave the bushes alone. Please hurry, the bushes are really rare! 
Alice &amp; Bob有一天发现了一株奇怪的灌木、他的枝分叉之后又可以汇合、更奇特的是来自不同的不仅是同一点的分叉可以汇合、即使分叉点相差很远、两根枝条仍然可以生长到一起(组织连在一块儿了)。在我们看来他可以抽象为一个无向图。其中有唯一结点是根。 
他们认为这是用来玩游戏的绝佳材料。于是他们打算在这棵树上玩伐木游戏，规则如下： 
1.两人轮流从灌木上截下枝条(图上的边)，每截下一根枝条就将与根不再相连的部分去掉。 
2.截去最后一根枝条的人获胜 
Alice 先手。 
对于给出的无向图输出输出胜利的人的名字。 
</div>

# Input

<div class="content">On the first line of the input file is the number B of bushes. B blocks of data follow, each of them describes one bush. 
Each block begins with two numbers N, M separated by whitespaces, where N is the number of vertices and M the number of edges of the respective bush. Descriptions of M edges follow. For each edge the input file contains the numbers of the vertices it connects. All these numbers are separated by whitespaces. 

</div>

# Output

<div class="content">For each block in the input file, output a single line containing the name of the player who will win the game on the given bush (e.g. either Alice or Bob). 

</div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
  <br/>
8 7<br/>
<br/>
1 2<br/>
1 3<br/>
3 4<br/>
1 5<br/>
5 6<br/>
6 7<br/>
7 8<br/>
<br/>
5 6<br/>
<br/>
1 2<br/>
1 3<br/>
3 2<br/>
1 4<br/>
5 1<br/>
4 5<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Alice<br/>
Bob<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

