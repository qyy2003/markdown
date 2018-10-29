# 2018 Multi-University Training Contest 1
http://acm.hdu.edu.cn/search.php?field=problem&key=2018+Multi-University+Training+Contest+1&source=1&searchmode=source































## 解题报告

### QYY























# Maximum Multiple

**Time Limit: 4000/2000 MS (Java/Others)    Memory Limit: 32768/32768 K (Java/Others)
Total Submission(s): 3735    Accepted Submission(s): 1526**



#### Problem Description

Given an integer $n​$, Chiaki would like to find three positive integers $x​$, $y​$ and $z​$ such that: $n=x+y+z​$, $x\mid n​$, $y \mid n​$, $z \mid n​$ and $xyz​$ is maximum.

#### Input

There are multiple test cases. The first line of input contains an integer $T$ ($1 \le T \le 10^6$), indicating the number of test cases. For each test case:
The first line contains an integer $n$ ($1 \le n \le 10^{6}$).


#### Output
For each test case, output an integer denoting the maximum $xyz$. If there no such integers, output $-1$ instead.


#### Sample Input

```
3
1
2
3
```


#### Sample Output

```
-1
-1
1
```



---



### TRY1

考虑存一下$(X+Y,X*Y)$的合法情况，然后逐个遍历

```c++
#include<cstdio>
#include<algorithm>
#include<map>
using namespace std;
int n,m;
int ans=0;
map<pair<int,int>,bool> ma;
int main(){
    m=1e6;
    for(int i=2;i<=1000;i++)
	for(int j=1;j<=m/i;j++)
	   ma[make_pair(i+j,i*j)]=1;
}
```

HOWEVER

```
real	0m11.516s
user	0m11.200s
sys	0m0.224s
```

好快!...

```c++
#include<cstdio>
#include<algorithm>
#include<map>
using namespace std;
int n,m;
int ans=0;
map<long long,bool> ma;
int main(){
    m=1e6;
    for(int i=2;i<=1000;i++)
	for(int j=1;j<=m/i;j++)
	   ma[1ll*(i+j)*m+1ll*i*j]=1;
}
```

优化一波

```
real	0m9.057s
user	0m8.778s
sys	0m0.260s
```

还是挂挂

```c++
#include<cstdio>
#include<algorithm>
#include<map>
using namespace std;
int n,M;
vector<int> q[1000005];
int main(){
    M=1e6;
    for(int i=2;i<=1000;i++)
	for(int j=1;j<=M/i;j++)
	  q[i*j].push_back(i+j);
}
```

向vector求助

```
real	0m9.083s
user	0m8.729s
sys	0m0.304s
```

这......

忽然发现要push_back6485017次。。。

弃疗





# Balanced Sequence

**Time Limit: 2000/1000 MS (Java/Others)    Memory Limit: 32768/32768 K (Java/Others)Total Submission(s): 6531    Accepted Submission(s): 1718**



#### Problem Description

Chiaki has $n$ strings $s_1,s_2,\dots,s_n$ consisting of '(' and ')'. A string of this type is said to be balanced:

+ if it is the empty string
+ if $A$ and $B$ are balanced, $AB$ is balanced,
+ if $A$ is balanced, $(A)$ is balanced.

Chiaki can reorder the strings and then concatenate them get a new string $t$. Let $f(t)$ be the length of the longest balanced subsequence (not necessary continuous) of $t$. Chiaki would like to know the maximum value of $f(t)$ for all possible $t$.

#### Input

There are multiple test cases. The first line of input contains an integer $T$, indicating the number of test cases. For each test case:
The first line contains an integer $n$ ($1 \le n \le 10^5$) -- the number of strings.
Each of the next $n$ lines contains a string $s_i$ ($1 \le |s_i| \le 10^5$) consisting of `(' and `)'.
It is guaranteed that the sum of all $|s_i|$ does not exceeds $5 \times 10^6$.

#### Output

For each test case, output an integer denoting the answer.

#### Sample Input

```
2
1
)()(()(
2
)
)(
```

 

#### Sample Output

```
4
2
```

 











# Triangle Partition

**Time Limit: 2000/1000 MS (Java/Others)    Memory Limit: 132768/132768 K (Java/Others)Total Submission(s): 2698    Accepted Submission(s): 1363Special Judge**



#### Problem Description

Chiaki has $3n$ points $p_1,p_2,\dots,p_{3n}$. It is guaranteed that no three points are collinear.
Chiaki would like to construct $n$ disjoint triangles where each vertex comes from the $3n$ points.

 

#### Input

