# Division

**Time Limit: 10000/5000 MS (Java/Others)    Memory Limit: 999999/400000 K (Java/Others)Total Submission(s): 6004    Accepted Submission(s): 2382**

Problem Description

Little D is really interested in the theorem of sets recently. There’s a problem that confused him a long time.  
Let  T be a set of integers. Let the MIN be the minimum integer in T and MAX  be the maximum, then the cost of set T if defined as (MAX – MIN)^2. Now  given an integer set S, we want to find out M subsets S1, S2, …, SM of  S, such that

![img](http://acm.hdu.edu.cn/data/images/C295-1003-1.jpg)

and the total cost of each subset is minimal. 

 

Input

The input contains multiple test cases.
In  the first line of the input there’s an integer T which is the number of  test cases. Then the description of T test cases will be given. 
For  any test case, the first line contains two integers N (≤ 10,000) and M  (≤ 5,000). N is the number of elements in S (may be duplicated). M is  the number of subsets that we want to get. In the next line, there will  be N integers giving set S.



 

Output

For  each test case, output one line containing exactly one integer, the  minimal total cost. Take a look at the sample output for format.



 

Sample Input

```
2
3 2
1 2 4
4 2
4 7 10 1
```

 

Sample Output

```
Case 1: 1
Case 2: 18
```

 

```c++
#include<cstdio>
#include<algorithm>
#include<iostream>
using namespace std;
int cnt,cn,n,m,a[10005],f[10005],pre[10005],l,r;
pair<int,int> s[10005];
int cal(int k,int x,int y){
    return y-k*x;
}
int worse(int k,int xx1,int yy1,int xx2,int yy2){
    if(cal(k,xx1,yy1)>=cal(k,xx2,yy2)) return 1;
    return 0;
}
int cross(int xx1,int yy1,int xx2,int yy2,int xx3,int yy3){
    return (xx2-xx1)*(yy3-yy1)-(xx3-xx1)*(yy2-yy1);
}
int main()
{
    scanf("%d",&cnt);
    for(int cn=1;cn<=cnt;cn++)
    {
        printf("Case %d: ",cn);
        scanf("%d%d",&n,&m);
        for(int i=1;i<=n;i++)
            scanf("%d",&a[i]);
        sort(a+1,a+n+1);
        for(int i=1;i<=n;i++)
        f[i]=(a[i]-a[1])*(a[i]-a[1]);
        if(n<=m) return printf("0\n"),0;
           // for(int i=1;i<=n;printf("%d ",f[i]),i++);
        for(int j=2;j<=m;j++)
        {
            l=0;r=0;
            s[l]=make_pair(2*a[j],a[j]*a[j]);
            s[++r]=make_pair(2*a[j+1],f[j]+a[j+1]*a[j+1]);
            for(int i=j+1;i<=n;i++)
            {
            //printf("$%d %d %d %d\n",a[i],s[l].first,s[l].second,f[i]);
            while(l<r&&worse(a[i],s[l].first,s[l].second,s[l+1].first,s[l+1].second)) l++;
            while(l<r&&cross(s[r-1].first,s[r-1].second,2*a[i+1],f[i]+a[i+1]*a[i+1],s[r].first,s[r].second)>=0) r--;
            s[++r]=make_pair(2*a[i+1],f[i]+a[i+1]*a[i+1]);
            f[i]=cal(a[i],s[l].first,s[l].second)+a[i]*a[i];
            //printf("!%d %d %d %d\n",a[i],s[l].first,s[l].second,f[i]);
            }
            //for(int i=1;i<=n;printf("%d ",f[i]),i++);
        }
        printf("%d\n",f[n]);
    }
}	
```



斜率优化









# 开关问题

| **Time Limit:** 1000MS       |      | **Memory Limit:** 30000K |
| ---------------------------- | ---- | ------------------------ |
| **Total Submissions:** 10710 |      | **Accepted:** 4300       |

Description

有N个相同的开关，每个开关都与某些开关有着联系，每当你打开或者关闭某个开关的时候，其他的与此开关相关联的开关也会相应地发生变化，即这些相联系的开关的状态如果原来为开就变为关，如果为关就变为开。你的目标是经过若干次开关操作后使得最后N个开关达到一个特定的状态。对于任意一个开关，最多只能进行一次开关操作。你的任务是，计算有多少种可以达到指定状态的方法。（不计开关操作的顺序）

Input

输入第一行有一个数K，表示以下有K组测试数据。 
每组测试数据的格式如下： 
第一行 一个数N（0 < N < 29） 
第二行 N个0或者1的数，表示开始时N个开关状态。 
第三行 N个0或者1的数，表示操作结束后N个开关的状态。 
接下来 每行两个数I  J，表示如果操作第 I 个开关，第J个开关的状态也会变化。每组数据以 0 0 结束。 

Output

如果有可行方法，输出总数，否则输出“Oh,it's impossible~!!” 不包括引号

Sample Input

```
2
3
0 0 0
1 1 1
1 2
1 3
2 1
2 3
3 1
3 2
0 0
3
0 0 0
1 0 1
1 2
2 1
0 0
```

Sample Output

```
4
Oh,it's impossible~!!
```

Hint

第一组数据的说明： 
一共以下四种方法： 
操作开关1 
操作开关2 
操作开关3 
操作开关1、2、3 （不记顺序） 

```c++
#include<cstdio>
#include<iostream>
#include<algorithm>
using namespace std;
int n,a[1000],x,y;
pair<int,int> f[1000];
int gauss(){
	int sum=0,cnt=0,flag=1;
	for(int i=1;i<=n;i++){
		for(cnt=i;(f[cnt].first&(1<<(i-1)))==0&&cnt<=n;cnt++);
		if(cnt>n){ sum++; continue;}
		swap(f[i],f[cnt]);
		for(int j=1;j<=n;j++)
			if((j!=i)&&(f[j].first&(1<<(i-1))))
				f[j].first^=f[i].first,f[j].second^=f[i].second;
	}
	for(int i=1;i<=n;i++)
		if(f[i].first==0&&f[i].second!=0)
			return printf("Oh,it's impossible~!!\n"),1;
	return printf("%d\n",1<<sum);
}
int solve(){
	scanf("%d",&n);
	for(int i=1;i<=n;i++) scanf("%d",&a[i]);
	for(int i=1;i<=n;i++){
		scanf("%d",&x);
		f[i]=make_pair(1<<(i-1),(a[i]==x)?0:1);
	}
	while(scanf("%d%d",&x,&y)&&x&&y)f[y].first|=1<<(x-1);
	if(gauss()) return 0;
}
int main(){
	int cnt;
	scanf("%d",&cnt);
	while(cnt--){
		solve();
	}
}
```

Gauss





# Keywords Search

**Time Limit: 2000/1000 MS (Java/Others)    Memory Limit: 131072/131072 K (Java/Others)Total Submission(s): 79335    Accepted Submission(s): 27633**

In the modern time, Search engine came into the life of everybody like Google, Baidu, etc.
Wiskey also wants to bring this feature to his image retrieval system.
Every  image have a long description, when users type some keywords to find  the image, the system will match the keywords with description of image  and show the image which the most keywords be matched.
To simplify  the problem, giving you a description of image, and some keywords, you  should tell me how many keywords will be match.

 

Input

First line will contain one integer means how many cases will follow by.
Each case will contain two integers N means the number of keywords and N keywords follow. (N <= 10000)
Each keyword will only contains characters 'a'-'z', and the length will be not longer than 50.
The last line is the description, and the length will be not longer than 1000000.

 

Output

Print how many keywords are contained in the description.

 

Sample Input

```
1
5
she
he
say
shr
her
yasherhs
```

 

Sample Output

```
3
```

  

```c++
#include<iostream>
#include<cstdio>
#include<algorithm>
#include<cstring>
using namespace std;
const int N=500005;
const int CD= 26;
bool b[N];
int sz,ch[N][CD],val[N],fail[N],Q[N],ID[512];
char ss[N*2];
void Init(){
	fail[0]=0;
	for(int i=0;i<26;i++) ID[i+'a']=i;
}
void Reset(){
	memset(ch[0],0,sizeof(ch[0]));
	memset(b,0,sizeof(b));
	sz=1;
}
void Insert(char *a){
	int p=0;
	for(;*a;a++){
		int c=ID[*a];
		if(!ch[p][c])
		{
			memset(ch[sz],0,sizeof(ch[sz]));
			val[sz]=0;
			fail[sz]=0;
			ch[p][c]=sz++;
		}
		p=ch[p][c];
	}
	val[p]++;
}
void Construct(){
	int *s=Q,*e=Q;
	for(int i=0;i<CD;i++){
		if(ch[0][i]){
			fail[ch[0][i]]=0;
			*e++=ch[0][i];
		}
	}
	while(s!=e){
		int u=*s++;
		for(int i=0;i<CD;i++){
			int &v=ch[u][i];
			if(v){
				*e++=v;
				fail[v]=ch[fail[u]][i];
			}
			else
			{
				v=ch[fail[u]][i];
			}
		}
	}
}

int main()
{
	int ans,cnt,n;
	Init();
	scanf("%d",&cnt);
	while(cnt--)
	{
		Reset();
		scanf("%d",&n);
		for(int i=1;i<=n;i++)
		{
			scanf("%s",ss);
	//		printf("%s\n",ss);
			Insert(ss);
		}
		Construct();
		ans=0;
		scanf("%s",ss);
		int p=0,c;
		int len=strlen(ss);
		for(int i=0;i<len;i++)
		{
			c=ID[ss[i]];
			p=ch[p][c];
			for(int j=p;(!b[j])&&j;j=fail[j])
			{ ans+=val[j]; b[j]=1; val[j]=0;}
//			printf("%d %d\n",i,ans);
		}
		printf("%d\n",ans);
	}
}


```







## [A - LCM from 1 to n](https://vjudge.net/problem/LightOJ-1289)

​                         [LightOJ - 1289 ](https://vjudge.net/problem/26999/origin)                     

Given an integer **n**, you have to find

**lcm(1, 2, 3, ..., n)**

**lcm** means least common multiple. For example lcm(2, 5, 4) = 20, lcm(3, 9) = 9, lcm(6, 8, 12) = 24.

Input

Input starts with an integer **T (****≤ 10000)**, denoting the number of test cases.

Each case starts with a line containing an integer **n (2 ≤ n ≤ 108)**.

Output

For each case, print the case number and **lcm(1, 2, 3, ..., n)**. As the result can be very big, print the result modulo **232**.

Sample Input

5

10

5

200

15

20

Sample Output

Case 1: 2520

Case 2: 60

Case 3: 2300527488

Case 4: 360360

Case 5: 232792560



```c++
#pragma GCC optimize(3)
#pragma GCC optimize("Ofast")
#pragma GCC optimize(2)
#include<cstdio>
#include<algorithm>
using namespace std;
unsigned int b[4000000],p[6000000],ans,cnt,sum[6000000];
int last,n,top=0,flag;

int judge(int x)
{
    int y=n;int ans=0;
    while(p[x]<=y)
    {
        y=y/p[x];
        ans++;
    }
    return ans;
}
        

int find(int l,int r,int goal)
{
    int mid,ans;
    while(l<=r)
    {
        mid=(l+r)>>1;
        if(judge(mid)>=goal)
         l=mid+1,ans=mid;
        else
            r=mid-1;
    }
    return ans;
}

int main()
{
    for(int i=2;i<=100000000;i++)
    {
        if(!(b[i/30]&(1<<(i%30))))
            p[++top]=i;
        for(int j=1;j<=top;j++)
        {
            if(1ll*i*p[j]>100000000)break;
            b[i*p[j]/30]|=1<<(i*p[j]%30);
            if(i%p[j]==0) break;
        }
    }
    sum[0]=1;
    for(int i=1;i<=top;i++)
        sum[i]=1ll*sum[i-1]*p[i];
    scanf("%u",&cnt);
    for(int cn=1;cn<=cnt;cn++)
    {
        flag=cn&1;
        scanf("%d",&n);
        ans=1;
        last=0;
        for(int k=judge(1);k>=1;k--)
        {
            last=find(last,top,k);
            ans=1ll*ans*sum[last];
        }
        printf("Case %d: %u\n",cn,ans);
    }
}
```

数论









## [A - Co-prime](https://vjudge.net/problem/HDU-4135)

​                         [HDU - 4135 ](https://vjudge.net/problem/26104/origin)                     

   Given a number N, you are asked to count the number of integers between A and B inclusive which are relatively prime to N.   
Two integers are said to be co-prime or relatively prime if they  have no common positive divisors other than 1 or, equivalently, if their  greatest common divisor is 1. The number 1 is relatively prime to every  integer.  

Input

The first line on input contains T (0 < T <= 100) the  number of test cases, each of the next T lines contains three integers  A, B, N where (1 <= A <= B <= 10  15) and (1 <=N <= 10  9).

Output

For each test case, print the number of integers between A  and B inclusive which are relatively prime to N. Follow the output  format below.

Sample Input

```
2
1 10 2
3 15 5
```

Sample Output

```
Case #1: 5
Case #2: 10


        
  
```

Hint

```
In the first test case, the five integers in range [1,10] which are relatively prime to 2 are {1,3,5,7,9}. 
        
 
```

```c++
#include<stdio.h>
#include<algorithm>
#include<iostream>
#define int long long
using namespace std;
int cnt,x,y,z,ans;
int tops,top,b[100000],p[100000],f[100000],g[100000];
int pri()
{
    for(int i=2;i<=100000;i++)
    {
        if(!b[i])
            p[++tops]=i;
        for(int j=1;j<=tops;j++)
        {
            if(p[j]*i>100000) break;
            b[p[j]*i]=1;
            if(i%p[j]==0) break;
        }
    }
}
int fen(int x)
{
    for(int i=1;i<=tops;i++)
        if(x%p[i]==0)
        {
            g[++top]=p[i];
            while(x%p[i]==0)
                x=x/p[i];
        }
    if(x!=1)
        g[++top]=x;
}

int dfs(int x,int y,int z)
{
    f[z]+=y/ans;
    for(int i=x+1;i<=top;i++)
    {
        ans*=g[i];
        dfs(i,y,z+1);
        ans/=g[i];
    }
}
        
int work(int x,int y)
{
    ans=1;
    fill(f,f+top+1,0);
    dfs(0,x,0);
    //if(y<x)
    //   x++;
    for(int i=1;i<=top;i++)
    if(i&1)
        x-=f[i];
    else
        x+=f[i];
    return x;
}
 main()
{
    pri();
    scanf("%lld",&cnt);
    for(int cn=1;cn<=cnt;cn++)
    {
        scanf("%lld%lld%lld",&x,&y,&z);
        top=0;
        fen(z);
        printf("Case #%lld: %lld\n",cn,work(y,z)-work(x-1,z));
    }
}
```

容斥









## [B - "红色病毒"问题](https://vjudge.net/problem/HDU-2065)

​                         [HDU - 2065 ](https://vjudge.net/problem/23607/origin)                     

   医学界发现的新病毒因其蔓延速度和Internet上传播的"红色病毒"不相上下,被称为"红色病毒",经研究发现,该病毒及其变种的DNA的一条单链中,胞嘧啶,腺嘧啶均是成对出现的。   
 现在有一长度为N的字符串,满足一下条件:   
(1) 字符串仅由A,B,C,D四个字母组成;   
(2) A出现偶数次(也可以不出现);   
(3) C出现偶数次(也可以不出现);   
计算满足条件的字符串个数.   
当N=2时,所有满足条件的字符串有如下6个:BB,BD,DB,DD,AA,CC.   
由于这个数据肯能非常庞大,你只要给出最后两位数字即可.   
  

Input

每组输入的第一行是一个整数T,表示测试实例的个数,下面是T行数据,每行一个整数N(1<=N<2^64),当T=0时结束.  

Output

对于每个测试实例,输出字符串个数的最后两位,每组输出后跟一个空行.

Sample Input

```
4
1
4
20
11
3
14
24
6
0
```

Sample Output

```
Case 1: 2
Case 2: 72
Case 3: 32
Case 4: 0

Case 1: 56
Case 2: 72
Case 3: 56
```

```c++
#include<stdio.h>
#include<cstring>
#include<algorithm>
#include<iostream>
using namespace std;
int n,b[4];
long long m;
int a[4][4]={2,1,1,0,
             1,2,0,1,  
             1,0,2,1,
             0,1,1,2};
int c[4],d[4][4],e[4][4];
void che1()
{
    for(int i=0;i<=3;i++)
        for(int j=0;j<=3;j++)
            c[i]+=b[j]*e[j][i]%100;
    for(int i=0;i<=3;i++)
        b[i]=c[i]%100,c[i]=0;
}
void che()
{
    for(int i=0;i<=3;i++)
        for(int j=0;j<=3;j++)
            for(int k=0;k<=3;k++)
                d[i][j]+=e[i][k]*e[k][j]%100;
    for(int i=0;i<=3;i++)
        for(int j=0;j<=3;j++)
            e[i][j]=d[i][j]%100,d[i][j]=0;
}

void mi(long long x)
{
    while(x)
    {
        if(x&1)
            che1();
        x>>=1; che();
    }
}

int main()
{
    scanf("%d",&n);
    while(n)
    {
        for(int i=1;i<=n;i++)
        {
            printf("Case %d: ",i);
            scanf("%lld",&m);
            m--;
            b[0]=2; b[1]=1; b[2]=1; b[3]=0;
            for(int i=0;i<=3;i++) for(int j=0;j<=3;j++) e[i][j]=a[i][j];
            mi(m);
           // for(int i=0;i<=3;i++)
           ///     printf("!%d ",b[i]);
            printf("%d\n",b[0]);
        }
    printf("\n");
    scanf("%d",&n);
    }
}
```

矩阵乘法











## [A - 最大匹配](https://vjudge.net/problem/HDU-1083)

​                         [HDU - 1083 ](https://vjudge.net/problem/17609/origin)                     

   Consider a group of N students and P courses. Each student visits  zero, one or more than one courses. Your task is to determine whether it  is possible to form a committee of exactly P students that satisfies  simultaneously the conditions:   
   
. every student in the committee represents a different course (a student can represent a course if he/she visits that course)   
   
. each course has a representative in the committee   
   
Your program should read sets of data from a text file. The first  line of the input file contains the number of the data sets. Each data  set is presented in the following format:   
   
P N   
Count1 Student1 1 Student1 2 ... Student1 Count1   
Count2 Student2 1 Student2 2 ... Student2 Count2   
......   
CountP StudentP 1 StudentP 2 ... StudentP CountP   
   
The first line in each data set contains two positive integers  separated by one blank: P (1 <= P <= 100) - the number of courses  and N (1 <= N <= 300) - the number of students. The next P lines  describe in sequence of the courses . from course 1 to course P, each  line describing a course. The description of course i is a line that  starts with an integer Count i (0 <= Count i <= N) representing  the number of students visiting course i. Next, after a blank, you'll  find the Count i students, visiting the course, each two consecutive  separated by one blank. Students are numbered with the positive integers  from 1 to N.   
   
There are no blank lines between consecutive sets of data. Input data are correct.   
   
The result of the program is on the standard output. For each input  data set the program prints on a single line "YES" if it is possible to  form a committee and "NO" otherwise. There should not be any leading  blanks at the start of the line.   
   
An example of program input and output:  

Input

```
2
3 3
3 1 2 3
2 1 2
1 1
3 3
2 1 3
2 1 3
1 1
```

Output

```
YES
NO 
```

Sample Input

```
2
3 3
3 1 2 3
2 1 2
1 1
3 3
2 1 3
2 1 3
1 1
```

Sample Output

```
YES
NO 
```

```c++
#include<stdio.h>
#include<algorithm>
#include<vector>
using namespace std;
int cnt,n,m,num,x,mx[1000],my[1000],visy[1000];
vector<int> q[205];
int dfs(int s)
{
    for(auto t:q[s])
    if(!visy[t])
    {
        visy[t]=1;
        if(my[t]==-1||dfs(my[t]))
        {
            mx[s]=t;
            my[t]=s;
            return 1;
        }
    }
    return 0;
}
int max_match(int n,int m)
{
    fill(mx+1,mx+n+1,-1);
    fill(my+1,my+m+1,-1);
    int ret=0;
    for(int i=1;i<=n;i++)
    {
        fill(visy+1,visy+m+1,0);
        if(dfs(i))
            ret++;
    }
    return ret;
}
int main()
{
    scanf("%d",&cnt);
    for(int cn=1;cn<=cnt;cn++)
    {
        scanf("%d%d",&n,&m);
        for(int i=1;i<=n;i++)
        {
            //fill(q[i]+1,q[i]+sum[i]+1,0);
            scanf("%d",&num);
            q[i].clear();
            for(int j=1;j<=num;j++)
            {
            scanf("%d",&x);
            q[i].push_back(x);
            }
        }
        if(max_match(n,m)==n)
            printf("YES\n");
        else
            printf("NO\n");
    }
}

```

二分图









## [E - Tree](https://vjudge.net/problem/HDU-4757)

​                         [HDU - 4757 ](https://vjudge.net/problem/46759/origin)                     

Zero and One are good friends who always  have fun with each other. This time, they decide to do something on a  tree which is a kind of graph that there is only one path from node to  node. First, Zero will give One an tree and every node in this tree has a  value. Then, Zero will ask One a series of queries. Each query contains  three parameters: x, y, z which mean that he want to know the maximum  value produced by z xor each value on the path from node x to node y  (include node x, node y). Unfortunately, One has no idea in this  question. So he need you to solve it.  

Input

  There are several test cases and the cases end with EOF. For each case:  
  
  The first line contains two integers n(1<=n<=10^5) and  m(1<=m<=10^5), which are the amount of tree’s nodes and queries,  respectively.  
  
  The second line contains n integers a[1..n] and a[i](0<=a[i]<2^{16}) is the value on the ith node.  
  
  The next n–1 lines contains two integers u v, which means there is an connection between u and v.  
  
  The next m lines contains three integers x y z, which are the parameters of Zero’s query.  

Output

  For each query, output the answer.  

Sample Input

```
3 2
1 2 2
1 2
2 3
1 3 1
2 3 2
```

Sample Output

```
3
0
```

```c++
#include<stdio.h>
#include<algorithm>
#include<iostream>
#include<cstring>
#define MAXA 120010
using namespace std;
int first[MAXA],nxt[MAXA*2],go[MAXA*2],fa[MAXA][25],a[MAXA],deep[MAXA];
int son[MAXA*50][2],root[MAXA],sum[MAXA*50],n,m,x,y,z,faa,tot,top;;
void add(int x,int y){
    nxt[++top]=first[x]; first[x]=top; go[top]=y;}
int newnode(int x){
    tot++; memset(son[tot],0,sizeof(son[tot]));sum[tot]=x;return tot;}
int insert(int x,int val ,int dep){
    int rt=newnode(sum[x]+1);if(dep==-1) return rt;int v=(val>>dep)&1;
    son[rt][v^1]=son[x][v^1];son[rt][v]=insert(son[x][v],val,dep-1);
    return rt;}
void dfs(int x,int father){
    root[x]=insert(root[father],a[x],16);deep[x]=deep[father]+1;fa[x][0]=father;
    for(int i=1;i<=20;i++)fa[x][i]=fa[fa[x][i-1]][i-1];
    for(int i=first[x];i;i=nxt[i])if(go[i]!=father)dfs(go[i],x);}
int find(int x,int y){
    if(deep[x]<deep[y])swap(x,y);
    for(int i=20;i>=0;i--){
        if(deep[fa[x][i]]>=deep[y])x=fa[x][i];
        if(deep[x]==deep[y])break;}
    if(x==y)return x;
    for(int i=20;i>=0;i--) if(fa[x][i]!=fa[y][i])x=fa[x][i],y=fa[y][i];
    return fa[x][0];}
int work(int x,int y,int z,int num){
    int rt1=root[x]; int rt2=root[y]; int rt3=root[z]; int ans=0;
    int v=((num>>16)&1)^1; 
    if(sum[son[rt1][v]]+sum[son[rt2][v]]-2*sum[son[rt3][v]]<=0)  v^=1;
    rt1=son[rt1][v]; rt2=son[rt2][v];rt3=son[rt3][v];
    for(int i=15;;i--){
        ans|=v<<(i+1);  if(i==-1) break; v=((num>>i)&1)^1;
        if(sum[son[rt1][v]]+sum[son[rt2][v]]-2*sum[son[rt3][v]]<=0)  v^=1;
        rt1=son[rt1][v]; rt2=son[rt2][v];rt3=son[rt3][v];}
    return max(ans^num,a[z]^num);}
int main(){
    while(scanf("%d%d",&n,&m)!=EOF){
        tot=0; top=0;
        memset(first,0,sizeof(first));memset(sum,0,sizeof(sum));
        for(int i=1;i<=n;i++)scanf("%d",&a[i]);
        for(int i=1;i<n;i++){
            scanf("%d%d",&x,&y);
            add(x,y);add(y,x);}
        dfs(1,0);
        for(int i=1;i<=m;i++){
            scanf("%d%d%d",&x,&y,&z);faa=find(x,y);
            printf("%d\n",work(x,y,faa,z));}}}
```

字典树











## [L - Ilya and Escalator](https://vjudge.net/problem/CodeForces-518D)

​                         [CodeForces - 518D ](https://vjudge.net/problem/125219/origin)                     

Ilya got tired of sports programming, left university and got a  job in the subway. He was given the task to determine the escalator load  factor. 

Let's assume that *n* people stand  in the queue for the escalator. At each second one of the two following  possibilities takes place: either the first person in the queue enters  the escalator with probability *p*, or the first person in the queue doesn't move with probability (1 - *p*), paralyzed by his fear of escalators and making the whole queue wait behind him.

Formally speaking, the *i*-th person in the queue cannot enter the escalator until people with indices from 1 to *i* - 1  inclusive enter it. In one second only one person can enter the  escalator. The escalator is infinite, so if a person enters it, he never  leaves it, that is he will be standing on the escalator at any  following second. Ilya needs to count the expected value of the number  of people standing on the escalator after *t* seconds. 

Your task is to help him solve this complicated task.

Input

The first line of the input contains three numbers *n*, *p*, *t* (1 ≤ *n*, *t* ≤ 2000, 0 ≤ *p* ≤ 1). Numbers *n* and *t* are integers, number *p* is real, given with exactly two digits after the decimal point.

Output

Print a single real number — the expected number of people who will be standing on the escalator after *t* seconds. The absolute or relative error mustn't exceed 10 - 6.

Examples

​    Input   

```
1 0.50 1
```

​    Output   

```
0.5
```

​    Input   

```
1 0.50 4
```

​    Output   

```
0.9375
```

​    Input   

```
4 0.20 2
```

​    Output   

```
0.4
```

```c++
#include<stdio.h>
#include<iostream>
#include<algorithm>
using namespace std;
int n,t;
double ans,p,f[2005];
int main()
{
	scanf("%d%lf%d",&n,&p,&t);
	f[0]=1;
	for(int i=1;i<=t;i++)
	{
		f[n]=p*f[n-1]+f[n];
		for(int j=n-1;j>0;j--)
			f[j]=f[j]*(1-p)+p*f[j-1];;
		f[0]*=1-p;
	}
	for(int i=1;i<=n;i++)
		ans+=f[i]*i;
	printf("%lf",ans);
}
		
```

期望和概率











图和树算啦