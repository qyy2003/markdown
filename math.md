MATH

---


45、对集合{1，2，…，n}及其每一个非空子集，定义一个唯一确定的“交替和”如下：按照递减的次序重新排列该子集，然后交替地减或加后继的数所得的结果，例如，集合{1,2,4,6,9}的“交替和”是9-6+4-2+1=6. {5,6}的“交替和”是6-5=1，{2}的交替和是2。那么，对于n=7。求所有子集的“交替和”的总和。

解析：$n*2^{n-1}$

最大的那个取和不取正好抵消

答案：**448**

---

46、将与105互素的所有正整数，从小到大排成一个数列，试求出该数的第1000项．

解析：

由105=3×5×7，
由容斥原理，每连续105个数中，
有105-（1053+1055+1057）+105/3×5+105/5×7+105/3×7−105/3×5×7
=105×（1-13）（1-15）（1-17）=48，
故不超过105而与105互质的正整数有48个．
1000=48×20+48-8，
105×20=2100．
自105向前倒数，第9个与105互素的数是86，
∴在不超过105的与105互质的数中第40个数是86．
∴所求数为2100+86=2186．
故这个数列的第1000项是2186．

答案：****

---

47、对于任何的集合S，记|S|为集合的元素个数，记n（S）为集合S的子集个数，若A，B，C是三个集合，满足：n(A)+n(B)+n(C)=n(A∪B∪C)。|A|=|B|=100。求|A∩B∩C|的最小值。

解析：$2^{100}+2^{100}+2^X=2^Y$

$x=101,y=102$

所以有一个

答案：**97**

---
