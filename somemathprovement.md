##### 在一条长度为1 的线段上随机取两个点，则以这两个点为端点的线段的期望长度是（ ）

ans=(sigma(1,n)sigma(i+1,n)(j-i)/n)/(n(n+1)/2)
=(sigma(1,n) (n-i+1)(n-i) )/((n^2)(n+1)/2)
=(n^3+n^2-(2n+1)(sigma(1,n)i)+sigma(1,n) i^2)/((n^2)(n+1)/2)
=1-((2n+1)(sigma(1,n)i)-(sigma(1,n)i^2)/((n^2)(n+1))
=1-((2n+1)(n)(n+1)/2-(2n+1)(n)(n+1)/6)/(n^2(n+1))
=1-(2n+1)/3n

as n be inf
ans = 1/3