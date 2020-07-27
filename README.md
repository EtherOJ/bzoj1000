
# Description

<div class="content">有一种很简单的压缩方式，用于表示连续的若干个相同的字符，例如aaaaa可以压缩成#a5。其中#表示下面的部分是压缩的，a是重复字符，5是重复次数。在这个问题里，字符集也用整数代替，从0到n-1；#也用0到n-1中的一个数表示，初始时都用0表示，但是可以变；重复次数也在0到n-1之间。也就是说原先的一个数列压缩以后，还是由0到n-1范围内的数构成的数列。
压缩的规定如下：
1.
除了#以外的所有数，都表示原本的字符。
2.
如果当前#用数e表示，e如果出现了，那么
a)
如果后面紧跟e k，那么说明编号为e的字符重复k+1次
b)
如果后面紧跟b 0，b不是e，说明从这里往后#用数b来表示
c)
如果后面紧跟b k，b不是e且k&gt;0，则表示编号为b的字符重复k+3次
例如当n=4时，原本的序列是1002222223333303020000，经过压缩后的一种表示方式是10010230320100302101。
给出一个压缩后的数列，求原数列的哪个压缩数列长度最小，并输出该压缩数列。
</div>

# Input

<div class="content">第一行是n，2&lt;=n&lt;=100000。
第二行是m，表示压缩数列的长度，1&lt;=m&lt;=2000000。
接下来的一行中有m个整数，都在0到n-1之间，表示一个压缩数列。
</div>

# Output

<div class="content">第一行输出同样表示原数列的最短压缩数列的长度。
</div>

# Sample Input

<div class="content"><span class="sampledata">输入1<br/>
4<br/>
20<br/>
1 0 0 1 0 2 3 0 3 2 0 1 0 0 3 0 2 1 0 1<br/>
输入2<br/>
14<br/>
15<br/>
10 10 10 0 10 0 10 10 13 10 10 13 10 10 13<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">输出1<br/>
19<br/>
<br/>
输出2<br/>
9<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