There  are multiple test cases. The first line of input contains an integer  $T$, indicating the number of test cases. For each test case:
The first line contains an integer $n$ ($1 \le n \le 1000$) -- the number of triangle to construct.
Each of the next $3n$ lines contains two integers $x_i$ and $y_i$ ($-10^9 \le x_i, y_i \le 10^9$).
It is guaranteed that the sum of all $n$ does not exceed $10000$.

 

#### Output

For  each test case, output $n$ lines contain three integers $a_i,b_i,c_i$  ($1 \le a_i,b_i,c_i \le 3n$) each denoting the indices of points the  $i$-th triangle use. If there are multiple solutions, you can output any  of them.

 

#### Sample Input

```
1
1
1 2
2 3
3 5
```

 

#### Sample Output

```
1 2 3
```

 

 







# Distinct Values

**Time Limit: 4000/2000 MS (Java/Others)    Memory Limit: 32768/32768 K (Java/Others)Total Submission(s): 5115    Accepted Submission(s): 1759**



#### Problem Description

Chiaki  has an array of $n$ positive integers. You are told some facts about  the array: for every two elements $a_i$ and $a_j$ in the subarray  $a_{l..r}$ ($l \le i < j \le r$), $a_i \ne a_j$ holds.
Chiaki would like to find a lexicographically minimal array which meets the facts.

 

#### Input

There  are multiple test cases. The first line of input contains an integer  $T$, indicating the number of test cases. For each test case:

The  first line contains two integers $n$ and $m$ ($1 \le n, m \le 10^5$) --  the length of the array and the number of facts. Each of the next $m$  lines contains two integers $l_i$ and $r_i$ ($1 \le l_i \le r_i \le n$).

It is guaranteed that neither the sum of all $n$ nor the sum of all $m$ exceeds $10^6$.

 

#### Output

For  each test case, output $n$ integers denoting the lexicographically  minimal array. Integers should be separated by a single space, and no  extra spaces are allowed  at the end of lines.

 

#### Sample Input

```
3
2 1
1 2
4 2
1 2
3 4
5 2
1 3
2 4
```

 

#### Sample Output

```
1 2
1 2 1 2
1 2 3 1 1
```

 















# Maximum Weighted Matching

**Time Limit: 8000/4000 MS (Java/Others)    Memory Limit: 65535/65535 K (Java/Others)Total Submission(s): 181    Accepted Submission(s): 35**



#### Problem Description

Chiaki  is good at generating special graphs. Initially, she has a graph with  only two vertices connected by an edge. Each time, she can choose an  edge $(u,v)$, make a copy of it, insert some new vertices (maybe zero)  in the edge (i.e. let the new vertices be $t_1,t_2,\dots,t_k$, Chiaki  would insert edges $(u,t_1)$, $(t_1,t_2)$,  $(t_{k-1}, t_k)$, $(t_k, v)$  into the graph).
Given a weighted graph generated by above  operations, Chiaki would like to know the maximum weighted matching of  the graph and the number different maximum weighted matchings modulo  ($10^9 + 7)$).
A matching in a graph is a set of pairwise  non-adjacent edges, none of which are loops; that is, no two edges share  a common vertex.
A maximum weighted matching is defined as a  matching where the sum of the values of the edges in the matching have a  maximal value.

 

#### Input

There  are multiple test cases. The first line of input contains an integer  $T$, indicating the number of test cases. For each test case:
The first line contains two integers $n$ and $m$ ($1 \le n, m \le 10^5$) -- the number of vertices and the number of edges.
Each  of the next $m$ lines contains three integers $u_i$, $v_i$ and $w_i$  ($1 \le u_i, v_i \le n, 1 \le w_i \le 10^9$) -- deonting  an edge  between $u_i$ and $v_i$ with weight $w_i$.
It is guaranteed that neither the sum of all $n$ nor the sum of all $m$ exceeds $10^6$.

 

#### Output

For  each test case, output two integers separated by a single space. The  first one is the sum of weight and the second one is the number of  different maximum weighted matchings modulo ($10^9 + 7$).

 

#### Sample Input

```
2
6 7
1 2 1
2 3 1
4 5 1
5 6 1
1 4 1
2 5 1
3 6 1
4 5
1 2 1
1 3 1
1 4 1
2 3 1
3 4 1
```

 

#### Sample Output

```
3 3
2 2
```







# Period Sequence

**Time Limit: 12000/6000 MS (Java/Others)    Memory Limit: 65535/65535 K (Java/Others)Total Submission(s): 156    Accepted Submission(s): 56**



#### Problem Description

Chiaki  has $n$ integers $s_0,s_1,\dots,s_{n-1}$. She has defined an infinite  sequence $S$ in the following way: $S_k = s_{k \bmod n} + n \cdot  \lfloor \frac{k}{n} \rfloor$, where $k$ is a zero based index.

For  a continuous subsequence $S[l..r]$, let $cnt_x$ be the number of  occurrence of $x$ in the subsequence $S[l..r]$. Then the value of  $S[l..r]$ is defined as follows $$f(l,r)=\sum\limits_{x}x \cdot  cnt^2_x$$

For two integers $a$ and $b$ ($a \le b$), Chiaki would  like to find the value of $$(\sum\limits_{a \le l \le r \le b} f(l,r))  \bmod (10^9+7)$$

 

#### Input

There  are multiple test cases. The first line of input contains an integer  $T$, indicating the number of test cases. For each test case:
The first line contains three integers $n$, $a$ and $b$ ($1 \le n \le 2000, 0 \le a \le b \le 10^{18}$).
The second line contains $n$ integers $s_0,s_1,\dots,s_{n-1}$ ($0 \le s_i \le 10^9$).
It is guaranteed that the sum of all $n$ does not exceed $20000$.

 

#### Output

For each test case, output an integer denoting the answer.

 

#### Sample Input

```
4
3 2 6
2 1 3
5 2 7
2 1 5 1 2
4 4 8
2 1 5 17
3 5 9
2 5 2
```

#### Sample Output

```
179
268
369
437
```

 









# Chiaki Sequence Revisited

**Time Limit: 2000/1000 MS (Java/Others)    Memory Limit: 32768/32768 K (Java/Others)Total Submission(s): 3235    Accepted Submission(s): 961**



#### Problem Description

Chiaki is interested in an infinite sequence $a_1, a_2, a_3, ...$, which is defined as follows: 
$$a_n=\begin{cases}1 & n = 1,2 \\ a_{n - a_{n-1}} + a_{n-1 - a_{n-2}} & n \ge 3\end{cases}$$
Chiaki  would like to know the sum of the first $n$ terms of the sequence, i.e.  $\sum\limits_{i=1}^{n}a_i$. As this number may be very large, Chiaki is  only interested in its remainder modulo ($10^9 + 7$).

 

#### Input

There  are multiple test cases. The first line of input contains an integer  $T$ ($1 \le T \le 10^5$), indicating the number of test cases. For each  test case:
The first line contains an integer $n$ ($1 \le n \le 10^{18}$).

 

#### Output

For each test case, output an integer denoting the answer.



 #### Sample Input

```
10
1
2
3
4
5
6
7
8
9
10
```

 

#### Sample Output

```
1
2
4
6
9
13
17
21
26
32
```

 









# RMQ Similar Sequence

**Time Limit: 4000/2000 MS (Java/Others)    Memory Limit: 255535/255535 K (Java/Others)Total Submission(s): 1624    Accepted Submission(s): 565**



#### Problem Description

Chiaki  has a sequence $A=\{a_1,a_2,\dots,a_n\}$. Let $\mathbf{RMQ}(A, l, r)$  be the minimum $i$ ($l \le i \le r$) such that $a_i$ is the maximum  value in $a_l, a_{l+1}, \dots, a_{r}$.

Two sequences $A$ and $B$  are called \textit{RMQ Similar}, if they have the same length $n$ and  for every $1 \le l \le r \le n$, $\mathbf{RMQ}(A, l, r) =  \mathbf{RMQ}(B, l, r)$.

For a given the sequence  $A=\{a_1,a_2,\dots,a_n\}$, define the weight of a sequence  $B=\{b_1,b_2,\dots,b_n\}$ be $\sum\limits_{i=1}^{n} b_i$ (i.e. the sum  of all elements in $B$) if sequence $B$ and sequence $A$ are RMQ  Similar, or $0$ otherwise. If each element of $B$ is a real number  chosen independently and uniformly at random between $0$ and $1$, find  the expected weight of $B$.

 

#### Input

There  are multiple test cases. The first line of input contains an integer  $T$, indicating the number of test cases. For each test case:
The first line contains an integer $n$ ($1 \le n \le 10^6$) -- the length of the sequence.
The second line contains $n$ integers $a_1, a_2, \dots, a_n$ ($1 \le a_i \le n$) denoting the sequence.
It is guaranteed that the sum of all n does not exceed $3 \times 10^6$.

 

#### #### Output

For each test case, output the answer as a value of a rational number modulo $10^9 + 7$.
Formally,  it is guaranteed that under given constraints the probability is always  a rational number $\frac{p}{q}$ ($p$ and $q$ are integer and coprime,  $q$ is positive), such that $q$ is not divisible by $10^9 + 7$. Output  such integer a between $0$ and $10^9 + 6$ that $p - aq$ is divisible by  $10^9 + 7$.

 

#### Sample Input

```
3
3
1 2 3
3
1 2 1
5
1 2 3 2 1
```

 

#### Sample Output

```
250000002
500000004
125000001
```











# Lyndon Substring

**Time Limit: 6000/3000 MS (Java/Others)    Memory Limit: 65535/65535 K (Java/Others)Total Submission(s): 182    Accepted Submission(s): 17**



#### Problem Description

A string $w$ is said to be a Lyndon word if $w$ is lexicographically smaller than any of its cyclic rotations. 
The longest Lyndon substring of a string $s$ is the longest substring of $s$ which is a Lyndon word.
Chiaki  has $n$ strings $s_1,s_2,\dots,s_n$. She has some queries: for some  pair $(i,j)$, find the length of the longest Lyndon substring of string  $s_is_j$.

 

#### Input

There  are multiple test cases. The first line of input contains an integer  $T$, indicating the number of test cases. For each test case:
The first line contains two integers $n$ and $m$ $(1 \le n, m \le 10^5)$ -- the number of strings and the number of queries.
Each of the next $n$ lines contains a nonempty string $s_i$ $(1 \le s_i \le 10^5)$ consisting of lowercase English letters.
Each of the next $m$ lines contains two integers $i$ and $j$ ($1 \le i, j \le n$) denoting a query.
It  is guaranteed that in one test case the sum of all $|s|$ does not  exceed $5 \times 10^5$ and that in all cases the sum of all $|s|$ does  not exceed $5 \times 10^6$.
It is guaranteed that neither the sum of all $n$ nor the sum of all $m$ exceeds $10^6$.

 

#### Output

For each query, output an integer denoting the answer.

 

#### Sample Input

```
1
2 1
aa
bb
1 2
```

 

#### Sample Output

```
4
```











# Turn Off The Light

**Time Limit: 4000/2000 MS (Java/Others)    Memory Limit: 32768/32768 K (Java/Others)Total Submission(s): 191    Accepted Submission(s): 6**



#### Problem Description

There  are $n$ lights aligned in a row. These lights are numbered $1$ to $n$  from left to right. Initially some of the lights are turned on. Chiaki  would like to turn off all the lights.
Chiaki starts from the $p$-th  light. Each time she can go left or right (i.e. if Chiaki is at $x$,  then she can go to $x-1$ or $x+1$) and then press the switch of the  light in that position (i.e. if the light is turned on before, it will  be turned off and vise versa).
For each $p=1,2,\dots,n$, Chiaki would like to know the minimum steps needed to turn off all the lights.

 

#### Input

There are multiple test cases. The first line of input is an integer $T$ indicates the number of test cases. For each test case:
The first line contains an integer $n$ ($2 \le n \le 10^6$) -- the number of lights.
The  second line contains a binary string $s$ where $s_i=1$ means the $i$-th  light is turned on and $s_i=0$ means $i$-th light is turned off.
It is guaranteed that the sum of all $n$ does not exceed $10^7$.

 

#### Output

For  each test cases, output $(\sum\limits_{i=1}^{|s|} i \times z_i) \bmod  (10^9+7)$, where $z_i$ is the number of step needed when Chikai starts  at the $i$-th light.

 

#### Sample Input

```
3
3
000
3
111
8
01010101
```

 

#### Sample Output

```
0
26
432
```

 









# Time Zone

**Time Limit: 2000/1000 MS (Java/Others)    Memory Limit: 32768/32768 K (Java/Others)Total Submission(s): 4619    Accepted Submission(s): 1349**



#### Problem Description

Chiaki often participates in international competitive programming contests. The time zone becomes a big problem.
Given a time in Beijing time (UTC +8), Chiaki would like to know the time in another time zone $s$.

 

#### Input

There  are multiple test cases. The first line of input contains an integer  $T$ ($1 \le T \le 10^6$), indicating the number of test cases. For each  test case:
The first line contains two integers $a$, $b$ ($0 \le a  \le 23, 0 \le b \le 59$) and a string $s$ in the format of "UTC+X'',  "UTC-X'', "UTC+X.Y'', or "UTC-X.Y'' ($0 \le X, X.Y \le 14, 0 \le Y \le  9$).

 

#### Output

For each test, output the time in the format of $hh:mm$ (24-hour clock).

 

#### Sample Input

```
3
11 11 UTC+8
11 12 UTC+9
11 23 UTC+0
```

 

#### Sample Output

```
11:11
12:12
03:23
```











# END

### QYY





##### Copyright(c) qyy.   