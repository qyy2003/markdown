

# **NOIP初赛**



---



---



---



---



标签 ： OI 

---
内部资料，不可外（wai第四声,重音在前）传...

---

本文链接http://noip.zjqyy.top/

qyy日更

pdf http://noip.zjqyy.top/NOIP.pdf

---

---

# 前言

---

QYY对初赛很是不放心，因为qyy太菜了
为巩固初赛，qyy作此文以方便复习

---

---

---



# 错题锦集

---

## 计算机基础知识

1、若一台计算机的字长为32位，则表明该机器（）。
A、能处理的数值最大为4位十进制数
B、能处理的数值最多为4个字节
C、在CPU中能够作为一个整数加以处理的二进制数据为4个字节
D、在CPU中运算的结果最大为2^32

解析：无

答案:**D**

---

1、关于CPU下面哪些说法是正确的：
A)CPU全称为中央处理器（或中央处理单元）。
B)CPU能直接运行机器语言。
C)CPU最早是由Intel公司发明的。
D)同样主频下，32位的CPU比16位的CPU运行速度快一倍。

解析：D不一定

答案:**AB**

---

9、排序算法是稳定的意思是关键码相同的记录排序前后相对位置不发生改变，下列哪些排序算法是稳定的：
A) 插入排序     B) 基数排序     C) 归并排序     D)  冒泡排序

解析：C是稳定的

答案:**ABCD**

---

5、关于HTML下面哪些说法是正确的：
A)HTML全称超文本标记语言，实现了文本、图形、声音乃至视频信息的统一编码。
B)HTML不单包含有网页内容信息的描述，同时也包含对网页格式信息的定义。
C)网页上的超链接只能指向外部的网络资源，本网站网页间的联系通过设置标签来实现。
D)点击网页上的超链接从本质上就是按照该链接所隐含的统一资源定位符（URL）请求网络资源或网络服务。

解析：然而A并没有

答案:**BD**

---

143、汉字输入码可分为有重码和无重码两类，下列属于无重码类的是______。
A)全拼码 B)自然码
C)区位码 D)简拼码

解析：

答案:**C**

---

***144***、已知汉字"家"的区位码是2850，则其国标码是_______。
A)4870D   B)3C52H
C)9CB2H  D)A8D0H

解析：

5442H

答案:**C**???

---

189、关于网络体系结构，以下哪种描述是错误的?   （  ）
A、物理层完成比特流的传输 
B、数据链路层用于保证端到端数据的正确传输 
C、网络层为分组通过通信子网选择适合的传输路径 
D、应用层处于参考模型的最高层 

解析：数据链路层为分组通过通信子网选择适合的传输路径 

答案:**B**

---

190、在TCP／IP体系结构中，TCP和IP所提供的服务层次分别为   （  ）
A．应用层和运输层    B．运输层和网络层 
C.网络层和链路层    D．链路层和物理层

解析：

 **数据链路层**在物理**层**提供的服务的基础上向网络**层**提供服务，其最基本的服务是将源自网络**层**来的**数据**可靠地传输到相邻节点的目标机网络**层**。

答案:**D**

---

192、在一座大楼内组建的一个计算机网络系统，属于（    ）。
A. WAN     B. LAN      C. MAN     D. PAN

解析：

答案:**B**

---

193、计算机网络通信的一个显著特点是（  ）。
 A、稳定性      B、间歇性、突发性  C、安全性   D、易用性

解析：

答案:**B**

---

194、网络按通信方式分类，可分为（ ）和（ ）。  
A. 点对点传输网络 　　　B. 广播式传输网络　
C. 数据传输网络 　　    D. 对等式网络

解析：

答案:**AB**

---

195、UDP 协议是（）                                         
A．可靠的无连接协议		B．不可靠的无连接协议
C．可靠的连接协议		D．不可靠的连接协议

解析：

UDP使用简单的无[连接通信](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Connectionless_communication&xid=17259,15700019,15700124,15700149,15700186,15700191,15700201,15700214&usg=ALkJrhjLw8rhCBGyqZSufkT27SbmX7zQQA)模型，并且协议机制最少。  UDP提供数据完整性的[校验和](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Checksum&xid=17259,15700019,15700124,15700149,15700186,15700191,15700201,15700214&usg=ALkJrhjtHok_MypkWNl9hbB-WVx6t9APQQ) ，以及用于在数据报的源和目标处寻址不同功能的[端口号](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Port_numbers&xid=17259,15700019,15700124,15700149,15700186,15700191,15700201,15700214&usg=ALkJrhgOx8Scwza5HbtyU5idmgD0z0YNPw) 。 它没有[握手](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Handshaking&xid=17259,15700019,15700124,15700149,15700186,15700191,15700201,15700214&usg=ALkJrhjuSpOegliByOrXoNJCTzh2hdtNIw)对话，因此使用户的程序暴露于底层网络的任何[不可靠性](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Reliability_(computer_networking)&xid=17259,15700019,15700124,15700149,15700186,15700191,15700201,15700214&usg=ALkJrhjuQjwryE1KXBztpNvKkDrOB5yFgA) ; 不保证交付，订购或重复保护。 如果在网络接口级需要纠错设施，则应用可以使用为此目的而设计的[传输控制协议](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Transmission_Control_Protocol&xid=17259,15700019,15700124,15700149,15700186,15700191,15700201,15700214&usg=ALkJrhhmLnfR0VxkCYzA7dfDfjvRDwwFKQ) （TCP）或[流控制传输协议](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Stream_Control_Transmission_Protocol&xid=17259,15700019,15700124,15700149,15700186,15700191,15700201,15700214&usg=ALkJrhh6h0NKvFhQ8dbiiqAaDS-fTBKmWg) （SCTP）。

答案:**B**

---

196、通常所说的TCP/IP是指　(  )                         
A. TCP 和　IP    B. 传输控制协议　  　Ｃ.　互联网协议
Ｄ.　IP ARP ICMP IGMP TCP UDP等多种协议的集合

解析：

**网际网路协议**（英语：Internet Protocol Suite，缩写IPS）[[1\]](https://zh.wikipedia.org/w/index.php?title=TCP/IP%E5%8D%8F%E8%AE%AE%E6%97%8F&variant=zh-hans&gettingStartedReturn=true#cite_note-1)是一个网路通讯模型，以及一整个[网络传输协议](https://zh.wikipedia.org/wiki/%E7%BD%91%E7%BB%9C%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)家族，为[网际网路](https://zh.wikipedia.org/wiki/%E7%B6%B2%E9%9A%9B%E7%B6%B2%E8%B7%AF)的基础通讯架构。它常被通称为**TCP/IP协议族**（英语：TCP/IP Protocol Suite，或TCP/IP Protocols），简称**TCP/IP**[[2\]](https://zh.wikipedia.org/w/index.php?title=TCP/IP%E5%8D%8F%E8%AE%AE%E6%97%8F&variant=zh-hans&gettingStartedReturn=true#cite_note-2)。因为该协定家族的两个核心协定：TCP（[传输控制协议](https://zh.wikipedia.org/wiki/%E4%BC%A0%E8%BE%93%E6%8E%A7%E5%88%B6%E5%8D%8F%E8%AE%AE)）和IP（[网际协议](https://zh.wikipedia.org/wiki/%E7%BD%91%E9%99%85%E5%8D%8F%E8%AE%AE)），为该家族中最早通过的标准[[3\]](https://zh.wikipedia.org/w/index.php?title=TCP/IP%E5%8D%8F%E8%AE%AE%E6%97%8F&variant=zh-hans&gettingStartedReturn=true#cite_note-3)。由于在网络通讯协议普遍采用分层的结构，当多个层次的协议共同工作时，类似计算机科学中的[堆栈](https://zh.wikipedia.org/wiki/%E5%A0%86%E6%A0%88)，因此又被称为**TCP/IP协议栈**（英语：TCP/IP Protocol Stack）[[4\]](https://zh.wikipedia.org/w/index.php?title=TCP/IP%E5%8D%8F%E8%AE%AE%E6%97%8F&variant=zh-hans&gettingStartedReturn=true#cite_note-4)[[5\]](https://zh.wikipedia.org/w/index.php?title=TCP/IP%E5%8D%8F%E8%AE%AE%E6%97%8F&variant=zh-hans&gettingStartedReturn=true#cite_note-5)  。这些协议最早发源于[美国国防部](https://zh.wikipedia.org/wiki/%E7%BE%8E%E5%9B%BD%E5%9B%BD%E9%98%B2%E9%83%A8)（缩写为DoD）的[ARPA网](https://zh.wikipedia.org/wiki/ARPA%E7%BD%91)项目，因此也被称作**DoD模型**（DoD Model）[[6\]](https://zh.wikipedia.org/w/index.php?title=TCP/IP%E5%8D%8F%E8%AE%AE%E6%97%8F&variant=zh-hans&gettingStartedReturn=true#cite_note-6)。这个协定套组由[互联网工程任务组](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E5%B7%A5%E7%A8%8B%E4%BB%BB%E5%8A%A1%E7%BB%84)负责维护。

答案:**D**

---

197、缩写CERNET表示中国( )计算机网。                
A.教育科研    B.经济    C.农业    D.工业

解析：

中国教育和科研计算机网（简称中国教育网或教育网，英语：China Education and Research Network，缩写：**CERNET**）始建于1994年，是全球最大的学术互联网，也是中国最大的学术计算机互联网络，还是中国四大骨干网之一。 中国教育网由中国教育部投资并管理，清华大学等高校承担建设和运行。

答案:**A**

---

198、浏览WWW使用的地址称为URL，URL是指        。        
A.IP地址    B.主页   C.主机域名    D.统一资源定位符

解析：

**统一资源定位符**（或称**统一资源定位器**/**定位地址**、**URL地址**等[[1\]](https://zh.wikipedia.org/zh-hans/%E7%BB%9F%E4%B8%80%E8%B5%84%E6%BA%90%E5%AE%9A%E4%BD%8D%E7%AC%A6#cite_note-1)，英语：Uniform Resource Locator，常缩写为**URL**），有时也被俗称为**网页地址**（**网址**）。如同在网路上的门牌，是[因特网](https://zh.wikipedia.org/wiki/%E5%9B%A0%E7%89%B9%E7%BD%91)上标准的资源的地址（Address）。它最初是由[蒂姆·伯纳斯-李](https://zh.wikipedia.org/wiki/%E8%92%82%E5%A7%86%C2%B7%E4%BC%AF%E7%BA%B3%E6%96%AF-%E6%9D%8E)发明用来作为[万维网](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91)的地址。现在它已经被[万维网联盟](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91%E8%81%94%E7%9B%9F)编制为因特网标准 [RFC 1738](https://tools.ietf.org/html/rfc1738)。 

在网际网路的历史上，统一资源定位符的发明是一个非常基础的步骤。统一资源定位符的语法是一般的，可扩展的，它使用[ASCII](https://zh.wikipedia.org/wiki/ASCII)代码的一部分来表示因特网的地址。统一资源定位符的开始，一般会标志着一个计算机网络所使用的网络协议。 

统一资源定位符的标准格式如下：  

> **协议类型:**[**//服务器地址**[**:端口号**]][**/资源层级UNIX文件路径**]文件名[?**查询**][#**片段ID**]

统一资源定位符的完整格式如下：  

> **协议类型:**[**//**[**访问资源需要的凭证信息@**]**服务器地址**[**:端口号**]][**/资源层级UNIX文件路径**]文件名[?**查询**][#**片段ID**]

其中【访问凭证信息@  :端口号  ?查询  #片段ID】都属于选填项。 



答案:**D**

---

199、域名http://www.njupt.edu.cn/由4个子域组成,其中哪个表示主机名 .( )  
A,www B,njupt C,edu D,cn

解析：?!!!

答案:**A**

---

200、一条TCP连接的建立过程包括(     )个步骤，释放过程包括(  )个步骤。
A.   2           B.   3        C.   4         D.   5

解析：

TCP协议的运行可划分为三个阶段：连接创建(*connection establishment*)、数据传送（*data transfer*）和连接终止（*connection termination*）。操作系统将TCP连接抽象为[套接字](https://zh.wikipedia.org/wiki/Berkeley%E5%A5%97%E6%8E%A5%E5%AD%97)表示的本地端点（local end-point），作为编程接口给程序使用。在TCP连接的生命期内，本地端点要经历一系列的[状态](https://zh.wikipedia.org/wiki/%E4%BC%A0%E8%BE%93%E6%8E%A7%E5%88%B6%E5%8D%8F%E8%AE%AE#状态编码)改变。[[1\]](https://zh.wikipedia.org/wiki/%E4%BC%A0%E8%BE%93%E6%8E%A7%E5%88%B6%E5%8D%8F%E8%AE%AE#cite_note-1)

答案:**BC**

---

125、根据汉字国标GB2312－80的规定，一个汉字的机内码的码长是________。
A)8bit   B)12bit
C)16bit  D)24bit

解析：

答案:**C**

---

126、下列各位十进制数中，属于正确的汉字区位码的是___。
A)5601      B)9596   
C)9678      D)8799

解析：

答案:**A**

---

131、下列关于汉字编码的叙述中，==错误==的是______。
A)***BIG5码是通行于香港和台湾地区的繁体汉字编码***
B)一个汉字的区位码就是它的国标码
C)无论两个汉字的笔画数目相差多大，但它们的机内码的长度是相同的
D)同一汉字用不同的输入法输入时，其输入码不同但机内码却是相同的

解析：

答案:**B**

---

***132***、汉字的区位码由一个汉字的区号和位号组成。其区号和位号的范围各为_______。
A)区号1～95，位号1～95
B)区号1～94，位号1～94
C)区号0～94，位号0～94
D)区号0～95，位号0～95

解析：

答案:**B**

---

***134***、根据汉字国标码GB2312－80的规定，一级常用汉字数是________个。
A)3477  B)3575
C)3755  D)7445

解析：

答案:**C**

---

138、设已知一汉字的国标码是5E48H，则其内码应该是______。
A)DE48H  B)DEC8H
C)5EC8H  D)7E68H

解析：+8080H

答案:**B**

---

2、关于计算机内存下面的说法哪些是正确的：
A)随机存储器（RAM）的意思是当程序运行时，每次具体分配给程序的内存位置是随机而不确定的。
B)一般的个人计算机在同一时刻只能存/取一个特定的内存单元。
C)计算机内存严格说来包括主存（memory）、高速缓存（cache）和寄存器（register）三个部分。
D)1MB内存通常是指1024*1024字节大小的内存。

解析：所谓“随机存取”，指的是当存储器中的讯息被读取或写入时，所需要的时间与这段信息所在的位置无关。

答案:**BD**

---

42、从逻辑功能上讲，计算机主要由（）组成。
A、ALU   B、I/O设备   C、存储器   D、控制器

解析：

**算术逻辑单元** （ **ALU** ）是[组合](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Combinational_logic&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhglSqif8HcQ2YGAnVtgPAmJAa-4kw) [数字电子电路](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Digital_electronic_circuit&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhg2s9Mi7Qzbh1B9gpHQasJSw1LFhA) ，其对[整数](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Integer&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhiiRyANxLRnKbkJ3sZaLf0pEYuO3w) [二进制数](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Binary_number&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhjie18Abp2fN6YYZEh0hIbrR7PHuA)执行[算术](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Arithmetic&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhimGADx449i_j01DnTFLlKoPzqSkg)和[按位运算](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Bitwise_operation&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhgeEJDW26WgvC77joxjDBRvepxIlg) 。 这与[浮点单元](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Floating-point_unit&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhii2fl18OBVvFlNv-1_NrQ3h1p0fw) （FPU）形成对比，后者对[浮点数](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Floating_point&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhgbdPzepE-B_RR6GQikCv0Dj2ZMOw)进行操作。  ALU是许多类型的计算电路的基本构建块，包括计算机的[中央处理单元](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Central_processing_unit&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhjIeOGHzJUoX9fjQYEOSFu2fSQI6Q) （CPU），FPU和[图形处理单元](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Graphics_processing_unit&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhgEZSP4fq7FBWUJbYazLOD9WteBgw) （GPU）。 单个CPU，FPU或GPU可能包含多个ALU。 

  ALU的输入是要操作的数据，称为[操作数](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Operand&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhgnaQJWPLgjy7IDd-42EHMhfTb2DQ) ，以及指示要执行的操作的代码;  ALU的输出是执行操作的结果。 在许多设计中，ALU还具有状态输入或输出或两者，它们分别在ALU和外部[状态寄存器](https://translate.googleusercontent.com/translate_c?depth=1&hl=zh-CN&rurl=translate.google.com&sl=auto&sp=nmt4&u=https://en.wikipedia.org/wiki/Status_register&xid=17259,15700021,15700124,15700149,15700186,15700190,15700201,15700214&usg=ALkJrhiHanuYsCTjE6ZZuLcPsXyQVZZyJw)之间传送关于先前操作或当前操作的信息。 

答案:**ABCD**

---

2、关于BIOS下面的说法哪个是正确的：
A)BIOS是计算机基本输入输出系统软件的简称。
B)BIOS里包含了键盘、鼠标、声卡、图形界面显器等常用输入输出设备的驱动程序。
C)BIOS一般由操作系统厂商来开发完成。
D)BIOS能提供各种文件拷贝、复制、删除以及目录维护等文件管理功能。

解析：无

答案:**D**

---

79、互联设备中Hub称为（     ）。 
A、网卡         B、网桥       C、服务器        D、集线器

答案：**Ｄ**

---

86、下列关于高级语言的说法正确的是（）。
A、Fortran是历史上的第一个面向科学计算的高级语言
B、Pascal和C都是编译执行的高级语言   
C、Smalltalk是历史上的第一个支持面向对象的语言  
D、编译器将高级语言程序转变为目标代码

解析：

**福传**（英语：Fortran），源自于“公式翻译”（英语：**For**mula **Tran**slation）的缩写，是一种[程式语言](https://zh.wikipedia.org/wiki/%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80)。1957年由[IBM](https://zh.wikipedia.org/wiki/IBM)开发出，是世界上第一个被正式采用并流传至今的[高级编程语言](https://zh.wikipedia.org/wiki/%E9%AB%98%E9%9A%8E%E8%AA%9E%E8%A8%80)。

**编译器**将汇编或高级计算机语言源程序（Source program）作为输入，翻译成目标语言（Target language）机器代码的等价程序。

答案:**ABD**

---

89、下列说法正确的是（）。
A、PASCAL通常是先编译后执行。   
B、BASIC语言程序通常需解释执行。   
C、连接程序可以把经编译程序产生的目标程序变成可执行的机器语言程序   
D、就执行速度而言，编译程序比解释程序快。

解析：

答案:**ABCD**

---

95、在Word的编辑状态,执行两次"剪切"操作,则剪贴板中（      ）。
A、仅有第一次被剪切的内容       B、仅有第二次被剪切的内容
C、有两次被剪切的内容           D、内容被清除

解析：

答案:**C**

---

2、关于BIOS下面的说法哪个是正确的：
A)BIOS是计算机==基本==输入输出系统软件的简称。
B)BIOS里包含了键盘、鼠标、声卡、图形界面显器等==常用==输入输出设备的驱动程序。
C)BIOS一般由操作系统厂商来开发完成。
D)BIOS能提供各种文件拷贝、复制、删除以及目录维护等文件管理功能。

解析：

答案:**A**

---

96、在Windows中，要删除已安装并注册了的应用程序，其操作是（        ）。
A、在计算机中找到对应的程序文件直接删除
B、在MSDOS方式下用Del命令删除指定的应用程序
C、删除开始菜单中对应的项目
D、通过控制面板中的“添加／删除程序”

解析：

答案:**D**

---

99、在Excel中，某个单元格显示为“######”，其原因可能为（        ）。
A、单元格列的宽度不够  				B、公式中有被0除的内容
C、与之相关的单元格数据被删除了		D、单元格行的高度不够

解析：

答案:**A**

---

101、下列关于Windows中文件名的叙述，正确的有（          ）。 
A、可以使用汉字						B、可以使用多个分隔符
C、可以使用*和？						D、可以使用空格

解析：

答案:**ABD**

---

103、若B1：B7单元格中的数据均为数值型数据，求B1至B7七个单元格的平均值，可以使用下列哪些公式（        ）。
A、AVERAGE（B1：B7，7） 			B、AVERAGE（B1：B7）
C、SUM（B1：B7）/7				D、SUM（B1：B7）/COUNT（B1：B7）

解析：

答案:**BCD**

---

108、下面关于中文Windows文件名的叙述中，错误的是(        )。
A、文件名允许使用汉字
B、文件名允许使用多个圆点分隔符
C、文件名允许使用空格
D、文件名允许使用竖线"|"

解析：

（1）、Windows操作系统对文件和文件夹命名限制:

1.1) 以下字符不能出现在文件和文件夹名称中：（引号之内）

'/'  '?'  '*'  ':'  '|'  '\'  '<'  '>'

1.2) 以下字符不能命名为文件或文件夹的名称：（引号之内）

"con","aux","nul","prn","com0","com1","com2","com3","com4","com5","com6","com7"

"com8","com9","lpt0","lpt1","lpt2","lpt3","lpt4","lpt5","lpt6","lpt7","lpt8","lpt9"

1.3) 另外，由于Windows对全文件名的字符长度作出258个字符以内的限制。全文件名长度指的是包括了文件路径的全部长度（一个汉字也按一个字符计算）。

（2）、Linux操作系统对文件和文件夹命名限制:

2.1) 除了 / 之外，所有的字符都合法。
2.2) 有些字符最好不用，如空格符、制表符、退格符和字符 @ # $ & ( ) - 等。
2.3) 避免使用加减号或 . 作为普通文件名的第一个字符。
2.4) 大小写敏感。
2.5) Linux 系统下的文件名长度最多可到256个字符。

（3）、Unix操作系统对文件和文件夹命名限制：

3.1）最多 255 个字符，除了字符 / 及空格其余均可。

3.2) 虽然在Unix系统中可以使用一些特殊的符号作为文件或者目录的名字。但是除非有特殊的必要，最好在文件名字中不要包含特殊符号。

答案:**D**

---

109、在Windows操作环境下，欲将整个屏幕的信息复制到剪贴板上，可使用键_______
A、Print Screen    B、Alt+Print Screen   C、Ctrl+Space     D、Alt+F4

解析：

答案:**A**

---

113、下列字符中ASCII码值最小的是（）。
A、a   B、B   C、R   D、1

解析：https://ascii.cl/

答案:**D**

---

115、微型计算机中，普遍使用的字符编码是（  ）   
A、补码  B、原码C、ASCII码 D、汉字编码

解析：字符编码...

答案:**C**

---

116、计算机中字符a的ASCII码值是01100001B，那么字符c的ASCII码值是（   ）。
A.01100010-B	B.01100011B		
C.143-O		D.63-H

解析:BCD答案相同...

答案:**BCD**

---

100、操作系统的主要功能是（  ）
A、	实现软、硬件转换 
B、	管理所有的软、硬件资源 
C、	把源程序转换为目标程序
D、	进行数据处理

解析：

答案:**B**

---

192、在一座大楼内组建的一个计算机网络系统，属于（    ）。
A. WAN     B. LAN      C. MAN     D. PAN

解析：

局域网（Local Area Network(LAN)）是一个可连接住宅，学校，实验室，大学校园或办公大楼等有限区域内计算机的计算机网络。 相比之下，广域网（WAN）不仅覆盖较大的地理距离，而且还通常涉及固接專線和对于互联网的链接。 相比来说互联网则更为广阔，是连接全球商业和个人电脑的系统。

答案:**B**

---

193、计算机网络通信的一个显著特点是（  ）。
 A、稳定性      B、间歇性、突发性  C、安全性   D、易用性

解析：

答案:**B**

---

194、网络按通信方式分类，可分为（ ）和（ ）。  
A. 点对点传输网络 　　　B. 广播式传输网络　
C. 数据传输网络 　　    D. 对等式网络

解析：

答案:**B**

---

195、UDP 协议是（）                                         
A．可靠的无连接协议		B．不可靠的无连接协议
C．可靠的连接协议		D．不可靠的连接协议

解析：

答案:**B**

---

196、通常所说的TCP/IP是指　(  )                         
A. TCP 和　IP    B. 传输控制协议　  　Ｃ.　互联网协议Ｄ.　IP ARP ICMP IGMP TCP UDP等多种协议的集合

解析：

答案:**B**

---

197、缩写CERNET表示中国( )计算机网。                
A.教育科研    B.经济    C.农业    D.工业

解析：

答案:**B**

---

198、浏览WWW使用的地址称为URL，URL是指        。        
A.IP地址    B.主页   C.主机域名    D.统一资源定位符

解析：

答案:**B**

---

199、域名http://www.njupt.edu.cn/由4个子域组成,其中哪个表示主机名 .( )  
A,www B,njupt C,edu D,cn

解析：

答案:**B**

---

200、一条TCP连接的建立过程包括(     )个步骤，释放过程包括(  )个步骤。
A.   2           B.   3        C.   4         D.   5

解析：

答案:**B**

---

65、下列部件中属于输出设备的有（  ）。
A、显示器    B、软盘    C、打印机    D、RAM

解析：BD即使输入设备，也是输出设备

答案:**ABCD**

---

4、计算机病毒传染的必要条件是（）。
A、在内存中运行病毒程序   B、对磁盘进行读写操作   
C、在内存中运行含有病毒的可执行程序。   D、运行游戏软件

解析：无

答案:**B**

---

67、在以下关于微机内存的叙述中，正确的叙述为（  ）。
A、是用半导体集成电路构造的
B、掉电后均不能保存信息
C、是依照数据对存储单元进行存取信息
D、是依照地址对存储单元进行存取信息

解析：无

答案:**AD**

---

77、在微机中，与VGA密切相关的设备是（    ）。
A、打印机
B、扫描仪
C、显示器
D、键盘

解析：无

答案:**C**

---

5、下列不属于冯诺依曼计算机模型的核心思想是（）。
A、采用二进制表示数据和指令   B、采用“存储程序”工作方式   
C、计算机软件只有系统软件     D、结构化程序设计方法

解析：无

答案:**CD**

---

27、办公室自动化(OA)是计算机的一项应用，按计算机应用的分类，它属于____。
A)科学计算 B)辅助设计
C)实时控制 D)信息处理

解析：???

答案:**D**

---
28、下列的英文缩写和中文名字的对照中，错误的是________。
A)CAD--计算机辅助设计
B)CAM--计算机辅助制造
C)CIMS--计算机集成管理系统
D)CAI--计算机辅助教育

解析：计算机集成[制造系统](https://baike.baidu.com/item/%E5%88%B6%E9%80%A0%E7%B3%BB%E7%BB%9F)，简称CIMS，是随着[计算机辅助设计与制造](https://baike.baidu.com/item/%E8%AE%A1%E7%AE%97%E6%9C%BA%E8%BE%85%E5%8A%A9%E8%AE%BE%E8%AE%A1%E4%B8%8E%E5%88%B6%E9%80%A0/3634741)的发展而产生的。它是在信息技术自动化技术与制造的基础上，通过计算机技术把分散在产品设计制造过程中各种孤立的自动化[子系统](https://baike.baidu.com/item/%E5%AD%90%E7%B3%BB%E7%BB%9F/4670893)有机地集成起来，形成适用于多品种、小批量生产，实现整体效益的集成化和智能化制造系统。

**D**:[Computer assisted instruction](https://en.wikipedia.org/wiki/Computer_assisted_instruction) or e-Learning

答案:**C**

---

24、关于世界上第一台电子计算机ENIAC的叙述中，错误的是________。
A)ENIAC是年在美国诞生的
B)它主要采用电子管和继电器
C)它是首次采用存储程序和程序控制自动工作的电子计算机
D)研制它的主要目的是用来计算弹道

解析：

ENIAC为[美国陆军](https://zh.wikipedia.org/wiki/%E7%BE%8E%E5%9B%BD%E9%99%86%E5%86%9B)的弹道研究实验室（BRL）所使用，用于计算[火炮](https://zh.wikipedia.org/wiki/%E7%81%AB%E7%82%AE)的[火力表](https://zh.wikipedia.org/wiki/%E5%A4%96%E5%BC%B9%E9%81%93)

ENIAC包含了17468个[真空管](https://zh.wikipedia.org/wiki/%E7%9C%9F%E7%A9%BA%E7%AE%A1)、7200个晶体[二极管](https://zh.wikipedia.org/wiki/%E4%BA%8C%E6%A5%B5%E7%AE%A1)、1500个[继电器](https://zh.wikipedia.org/wiki/%E7%BB%A7%E7%94%B5%E5%99%A8)、10000个[电容器](https://zh.wikipedia.org/wiki/%E7%94%B5%E5%AE%B9%E5%99%A8)，还有大约五百万个手工[焊接](https://zh.wikipedia.org/wiki/%E7%84%8A%E6%8E%A5)头。

1948年9月16日，ENIAC运行了一个由阿黛勒·戈德斯坦写给冯·诺伊曼的程序，因此成为了第一个[存储程序计算机](https://zh.wikipedia.org/wiki/%E5%AD%98%E5%82%A8%E7%A8%8B%E5%BA%8F%E8%AE%A1%E7%AE%97%E6%9C%BA)。

EDSAC是世界上第一台实际运行的[存储程序式](https://zh.wikipedia.org/wiki/%E5%86%AF%C2%B7%E8%AF%BA%E4%BC%8A%E6%9B%BC%E7%BB%93%E6%9E%84)[电子计算机](https://zh.wikipedia.org/wiki/%E7%94%B5%E5%AD%90%E8%AE%A1%E7%AE%97%E6%9C%BA)

答案:**C**

---

6、下列关于算法的正确的说法是（）。
A、算法必须有输出   B、算法必须在计算机上用某种语言实现   
C、算法不一定有输入   D、算法必须在有限步执行后能结束

解析：输入和输出看反了

答案:**ACD**

---

7、下面有关计算机知识说明，正确的是（）。
A、在Windows操作系统下，删除磁盘中的文件时都先存放在回收站中。
B、Foxmail是用于收发电子邮件的工具。
C、文件夹组织是一个有层次的树状结构，其中最顶层的是桌面。   
D、为了提高软件的测试效率，应该选择发现错误的可能性大的测试数据。

解析：A:shift+Del是直接删除

答案:**BCD**

---

14. 用计算机对人造卫星轨迹的计算属于计算机（        ）方面的应用。
    A、数据处理			B、科学计算
    C、辅助教学			D、人工智能

    解析：无

    答案:**B**

---

9、下面有关计算机知识的说明，正确的是（）。
A、在Windows操作系统下，删除磁盘中的文件时都先存放在回收站中   
B、用高级程序设计语言编写的程序必须通过编译或解释方式翻译后才能被执行。   
C、计算机病毒的本质是认为编制的具有破坏性的程序。   
D、在树型目录结构的不同文件夹中，允许两个文件名相同。

解析：A:shift+Del是直接删除

答案:**BCD**

---

34、计算机被病毒感染的可能途径是（   ）。
A、运行错误的操作命令
B、磁盘表面不清洁
C、运行来历不明的外来文件
D、电源不稳定

解析：运行错误的操作命令，不要偏激，钻牛角尖

答案:**C**

---

8、下列各数中最大的是（）
A、11010110.0101（二进制）  B、D6.53（十六进制）
C、214.32（十进制）  D、326.25（八进制）

解析：小数八进制一位对应二进制三位

答案:**D**

---

35、若一台计算机的字长为32位，则表明该机器（）。
A、	能处理的数值最大为4位十进制数
B、	能处理的数值最多为4个字节
C、	在CPU中能够作为一个整数加以处理的二进制数据为4个字节

D.在CPU中运算的结果最大为232

解析：数值可以不只四个字节

答案:**B**

---

39、下面关于计算机的说法正确的是（）。
A、微机内存容量的基本计量单位是字节。   
B、二进制数中右起第10位上的1相当于2^10   
C、CPU每执行一个指令，就完成一步基本运算或判断。   
D、32位的计算机中的“32”指的是字长。

解析：

答案:**ACD**

---

40、在下面关于计算机系统硬件的说法中不正确的是（）。
A、没有外部设备的计算机称为裸机   
B、当关闭计算机电源后，RAM中的程序和数据就消失了。

C、优盘和硬盘上的数据均可由CPU直接存取。   
D、优盘和硬盘驱动器既属于输入设备又属于输出设备。

解析：在计算机科学中，**裸机**（或**裸金属**）是指一个[计算机](https://en.wikipedia.org/wiki/Computer)执行直接在逻辑硬件指令而没有中间[操作系统](https://en.wikipedia.org/wiki/Operating_system)。

答案:**AC**

---

36、下列哪些是属于内存储器（）。
   A、硬盘   B、RAM   C、ROM  D、Cache

解析：

答案:**BCD**

---

42、从逻辑功能上讲，计算机主要由（）组成。
A、ALU   B、I/O设备   C、存储器   D、控制器

解析：一个**算术逻辑单元**（**ALU**）为[组合](https://en.wikipedia.org/wiki/Combinational_logic) [的数字电子电路](https://en.wikipedia.org/wiki/Digital_electronic_circuit)，其执行[算术](https://en.wikipedia.org/wiki/Arithmetic)和[位操作](https://en.wikipedia.org/wiki/Bitwise_operation)上[整数](https://en.wikipedia.org/wiki/Integer) [的二进制数](https://en.wikipedia.org/wiki/Binary_number)。

答案:**ABCD**

---

50、硬盘上一个扇区的字节数是 (    )
A、  256  B、 1024   C、 512   D、 128

解析：[磁盘](https://baike.baidu.com/item/%E7%A3%81%E7%9B%98)的每一面被分为很多条[磁道](https://baike.baidu.com/item/%E7%A3%81%E9%81%93)，即表面上的一些[同心](https://baike.baidu.com/item/%E5%90%8C%E5%BF%83)圆，越接近中心，圆就越小。而每一个[磁道](https://baike.baidu.com/item/%E7%A3%81%E9%81%93)又按512个[字节](https://baike.baidu.com/item/%E5%AD%97%E8%8A%82)为单位划分为等分，叫做扇区

答案:**C**

---

51、通常所说的主机主要包括(   )
​	A、CPU     			B、CPU和内存		
C、CPU、内存与外存		D、CPU、内存与硬盘

解析：

答案:**B

---

52、 和外存相比，内存的主要特征是（   ）。
A、	存储正在运行的程序		B、能存储大量信息
C、 能长期保存信息 			D、能同时存储程序和数据

解析：主要特征

答案:**A**

---
4.TCP协议属于哪一层协议（）。
A.应用层   B.传输层   C.网络层   D.数据链路层

解析：无

答案:**B**

---
20、按通信距离划分，计算机网络可以分为局域网和广域网。下列网络中属于局域网的是（）。
A、Internet  B、CERNET   C、Novell  D、以太网

解析：
B：中国教育和科研计算机网（China Education and Research Network）
C：Novell, Inc是世界上最具实力的网络系统公司，其主要产品NETWARE网络操作系统可将多台个人电脑连接到一个统一的整合子目录，存储，打印，数据库等的网络中。
D：以太网(Ethernet)指的是由Xerox公司创建并由Xerox、Intel和DEC公司联合开发的基带局域网规范，是当今现有局域网采用的最通用的通信协议标准。

答案:**CD**

---

2、如果互连的局域网高层分别采用TCP/IP协议与SPX/IPX协议，那么我们可以选择的互连设备应该是（）。
   A、中继器   B、网桥   C、网卡  D、路由器
解析：
A：中继器（RP repeater）是工作在***物理层***上的连接设备。适用于完全相同的两类网络的互连，主要功能是通过对数据信号的重新发送或者转发，来扩大网络传输的距离。中继器是对信号进行再生和还原的网络设备：OSI模型的物理层设备。
B：网桥（Bridge）是早期的两端口二层网络设备，用来连接不同网段。网桥的两个端口分别有一条独立的交换信道，不是共享一条背板总线，可隔离冲突域。网桥将网络的多个网段在***数据链路层***连接起来。
C：网卡是工作在***链路层***的网络组件，是局域网中连接计算机和传输介质的接口，不仅能实现与局域网传输介质之间的物理连接和电信号匹配，还涉及帧的发送与接收、帧的封装与拆封、介质访问控制、数据的编码与解码以及数据缓存的功能等。
D：路由器（Router），是连接因特网中各局域网、广域网的设备，它会根据信道的情况自动选择和设定路由，以最佳路径，按前后顺序发送信号。路由器（Router）又称网关设备（Gateway）是用于连接多个逻辑上分开的网络，所谓逻辑网络是代表一个单独的网络或者一个子网。路由和交换机之间的主要区别就是交换机发生在OSI参考模型第二层（数据链路层），而路由发生在第三层，即***网络层***。

答案:**D**

---

4．Linux下可执行文件的默认扩展名是(    )。
  A. exe        B. com       C. dll      D. 以上都不是

  解析：
  DLL(Dynamic Link Library)文件为动态链接库文件，又称“应用程序拓展”，是软件文件类型。 在Windows中，许多应用程序并不是一个完整的可执行文件，它们被分割成一些相对独立的动态链接库，即DLL文件，放置于系统中。

  答案：**D** 

---
5．如果在某个进制下等式7* 7=41成立，那么在该进制下等式12 *12=（     ）也成立。
A. 100        B. 144       C. 164      D. 196
解析：
12进制
14 * 14=196=1 * 144+4 * 12+4=144

答案：**B**

---
6．提出“存储程序”的计算机工作原理的是（     ）。
A. 克劳德•香农   B. 戈登•摩尔   C. 查尔斯•巴比奇   D. 冯•诺依曼

解析：无
答案：**D**

---
8．主存储器的存取速度比中央处理器(CPU)的工作速度慢的多，从而使得后者的效率受到影响。而根据局部性原理，CPU所访问的存储单元通常都趋于一个较小的连续区域中。于是，为了提高系统整体的执行效率，在CPU中引入了(   )。
A．寄存器        B．高速缓存       C．闪存         D．外存

解析：无
答案：**B**

---

4．在整数的补码表示法中，以下说法正确的是（   ）。
   A．只有负整数的编码最高位为1
   B．在编码的位数确定后，所能表示的最小整数和最大整数的绝对值相同
   C．整数0只有一个唯一的编码
   D．两个用补码表示的数相加时，如果在最高位产生进位，则表示运算溢出

解析：

-0的的编码让给了最小的那个数

答案：**D**

---

10.IPv4 协议使用 32位地址，随着其不断被分配，地址资源日趋枯竭。因此，它正逐渐被 使用（ ）位地址的 IPv6 协议所取代。   

 A. 40  		B. 48 		C. 64 		D. 128

解析：

IPv4 $2^4*2$

IPv6 $2^6*2$ 

答案：**D**

---

---
## 图论

---

19、下列关于图的说法正确的是（）：
A、欧拉图的每一个顶点都能作为某条欧拉闭迹的起点 
B、 一个图有欧拉闭迹当且仅当该图有零个奇点。 
C、 若一个无向图有奇数条边，则它必然不是二分图。
D、若G是汉密尔顿图，则对G上的汉密尔顿圈C，任意删去n个点，最多可将C划分为n段，反之亦然。

解析：
B 图不一定联通
D 反之亦然不对，***但我不知道为什么*** 

答案:**A**

---
2.如图所示，图中每条边上的数字表示该边的长度，则从A到E的最短距离是.
![](http://zjqyy.top/pic/2.png)

解析：

![](http://zjqyy.top/pic/1.png)

答案:**15**

---
完善程序（共2题11空，每题后三空为3分，其它空2分，共28分）
1、	现在政府计划在某个区域的城市之间建立告诉公路，以使得其中任意两个城市之间都有直接或间接的告诉公路相连。费用为每千米一个单位价格，求最小费用。
输入：n（n<=100，表示城市数目）
​     接下来n行每行两个数xi，yi，表示第i个城市的坐标。（单位：千米）
输出：最小费用（保留两位小数）{\displaystyle V}

```c++
#include<iostream> 
#include<iomanip>  
#include<cmath> 
using namespace std;  
const int MaxN=101;
struct Tcity{
	double x,y;
}c[MaxN];
double d[MaxN][MaxN];
int p[MaxN];
inline double pingfang(double a){return (1);}
int main() {
	int n;
	cin>>n;
	for(int i=1;i<=n;i++) cin>>c[i].x>>c[i].y;
	for(int i=1;i<=n;i++)
		for(int j=1;j<=n;j++)
		d[i][j]=sqrt(pingfang(c[i].x-c[j].x)+pingfang(  (2)  ));
	p[1]=0;
	for(int i=2;i<=n;i++) (3);
	double ans=0;
	for(int i=1;i<n;i++){
		double Min=1e10;
		int k;
		for(int j=1;j<=10;j++)
			if(  (4)  ){Min=d[p[j]][j];  (5) ;}
		ans+=d[p[k]][k];
		p[k]=0;
		for(int j=1;j<=n;j++) if(  (6)  )p[j]=k;
	}
	cout<<fixed<<setprecision(2)<<ans<<endl;
    return 0;
}
```

解析：
prim (4)(6)空是精髓，要理解
答案：
(1)a*a
(2)c[i].y-c[j].y
(3)p[i]=1
(4)p[j]>0&&d[p[j]][j]<Min
(5)k=j
(6)p[j]>0&&d[k][j]<d[p[j]][j]

---

## 数据结构

3、已知8个数据元素为（26，75，15，23，14，62，72，19），按照依次插入结点的方法生成一棵二叉排序树，则该树的深度为（）。
A、3  B、4   C、5  D、6

解析：二叉查找树左小右大，和位置关系不大

答案:**B**

---

7、在带尾指针（链表指针clist指向尾结点）的非空循环单链表中每个结点都以next字段的指针指向下一个节点。假定其中已经有2个以上的结点。下面哪些说法是正确的：
A)如果p指向一个待插入的新结点，在头部插入一个元素的语句序列为：
​      p->next = clist->next; clist->next = p;
B)如果p指向一个待插入的新结点，在尾部插入一个元素的语句序列为：
​      p->next = clist；clist->next = p;
C)在头部删除一个结点的语句序列为：
​      p = clist->next; clist->next = clist->next->next; delete p; 
D)在尾部删除一个结点的语句序列为。
​      p = clist; clist = clist ->next; delete p; 

解析：循环单链表的尾指针的next是头指针

答案:**AC**

---

8、散列表的地址区间为0-10,散列函数为H(K)=K mod 11。采用开地址法的线性探查法处理冲突，并将关键字序列26，25，72，38，8，18，59存储到散列表中，这些元素存入散列表的顺序并不确定。假定之前散列表为空，则元素59存放在散列表中的可能地址有：
A) 5      B) 7     C) 9      D) 10

解析：

| 0    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|      |      |      |      |      |      |      |      |      |      |      |

| 1    | 2    | 1    | 25   | 26   | 38   | 72   | 18   | 8    | 1    | 1    |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|      |      |      |      | 59   | 59   |      |      |      | 59   |      |



答案:**ABC**

---

17、下列说法正确的是（ABC）。

A、设G是一个n阶无向简单图，n是大于等于2的奇数，则图G与它的补图中的奇数度结点个数相等。	

B、若无向图G中只有两个奇数度的结点，则这两个结点一定是连通的。

C、连通图G有k个奇数度的结点，则图G至少要添加k/2条边才能使其成为欧拉图

D、设G具有n个结点的简单图，如果G中每一对结点度数之和大于等于n-1，则在G中存在一条汉密尔顿路，反之亦然。

解析：D反之亦然不对，==汉密尔顿回路暂时没有找到充要条件==.

---

7、设哈希函数H（K）=3 K mod 11，哈希地址空间为0～10，对关键字序列（32，13，49，24，38，21，4，12），按线性探测法解决冲突的方法构造哈希表，求出等概率下查找失败时的平均查找长度（D）。

 A. 11/11		            B. 29/11

 C. 35/11           		    D. 40/11

解析：查找失败的平均查找长度=各点到空位置的距离之和除以地址空间个数。

 ASLunsucc=（1+2+1+8+7+6+5+4+3+2+1）/11=40/11

------

27、由权值分别为3,8,6,2,5的叶子结点生成一棵哈夫曼树，它的带权路径长度为（  ）。
A. 24			B. 48			C. 72			D. 53

解析：带权路径长度$\sum$深度×值

答案:**D**

---

7、设哈希函数H（K）=3 K mod 11，哈希地址空间为0～10，对关键字序列（32，13，49，24，38，21，4，12），按线性探测法解决冲突的方法构造哈希表，求出等概率下查找失败时的平均查找长度（）。
A. 11/11		            B. 29/11
C. 35/11           		    D. 40/11

------

38、下列有关树的说法正确的是（）。
A. 二叉树的前序遍历中，任意结点均处在其子女结点之前。
B. 哈夫曼树的总结点个数（多于1时）不能为偶数。
C. 由二叉树的先序序列和后序序列可以唯一确定一颗二叉树。
D. 哈夫曼树一定是完全二叉树。

解析：

B 总结点个数：2*n-1

4 5 5 5 8 9

```
            36
        17  |    19
    19  |  8	|   10 |   8
 4     5 |   |5      5  |
```



答案:**BD**

------

4、二维数组A的每个元素是由10个字符组成的串，其行下标i=0,1,…,8，列下标j=1,2,…,10。若A按行先存储，元素A$[ 8 ][ 5 ]$的起始地址与当A按列先存储时的元素（ ）的起始地址相同。设每个字符占一个字节。

```
A．A[8][5]       B．A[3][10]       C．A[5][8]       D．A[0][9]
```

解析：

以行先存储，一行10个

以列先存储， 一列9个

可以想成横着写和竖着写进行记忆

答案:**B**

---

92、下列说法正确的是（）。
A、设G是一个n阶无向简单图，n是大于等于2的奇数，则图G与它的补图中的奇数度结点个数相等。	
B、若无向图G中只有两个奇数度的结点，则这两个结点一定是连通的。
C、连通图G有k个奇数度的结点，则图G至少要添加k条边才能使其成为欧拉图
D、设G具有n个结点的简单图，如果G中每一对结点度数之和大于等于n-1，则在G中存在一条汉密尔顿路

解析：**阶**（Order）：图![G](https://wikimedia.org/api/rest_v1/media/math/render/svg/f5f3c8921a3b352de45446a6789b104458c9f90b)中顶集![V](https://wikimedia.org/api/rest_v1/media/math/render/svg/af0f6064540e84211d0ffe4dac72098adfa52845)的大小称作图![G](https://wikimedia.org/api/rest_v1/media/math/render/svg/f5f3c8921a3b352de45446a6789b104458c9f90b)的阶。

D、设G具有n个结点的简单图，如果G中每一对结点度数之和大于等于n-1，则在G中存在一条汉密尔顿路

这意味这这两个点联通

即任意两点联通

哈密顿路径也称作哈密顿链，指在一个图中沿边访问每个顶点恰好一次的路径。

答案:**AB**

---

3、若对n阶对称矩阵A以行序为主序方式将其下三角形的元素(包括主对角线上所有元素)依次存放于一维数组B[1..(n(n+1))/2]中，则在B中确定aij（i<j）的位置k的关系为（  ）。
A．i* (i-1)/2+j      B．j* (j-1)/2+i      C．i* (i+1)/2+j      D．j* (j+1)/2+i

解析：下三角形如下图

```
1 1 1 1 1
  1 1 1 1
    1 1 1 
      1 1
        1
```

答案:**Ｂ**

------

66、具有n个顶点的有向无环图最多可包含（      ）条有向边。
A. n-1			B. n   			C. n(n-1)/2    	D.n(n-1)

解析：
考虑无向完全图，有$n*(n-1)$条边，用有向边代替无向边，即可得到有向无环图

答案:**C**

---

79、下列有关图的说法正确的是（）。
A. 如果无向图中各个顶点的度都大于2，则该图中必有回路。
B. 如果有向图中各个顶点的度都大于2，则该图中必有回路。
C. 图的深度优先搜索（depth first search）是一种典型的回溯搜索的例子，可以通过递归算法求解。
D. 图的广度优先搜索（breadth first search）算法可以不用递归算法实现。

解析：只要有一条边，左右满足度大于二，除此之外左右不联通，则不能形成回路

答案:**ACD**

---

77、下列有关图的说法正确的是（）。
A.一个图的子图可以是空图，顶点个数为0。 
B.存储图的邻接矩阵中，矩阵元素个数不但与图的顶点个数有关，而且与图的边数也有关。
C.对一个连通图进行一次深度优先搜索（depth first search）可以遍访图中的所有顶点。   	
D. 一个有1000个顶点和1000条边的有向图的邻接矩阵是一个稀疏矩阵。

解析：A不对，记一下

答案:**CD**

---

86、设有一个连通网络如图所示。试按如下格式，应用Kruskal算法给出在构造最小生成树过程中顺序选出的各条边。可行的生成方案为（）。

A. (0,3),(1,4),(2,5),(3,5),(3,4)     		
B. (0,3),(0,1),(0,2),(3,4),(3,5)			
C. (0,3),(2,5),(1,4),(3,5),(3,4)      	
D. (2,5),(3,5),(3,4),(3,1),(3,0)

![](http://www.zjqyy.top/pic/861.jpg)

解析:顺序

答案:**C**

---

91、设完全图G有n个结点，m条边，则当（）时，G中存在欧拉回路。
A、m为奇数	
B、m为偶数
C、n为奇数
D、n为偶数

解析:在**图**论的数学领域，**完全图**是一个简单的无向**图**，其中每对不同的顶点之间都恰连有一条边相连

那么对于一个点数为奇数的完全图联向其他点各一条边，即n-1条，是偶数

![](http://zjqyy.top/pic/graph1.png)

答案:**C**

---

80、下列有关图的说法正确的是（）。
A. 对于一个边上权值任意的带权有向图，使用Dijkstra算法可以求一个顶点到其它各个顶点的最短路径。
B.对一个有向图进行拓扑排序（topological sorting），一定可以将图的所有顶点按其关键码大小排列到一个拓扑有序的序列中。
C.有回路的有向图不能完成拓扑排序。     	
D. 对任何用顶点表示活动的网络（AOV网）进行拓扑排序的结果都是唯一的。

解析：A不要忘了负权

答案:**C**

---

8、以下说法错误的是（   ）。

A．求表长、定位这两种运算在采用顺序存储结构时实现的效率不比采用链式存储结构时实现的效率低
B．顺序存储的线性表可以随机存取
C．由于顺序存储要求连续的存储区域，所以在存储管理上不够灵活
D．线性表的链式存储结构优于顺序存储结构

解析：B有线性表的随机存储


答案:**D**

---

39、图的简单路径是指（      ）不重复的路径。
A. 权值			B. 顶点			C. 边			D. 边与顶点均 

解析：

答案:**B**

---

18、设栈S和队列Q的初始状态为空，元素e1、e2、e3、e4、e5和e6依次进入栈S，一个元素出栈后即进入Q，若6个元素出队的序列是e2、e4、e3、e6、e5和e1，则栈S的容量至少应该是（　）。
A．2              B．3              C．4                D． 6

解析：e3和e4都出栈了，仔细

答案:**B**

---

45、若一个图中包含有k个连通分量，若要按照深度优先搜索的方法访问所有顶点，则必须调用( )次深度优先搜索遍历的算法。
A. k      	B. 1        	C. k-1      	D. k+1   

解析：还有第一个点，仔细

答案:**A**

---

46、若采用邻接矩阵法存储一个n个顶点的无向图，则该邻接矩阵是一个 (       )。
A. 上三角矩阵	B. 稀疏矩阵		C. 对角矩阵		D. 对称矩阵

解析：对角线对称

答案:**D**

---

21、最大容量为n的循环队列，队尾指针是rear，队头是front，则队空的条件是（　）。
A. (rear+1)%n== front                  B. rear== front                                                 

   C．rear+1== front                      D. (rear-l)%n==front

解析：队空，仔细

答案:**B**

------

85、如果想把该连通图变成重连通图，至少在图中加（）条边？ 

![](http://zjqyy.top/pic/85.jpg)

解析：

在无向图中，如果任意两个顶点之间含有不止一条通路，这个图就被称为重连通图。

![](http://zjqyy.top/pic/86.jpg)

答案:**2**

---

30、欲实现任意二叉树的后序遍历的非递归算法而不必使用栈，最佳方案是二叉树采用（ ）存储结构。
A. 三叉链表	B. 广义表		C. 二叉链表    	D. 顺序

解析：三叉链表是二叉树的另一种主要的链式存储结构。三叉链表与二叉链表的主要区别在于，它的结点比二叉链表的结点多一个指针域，该域用于存储一个指向本结点双亲的指针。

答案:**A**

---

63、若一个图的边集为{(A,B),(A,C),(B,D),(C,F),(D,E),(D,F)}，则从顶点A开始对该图进行广度优先搜索，得到的顶点序列可能为( )。
A. A,B,C,F,D,E              	    B. A,C,F,D,E,B
C. A,B,D,C,F,E              	    D. A,B,D,F,E,C

解析：广搜是队列，拓展有先后

答案:**D**

---
7. 对长度为n的有序单链表，若检索每个元素的概率相等，则顺序检索到表中任一元素的

平均检索长度为（   ）。
A. n/2   B. (n+1)/2    C. (n-1)/2    D. n/4 

解析：
检索任一元素检索长度T=1+2+3+4+5+6+……+n=n(n+1)/2
因为概率相等，所以结果为T/n=（n+1)/2

答案:**B**

---

阅读程序写结果
```c++
#include<iostream>
using namespace std;
int n=12;
char ch[]= {'q','A','S','O','R','T','E','X','A','M','P','L','E'};
void shift(int k,int n) {
	char v;
	int j;
	v=ch[k];
	j=k+k;
	while(j<=n) {
		if(j<n&&ch[j]<ch[j+1])
			j++;
		if(v<ch[j]) {
			ch[j/2]=ch[j];
			j*=2;
		} else
			return;
		ch[j/2]=v;
	}
}
void hpsrt() {
	int k;
	char tmp;
	for(k=n/2; k>0; k--)
		shift(k,n);
	cout<<"No.1:";
	for(k=1; k<=n; k++)
		cout<<ch[k];
                cout<<' ';
	for(k=n; k>0; k--) {
		tmp=ch[1];
		ch[1]=ch[k];
		ch[k]=tmp;
		shift(1,k-1);
	}
}
int main() {
	int k;
	hpsrt();
	cout<<"No.2:";
	for(k=1; k<=n; k++)
		cout<<ch[k];
	cout<<endl;
	return 0;
}
```
输出：

解析：
No.1:ASORTEXAMPLE 
No.1:ASORTEXAMPLE 
No.1:ASORTEXAMPLE 
No.1:ASXRTEOAMPLE 
No.1:ATXRSEOAMPLE 
No.1:XTORSEAAMPLE 
注意：它是数位×2以后的max（这个数和它左边的那个数）尝试交换
No.2它就把最大的放在最后，排成有序数列
a sort example 堆排？

答案：
**No.1:XTORSEAAMPLE No.2:AAEELMOPRSTX**

---

7．关于拓扑排序，下列说法正确的是(   )。
   A．所有连通的有向图都可以实现拓扑排序
   B．对同一个图而言，拓扑排序的结构是唯一的
   C．拓扑排序中入度为0的结点总会排在入度大于0的结点的前面
   D．拓扑排序结果序列中的第一个结点一定是入度为0的点

解析：

C不一定，要看具体实现

答案:**D**

---

---
## 时间复杂度

3、假设某算法的计算时间表示为递推关系表达式：

   T(n)=9T(n/3)+n

   则算法的时间复杂度为（D）。

A.O(n)  			B.O(n^(1/2))         C.O(nlogn)  		D.O(n^2)  

9、假设某算法的计算时间表示为递推关系表达式：
   T(n)=2T(n/4)+n^(1/2)
   T(1)=1
   则算法的时间复杂度为（）。
A.O(n)  			B.O(n^(1/2))         C.O(n^(1/2)logn)  		D.O(n^2) 
解析：无
答案:**C**

![](http://zjqyy.top/pic/master.png)

---


15、下列属于冯诺依曼计算机模型的核心思想有（）。
A、采用二进制表示数据和指令  B、采用“存储程序”工作方式   
C、计算机硬件有五大部件（运算器、控制器、存储器、输入和输出设备）  
D、结构化程序设计方法

解析：无

答案:**ABC**

---

---

## 数学

4、合唱演出在即，一名团员病倒了，不能参加。指挥排了一下队伍，如果10人一排，有一排少一人，如果12人一排，有一排还是少一人，如果15人一排，有一排仍少一人。请问这个未上百人的合唱团共有多少（）人？
   A、59  B、60   C、61  D、62

解析：59+病倒团员+指挥

答案:**C**

---

```c++
#include <iostream>
using namespace std;

int main()
{
	int n,m,i,j,p,k;
	int a[100],b[100];
	cin >> n >> m;
	a[0]=n;
	i=0;
	p=0;
	k=0;
	do
	{
		for (j=0;j<i;j++)
			if (a[i]==a[j])
			{
				p=1;
				k=j;
				break;
			}
		if (p)
			break;
		b[i]=a[i]/m;
		a[i+1]=a[i]%m*10;
		i++;
	}while (a[i]!=0);
	
	cout << b[0] << ".";
	for (j=1; j<k; j++)
		cout << b[j];
	if (p)
		cout << "(";
	for (j=k;j<i;j++)
		cout << b[j];
	if (p)
		cout << ")";
	cout << endl;
	return 0;
}
输入：5 13
输出：_________
```

观察一波，就可以发现这是在求n/m的小数，循环部分用()围起

答案：**0.(384615)**

---

```c++
#include <iostream>
using namespace std;

const int maxn=50;
const int y=2009;
int main()
{
	int n,c[maxn][maxn],i,j,s=0;
	cin >> n;
	c[0][0]=1;
	for(i=1;i<=n;i++)
	{
		c[i][0]=1;
		for(j=1;j<i;j++)
			c[i][j]=c[i-1][j-1]+c[i-1][j];
		c[i][i]=1;
	}
	for(i=0;i<=n;i++)
		s=(s+c[n][i])%y;
	cout << s << endl;
	return 0;
}

输入：17
输出：_______________       
```

解析：一眼就可以看出在求$\sum c[17][0..n]$，但是没有看到取模和算错

$c[17][0]=c[17][17]=1$

$c[17][1]=c[17][16]=17$

$c[17][2]=c[17][15]=136$

$c[17][3]=c[17][14]=680$

$c[17][4]=c[17][13]=2380$

==$c[17][5]=c[17][12]=6188$==(~~5188~~)

$c[17][6]=c[17][11]=12376$

==$c[17][7]=c[17][10]=19448$==(~~21448~~)

==$c[17][8]=c[17][9]=24310$==(~~45331,还乘了三（错认为9多）~~)

$\sum =65536$

ans=131072%2009=487

然而忘了老师的讲义：

1<<17=65536

![](http://zjqyy.top/pic/53.png)

---
由数字1，1，2，4，8，8所组成的不同的四位数的个数是____。

解析：
1188 1818 1881
8811 8181 8118
1246->4！
11？？->c[3][1]*4!/2!
88？？->c[3][2]*4!/2!
总上所述，ans=6+24+72=102

答案:**102**

---
10. 若有变量var a: integer; x, y: real;，且a := 7，x := 2.5，y := 4.7，则
    表达式x + a mod 3 * trunc(x + y) mod 2 div 4的值大约是（   ）。 
    A. 2.500000  B. 2.750000   C. 3.500000   D. 0.000000 

解析：
a是整数，/4后0.25和舍去

答案:**A**

---

1、	Kathy函数是这样定义的：
f(1)=1
f(3)=3
f(2n)=f(n)
f(4n+1)=2f(2n+1)-f(n)
f(4n+3)=3f(2n+1)-2f(n)
对于一个给定的数m=55，求出所有满足f(n)=n,(n<=m)的自然数n的个数____。

解析：

f[1]=1;					1			1
f[2]=1;					10			01
f[3]=3;					11			11
f[4]=1;					100			001
f[5]=5;					101			101
f[6]=3;					110			011
f[7]=7;					111			111
f[8]=1;					1000		0001
f[9]=9;					1001		1001
f[10]=5					1010		0101
f[11]=13;				1011		1101
f[12]=3;					1100		0011
f[13]=11;				1101		1011
f[14]=7;					1110		0111
f[15]=15;				1111		1111

观察可得f[n]是n二级制下的反串  ~~（装作可以,反正我是想不到）~~

(1)

f[2n]=f[n]最后一位是0在最前面添0

(2)

f[4n+1]=2f[2n+1]-f[n];

结尾是01

设f[n]的二级制表示位x

f[2n+1]->1x

2f[2n+1]->1x0

2f[n]->x

1x0-x->10x

(3)

f[4n+3]=3f[2n+1]-2f[n]

结尾是11

设f[n]的二级制表示位x

3f[2n+1]->1x0+1x

2f[n]->x0

3f[2n+1]-2f[n]=11x

综上所述，可~~证~~结论成立

答案：**16**

---

2、在m*n的棋盘上，每个方格（单位正方形，即边长为1的正方形）的顶点称为格点。以格点为顶点的多边形称为格点多边形。若设格点凸八边形面积的最小值为9，格点凸八边形内部（非顶点的）格点的个数的最小值为。
解析：

![](http://www.zjqyy.top/pic/9.png)

答案：**6

------

65、篮子里有苹果、梨、桃和桔子，现有81个小朋友，如果每个小朋友都从中任意拿两个水果，那么至少有多少个小朋友拿的水果是相同的？ 

解析：

注意，可以拿两个相同的，故共有10种情况

ans=81/10+1

答案：**9**

------

25、四面体的一个顶点是A，从其它顶点和各棱中点中取3个点，使他们和点A在同一个平面上，则共有多少种不同的取法？ 

解析：

 $C^3_5$*3+3(底面一中点，底面一顶点，中间一中点，可构成一个平面)

答案：**33**

---

---
## 博弈

---

10、桌上有若干枚棋子，甲、乙两人玩轮流取棋子游戏，每次可取1枚、3枚或4枚，但不可取2枚，当无棋子取时算输。甲、乙两人都是玩取棋子游戏的绝顶高手，从不会失误。现甲、乙两人共玩了三局，先手分别是，甲，乙，甲，三局游戏开始时棋子枚数分别是7，13，21。问甲、乙双方在三局游戏中的必胜方分别是（）？
A．乙 乙 甲		B. 甲 乙 甲
C．乙 乙 乙		D. 乙 甲 乙

解析

f[0]=0;

f[1]=1;

f[2]=0;

f[3]=1;

f[4]=1;

f[5]=0;

f[6]=1;

f[7]=0;

f[8]=1;

f[9]=1;

f[10]=1;

f[11]=1;

f[12]=0;

f[13]=1;

f[14]=0;

f[15]=1;

f[16]=1;

f[17]=1;

f[18]=1;

f[19]=0;

f[20]=1;

f[21]=0;

答案：**C**

--

---

## 查找&排序

12.同时查找2n个数中的最大值和最小值，最少比较次数为（   ）。 
A. 3(n-2)/2     B. 4n-2     C. 3n-2     D. 2n-2 

解析：

/* 
网上题解：
前两个数比较，大的为最大值，小的为最小值，用掉1次；
还剩下2*（n-1)个数，每两个比较大的再和最大值比较，小的再和最小值比较，一共是3*（n-1)次
所以加一起就是（3*n-2）次 
*/

1 2 | （3 4） （5 6） （7 8）（9 10）
第一次
（x y)比大小，大的和MAXA比，小的和MINA比，共三次
综上所述：ans=1+(3 * (n-1))=3 * n-2

答案:**A**

---

6．当采用分块查找时，数据的组织方式为  (    )  
A．数据分成若干块，每块内数据有序
B．数据分成若干块，每块内数据不必有序，但块间必须有序，每块内最大（或最小）的数据组成索引块
C. 数据分成若干块，每块内数据有序，每块内最大（或最小）的数据组成索引块
D. 数据分成若干块，每块（除最后一块外）中数据个数需相同

解析:

答案:**B**

---

5．对22个记录的有序表作折半查找，当查找失败时，==至少==需要比较（   ）次关键字。
A．3            B．4          C．5           D．6

解析:

答案:**B**

---

33．在待排序序列局部有序时，效率最高的排序算法是(       )。
A. 直接选择排序   B. 直接插入排序   C. 快速排序      D.归并排序

解析:

直接插入排序应当指从i往前为i找位置，并和比它大的前一个交换

答案:**B**

---

34.下列排序算法中，（）算法会出现下面情况：在最后一趟结束之前，所有元素不在其最终的位置上。
​	A．堆排序			B．冒泡排序
​	C．快速排序　　　	D．插入排序

解析:

x1 x2 x3 x4 x5 x6 x7 x8 x9 x10

​						最小

答案:**D**

---

24、下列各项关于内部排序与外部排序的说法正确的是（）。
A．与内部排序相比，外部排序待排序数据量大       
B．内部排序过程是在计算机内存中进行的         
C．外部排序的效率衡量标准是读写外存次数      
D．外部排序全过程均不在内存

解析:

内部排序：待排序记录存放在计算机随机存储器中（说简单点，就是**内存**）进行的排序过程。

外部排序：待排序记录的数量很大，以致于内存不能一次容纳全部记录，所以在排序过程中**需要对外存进行访问**的排序过程。

答案:**ABC**

---

14.关于杂凑查找（哈希查找）说法不正确的有(    )                  
​    A、采用链地址法解决冲突时，查找一个元素的时间是相同的
​    B、采用链地址法解决冲突时，若插入规定总是在链首，则插入任一个元素的时间是相同的
​    C、用链地址法解决冲突易引起聚集现象
​    D、再哈希法不易产生聚集

解析: 

C链地址和探测一样，群聚不是链地址引起的，而是哈希算法

B链首才是O(1);

答案:**AC**

---

15.设哈希表长为14，哈希函数是H(key)=key%11,表中已有数据的关键字为15，38，61，84共四个，现要将关键字为49的结点加到表中，用二次探测再散列法解决冲突，则放入的位置是(    ) 
​       A．8         B．3         C．5       D．9 

解析:

答案:**B**

| 0    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|      |      |      |      | 15   | 38   | 61   | 84   |      |      |      |
|      |      |      |      | 2    | 1    | 3    |      |      | 4    |      |



---

12．散列表的平均查找长度（    ）。
A．	与处理冲突方法有关而与表的长度无关
B．	与处理冲突方法无关而与表的长度有关
C．	与处理冲突方法有关且与表的长度有关
D．	与处理冲突方法无关且与表的长度无关

解析:

答案:**A**

---

15.以下程序段实现了找第二小元素的算法。输入是n个不等的数构成的数组S，输出S中

第二小的数SecondMin。在最坏情况下，该算法需要做（   ）次比较。

![](http://zjqyy.top/pic/3.png)

解析:

前两个数比较用掉1次，剩下（n-2)个数
最坏的情况剩下每个数比较两次
所以再加起来，得C

答案:**C**

---
![](http://www.zjqyy.top/pic/7.png)
答案:**D**

---

11、在待排序的数据表已经为有序时，下列排序算法中时间复杂度会减少的是（）。
A、	堆排序 B、希尔排序  C、冒泡排序  D、插入排序  

解析：正常的冒泡排序不带跳出优化
答案：**BD**

---

16、下列排序算法中，哪些排序是不稳定的（）。
A、快速排序   B、选择排序  
C、基数排序   D、希尔排序

解析：基数排序是稳定的
答案：**ABD** 

---

```c++
2. (寻找等差数列)  有一些长度相等的等差数列（数列中每个数都为0~59的整数），设长度均为L，将等差数列中的所有数打乱顺序放在一起。现在给你这些打乱后的数，问原先，L最大可能为多大？先读入一个数n（1<=n<=60），再读入n个数，代表打乱后的数。输出等差数列最大可能长度L。

#include <iostream>
using namespace std;

int hash[60];
int n, x, ans, maxnum;

int work(int now) {
	int first, second, delta, i;
	int ok;
	while (      ①       && !hash[now])
		++now;
	if (now > maxnum)
		return 1;
	first = now;
	for (second = first; second <= maxnum; second++)
		if (hash[second]) {
			delta =       ②       ;  
			if (first + delta *    ③      > maxnum) 
				break;
			if (delta == 0)
				ok = (      ④      ); 
			else{
				ok = 1;
				for (i = 0; i < ans; i++)
					ok =     ⑤     && (hash[first+delta*i]); 
			}
			if (ok){
				for (i = 0; i < ans; i++)
					hash[first+delta*i]--;
				if (work(first)) 
					return 1;
				for (i = 0; i < ans; i++)
					hash[first+delta*i]++;
			}
		}
	return 0;
}

int main(){
	int i;
	memset(hash, 0, sizeof(hash));
	cin >> n;
	maxnum = 0;
	for (i = 0; i < n; i++){
		cin >> x;
		hash[x]++;
		if (x > maxnum)
			maxnum = x;
	}
	for (ans = n; ans >= 1; ans--)
		if ( n%ans==0 &&     ⑥     ) {
			cout << ans << endl;
			break;
		}
	return 0;
}
```

4是hash[first]>=ans,即差为０

| 6    | 3/3  | **now<=maxnum**                                              |
| ---- | ---- | ------------------------------------------------------------ |
| 7    | 3/3  | **second-first**                                             |
| 8    | 3/3  | **(ans-1)**                                                  |
| 9    | 0/3  | ~~ 								0								~~   							  								hash[first]>=ans |
| 10   | 3/3  | **ok**                                                       |
| 11   | 3/3  | **work(0)**                                                  |

---

---

## 暴力模拟

2、给定如图所示的正方形（n=3）。我们可以在这个正方形的某个格子上放置大炮。但是，如果大炮在同一行或者同一列，他们就会互相攻击到。大炮数量为2，请你求出可能的放置方案总数，使得大炮互相不会攻击到。现在告诉你n=3时，总数为46，则n=4时，总数为_______。
![](http://zjqyy.top/pic/5.JPG)
如图所示：上面为n=3的正方形，下面三幅图，前两幅可以互相攻击到，第三幅无法互相攻击到。

解析：
***图要画对！！！（I died)***
考虑左上角×4+中间的十字

答案:**206**

---

7、下列形状的三角形中，字幕a-i分别表示数字1,2,3,…,9
```
      a
    b   c
  d       e   
f   g   h   i
```
字母a-i同时满足下列条件：
(1)	a<f<i
(2)	b<d,g<h,c<e
(3)	a+b+d+f=f+g+h+i=i+e+c+a=19￼
则满足条件的三角形个数为（）。
A、2  B、3   C、4  D、5
解析：
|$a+b+d+f+f+g+h+i+i+e+c+a=19*3=57$
|$a+b+c+d+f+g+h+i=45$
得到
$a+f+i=12$

```
      1
    7   c
  8       e   
2   g   h   9
```
WA
```
      1
    6   ?
  9       ?   
3   g   h   8
```
WA
```
      1
    5   3
  9       8   
4   2   6   7
```
AC
```
      1
    6   2
  8       9   
4   3   5   7
```
AC
```
      1
    4   ?
  9       ?   
5   g   h   6
```
WA
```
      2
    5   4
  9       6   
3   1   8   7
```
AC
```
      2
    6   1
  8       9   
3   4   5   7
```
AC
```
      2
    5   ?
  8       ?   
4   g   h   6
```
WA
```
      3
    ?   c
  ?       e   
4   g   h   5
```
WA

综上所述： ans=4;

答案:**C**

---

```c++
#include<iostream>
#include<iomanip>
using namespace std;
int a[7];
int main() {
	for(int i=2;i<=6;i++) a[i]=i+1;
	int m;
	do {
		m=2;
		for(int i=3;i<=6;i++) if(a[m]>a[i]) m=i;
		a[m]=a[m]+m;
		m=1;
		for(int i=2;i<=5;i++)
			for(int j=i+1;j<=6;j++)
				if(a[i]<a[j]) m=0;
	} while(m==0);
	cout<<a[2]<<endl;
	return 0;
}
```

输出：  

5 4 5 6 7 
5 7 5 6 7 
7 7 5 6 7 
7 7 9 6 7 
7 7 9 11 7 
9 7 9 11 7 
9 10 9 11 7 
9 10 9 11 13 
11 10 9 11 13 
11 10 13 11 13 
11 13 13 11 13 
13 13 13 11 13 
13 13 13 16 13 
15 13 13 16 13 
15 16 13 16 13 
15 16 17 16 13 
15 16 17 16 19 
17 16 17 16 19 
17 19 17 16 19 
17 19 17 21 19 
19 19 17 21 19 
19 19 21 21 19 
21 19 21 21 19 
21 22 21 21 19 
21 22 21 21 25 
23 22 21 21 25 
23 22 25 21 25 
23 22 25 ==26== 25
23 25 25 26 25 
25 25 25 26 25 
27 25 25 26 25 
27 28 25 26 25 
27 28 29 26 25 
27 28 29 26 31 
27 28 29 31 31 
29 28 29 31 31 
29 31 29 31 31 
31 31 29 31 31 
31 31 33 31 31 
33 31 33 31 31 
33 34 33 31 31 
33 34 33 36 31 
33 34 33 36 37 
35 34 33 36 37 
35 34 37 36 37 
35 37 37 36 37 
37 37 37 36 37 
37 37 37 41 37 
39 37 37 41 37 
39 40 37 41 37 
39 40 41 41 37 
39 40 41 41 43 
41 40 41 41 43 
41 43 41 41 43 
43 43 41 41 43 
43 43 45 41 43 
43 43 45 46 43 
45 43 45 46 43 
45 46 45 46 43 
45 46 45 46 49 
47 46 45 46 49 
47 46 49 46 49 
47 49 49 46 49 
47 49 49 51 49 
49 49 49 51 49 
51 49 49 51 49 
51 52 49 51 49 
51 52 53 51 49 
51 52 53 51 55 
53 52 53 51 55 
53 52 53 56 55 
53 55 53 56 55 
55 55 53 56 55 
55 55 57 56 55 
57 55 57 56 55 
57 58 57 56 55 
57 58 57 56 61 
57 58 57 61 61 
59 58 57 61 61 
59 58 61 61 61 
59 61 61 61 61 
61 61 61 61 61 
61

其实只是找２，３，４，==５==，６的最小公约数＋１

---

```c++
#include <iostream>
#include <cmath>
using namespace std;
const int n=7,m=6;
float disp(int x1,int y1,int x2,int y2) {
	return sqrt((x1-x2)*(x1-x2)+(y1-y2)*(y1-y2));
}
int main() {
	int i,j,x0,y0,x1,y1,x2,y2;
	float d;
	int p;
	int g[n+1][m+1];
	for(i=0; i<=n; i++)
		for(j=0; j<=m; j++)
			g[i][j]=0;
	cin>>x1>>y1>>x2>>y2;
	g[x1][y1]=1;
	g[x2][y2]=1;
	p=1;
	while(p) {
		p=0;
		d=disp(x1,y1,x2,y2);
		x0=x1;
		y0=y1;
		for(i=4; i<=n; i++)
			for(j=0; j<=m; j++)
				if(d>disp(i,j,x2,y2)&&g[i][j]==0) {
					d=disp(i,j,x2,y2);
					x0=i;
					y0=j;
				}
		if(x0!=x1||y0!=y1) {
			x1=x0;
			y1=y0;
			p=1;
			g[x1][y1]=1;
		}
		d=disp(x1,y1,x2,y2);
		x0=x2;
		y0=y2;
		for(i=0; i<=3; i++)
			for(j=0; j<=m; j++)
				if(d<disp(x1,y1,i,j)&&g[i][j]==0) {
					d=disp(x1,y1,i,j);
					x0=i;
					y0=j;
				}
		if(x0!=x2||y0!=y2) {
			x2=x0;
			y2=y0;
			p=1;
			g[x2][y2]=1;
		}
	}
	cout<<x1<<" "<<y1<<" "<<x2<<" "<<y2<<endl;
	return 0;
}
//输入7 6 0 0 
```

输出：4 3 0 2
解析：先在右半个矩阵中找寻一个点，使得它与点（x2，y2）距离尽可能大且该点没有被访问过。然后在左半个矩阵中找寻一个点，使得它与点（x1，y1）距离尽可能小且该点没有被访问过．

模拟即可

---

---

---

##无法分类，复杂的看程序写结果

---

---

---

---

---
# **知识梳理**

---

---

## XY经验

**第一题**

细心，稳

**第二题**

用数学方法
加法原理和乘法原理
枚举，分治

**第三题**

1.模拟
2.模型
3.功能
4.分析结构，说明部分变量的作用（全局变量和基本变量）
5.列表记录变量变化
6.分块记录
7手算，不能跳步，口算

**第四题**

1.认真读题，分析已知和所求
2.分析结构
3.从输入输出入手
4.分块，分清层次嵌套
5.全局变量和基本变量
6.对照自己平时解决问题的方法
7.找突破口，找空的内在联系

---

---

---



## 信息技术基本知识

---

#### 送上巨佬wangyicheng的笔记

https://www.zybuluo.com/scrolllock/note/1299650

---

信息是以。。。等表示的**实际内容**

---
## 计算机发展&历史时间

---

ENIAC 1946
电子管46-58
晶体管59-64
中小集成电路65-71
大，超大集成电路71-now

---
摩尔定律：当价格不变时，集成电路上可容纳的元器件的数目，约每隔18-24个月便会增加一倍，性能也将提升一倍。

---

计算机软件保护条例：1991年6月

---

世界上第一款*商用计算机微处理器     1971 英特尔INTEL 4004 4位

---

EDSAC是世界上第一台实际运行的[存储程序式](https://zh.wikipedia.org/wiki/%E5%86%AF%C2%B7%E8%AF%BA%E4%BC%8A%E6%9B%BC%E7%BB%93%E6%9E%84)[电子计算机](https://zh.wikipedia.org/wiki/%E7%94%B5%E5%AD%90%E8%AE%A1%E7%AE%97%E6%9C%BA)

存储程序计算机在体系结构上主要特点有：

1. 以运算单元为中心
2. 采用存储程序原理
3. 存储器是按地址访问、线性编址的空间
4. 控制流由指令流产生
5. 指令由操作码和地址码组成
6. 数据以二进制编码

---

---



## 硬件

---
### 硬件系统

---
硬件系统是指构成计算机的物理设备，即由机械、光、电、磁器件构成的具有计算、控制、存储、输入和输出功能的实体部件。如CPU、存储器、软盘驱动器、硬盘驱动器、光盘驱动器、主机板、各种卡及整机中的主机、显示器、打印机、绘图仪、调制解调器等等，整机硬件也称“硬设备”。 随着电子系统的复杂化，系统设计已经成为一门重要的学科，传统的反复试验法已经越来越不适应时代的发展。发展迅速的软硬件协同设计技术越来越受到人们的重视。它是在系统目标要求的指导下，通过综合分析系统软硬件功能及现有资源，最大限度地挖掘系统软硬件之间的并发性，协调设计软硬件体系结构，以使系统工作在最佳工作状态。

---
### ROM&RAM&Cache

---

ROM:Read-Only Memory
RAM:random access memory
Cache:高速缓存
寄存器（最快，但不是内存）

---
### CPU

CPU的主频，即CPU内核工作的时钟频率（CPU Clock Speed）。通常所说的某某CPU是多少兆赫的，而这个多少兆赫就是“CPU的主频”。很多人认为CPU的主频就是其运行速度，其实不然。CPU的主频表示在CPU内数字脉冲信号震荡的速度，与CPU实际的运算能力并没有直接关系。由于主频并不直接代表运算速度，所以在一定情况下，很可能会出现主频较高的CPU实际运算速度较低的现象。

电脑技术中对CPU在单位时间内（同一时间）能一次处理的二进制数的位数叫字长。

字节大小取决于ALU寄存器的容量和连接着这些寄存器的电路性能

32位最多访问2^32个字节

---
### 总线

总线（Bus）是计算机各种功能部件之间传送信息的公共通信干线，它是由导线组成的传输线束， 按照计算机所传输的信息种类，计算机的总线可以划分为数据总线、地址总线和控制总线，分别用来传输数据、数据地址和控制信号。总线是一种内部结构，它是cpu、内存、输入、输出设备传递信息的公用通道，主机的各个部件通过总线相连接，外部设备通过相应的接口电路再与总线相连接，从而形成了计算机硬件系统。在计算机系统中，各个部件之间传送信息的公共通路叫总线，微型计算机是以总线结构来连接各个功能部件的。

数据总线:传输数据
地址总线:数据地址
控制总线:控制信号

---

BIOS固定在主板上的ROM

---

---

---

---

---

---

## 存储&编码

---
### ASCII

美国信息交换标准代码
128个
00H~7FH
00000...000
~
01111...111
一个字节
####（汉字交换码）内码：
GB2312(国标)
两个字节
最高位为1
一级字库3755 拼音排序
二级字库3008 偏旁排序

处理码：对每一台机器
（字形存储码）输出码：点阵，仅用于输出

---
### 图形

点阵
分辨率：通常1920×1080 横像素×竖像素
每个点256种颜色（像素点8位）/32位真彩色（举个栗子）
不要忘了bit和byte的转化

---
### 视频

容量=图片容量×帧频×时间

---
### 声音

采样合样化 

https://baike.baidu.com/item/%E5%A3%B0%E9%9F%B3%E5%90%88%E6%88%90%E4%B8%8E%E9%87%87%E6%A0%B7%E6%8A%80%E6%9C%AF/12463842

容量=采样频率(1/t)×量化位数(bit)×时间(t)×声道数/8

---
### 原码，反码，补码

正数都一样
|+0=00000000|
|-0=10000000|--原码

|+0=00000000|
|-0=11111111|--反码

|+0=00000000|
|-0= ~~(1)~~ 00000000|--补码

-0表示最小数

负数将其数值按位取反+1

---

1字节(byte)=8位（bit）
英语字母，字符，阿拉伯数字：1字节=8位
汉字：2字节=16位

---
---

### 汉字编码(XY)

区位码-->国标码-->机内码
​      +32             +128
​    前32危险  png首位+1（防和ASCII冲突）
​    

区位码转换成国标码是区位码加上2020H（注意是16进制的）国标码转成机内码是国标码加上8080H（也是16进制） 因为汉字是由两个字节组成的 国标码和区位码的区别就是 国标码的两个字节的最高位为0，而机内码的最高位为1，所以就要加上8080H（化成2进制的话就是每个字节的最高位变1）



字形码：通常用16×16点阵来显示汉字

---

---
### 指令

由操作码和操作数组成

操作码指计算机程序中所规定的要执行操作的那一部分指令或字段(通常用代码表示)，其实就是指令序列号，用来告诉CPU需要执行哪一条指令。

操作数是运算符作用于的实体，是表达式中的一个组成部分，它规定了指令中进行数字运算的量 。

---
### Linux UNIX

Linux是一种开源电脑操作系统内核。它是一个用C语言写成，符合POSIX标准的类Unix操作系统。 [1] 
Linux最早是由芬兰黑客 Linus Torvalds为尝试在英特尔x86架构上提供自由免费的类Unix操作系统而开发的。该计划开始于1991年，在计划的早期有一些Minix 黑客提供了协助，而今天全球无数程序员正在为该计划无偿提供帮助。


Linux是一套免费使用和自由传播的类Unix操作系统，是一个基于POSIX和UNIX的多用户、多任务、支持多线程和多CPU的操作系统。它能运行主要的UNIX工具软件、应用程序和网络协议。它支持32位和64位硬件。Linux继承了Unix以网络为核心的设计思想，是一个性能稳定的多用户网络操作系统。
Linux操作系统诞生于1991 年10 月5 日（这是第一次正式向外公布时间）

严格来讲，Linux这个词本身只表示Linux内核，但实际上人们已经习惯了用Linux来形容整个基于Linux内核，并且使用GNU 工程各种工具和数据库的操作系统。

linux创始人林纳斯·托瓦兹 

1995年1月，Bob Young创办了RedHat（小红帽），以GNU/Linux为核心，集成了400多个源代码开放的程序模块，搞出了一种冠以品牌的Linux，即RedHat Linux,称为Linux"发行版"，在市场上出售。这在经营模式上是一种创举。

Linux的基本思算速度, 单位: MIPS每秒百万条想有两点：第一，一切都是文件；第二，每个软件都有确定的用途。

linux 完全免费,完全兼容POSIX1.0标准,多用户、多任务,良好的界面,支持多种平台



UNIX操作系统，是一个强大的多用户、多任务操作系统，支持多种处理器架构，按照操作系统的分类，属于分时操作系统，最早由KenThompson、Dennis Ritchie和Douglas McIlroy于1969年在AT&T的贝尔实验室开发。目前它的商标权由国际开放标准组织所拥有，只有匹配单一UNIX规范的UNIX系统才能使用UNIX这个名称，否则只能称为类UNIX（UNIX-like）。

---
## 计算机语言

1.机器语言：机器直接识别
2.汇编语言：可调用硬件，助记符编写程序，符号代替机器指令，可移植性不强
3.高级语言：
编译方式：生成目标程序
效率高，可靠性高，可移植性强
解释方式：解释一条，执行一条 Python

---
### 面向对象

第一：SIMULA67
第二：Smalltalk
动态绑定和交互式开发环境

C语言，Pascal面向过程
C++,Object Psacal面向对象

---
## 关于数

---

### 进制转换

---

转10进制
乘权重相加

转二进制
整数除2取余
小数×2取整

二进制转16/8/4进制
4/3/2位划分后转换（小数和整数都可以）

---

H字母表示十六进制数（Hex），是逢十六进一，即基R=16=，通常在表示时用尾部标志H或下标16以示区别。

---
### 浮点数

尾数和阶码

![img](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4d/Float_mantissa_exponent.png/220px-Float_mantissa_exponent.png)



十进制浮点数的表示方式

在[计算机科学](https://zh.wikipedia.org/wiki/%E8%A8%88%E7%AE%97%E6%A9%9F%E7%A7%91%E5%AD%B8)中，**浮点**（英语：floating point，缩写为FP）是一种对于[实数](https://zh.wikipedia.org/wiki/%E5%AF%A6%E6%95%B8)的近似值数值表现法，由一个[有效数字](https://zh.wikipedia.org/wiki/%E6%9C%89%E6%95%88%E6%95%B0%E5%AD%97)（即**尾数**）加上[幂数](https://zh.wikipedia.org/wiki/%E5%86%AA%E6%95%B8)来表示，通常是乘以某个[基数](https://zh.wikipedia.org/wiki/%E5%9F%BA%E6%95%B0)的整数次[指数](https://zh.wikipedia.org/wiki/%E6%8C%87%E6%95%B0)得到。以这种表示法表示的数值，称为**浮点数**（floating-point number）。利用浮点进行运算，称为*浮点计算*，这种运算通常伴随着因为无法精确表示而进行的近似或舍入。

计算机使用浮点数运算的主因，在于计算机使用二进位制的运算。例如：4÷2=2，4=100(2)、2=010(2)，在二进制相当于退一位数。则1.0÷2=0.5=0.1(2)也就是![{\frac {1}{2}}](https://wikimedia.org/api/rest_v1/media/math/render/svg/a11cfb2fdb143693b1daf78fcb5c11a023cb1c55)。依此类推二进制的0.01(2)就是十进制![{\displaystyle {\frac {1}{2^{2}}}}](https://wikimedia.org/api/rest_v1/media/math/render/svg/5df095c48909bf64aa399e2fc4356d7917f113ae)=![\frac{1}{4}](https://wikimedia.org/api/rest_v1/media/math/render/svg/a2dfb63ee75ec084f2abb25d248bc151a2687508)=0.25。由于十进位制无法准确换算成二进位制的部分小数，如0.1，因此只能使用近似值的方式表达。

这种表示方法类似于基数为10的[科学记数法](https://zh.wikipedia.org/wiki/%E7%A7%91%E5%AD%A6%E8%AE%B0%E6%95%B0%E6%B3%95)，在计算机上，通常使用2为基数的幂数来表示。一个浮点数*a*由两个数*m*和*e*来表示：*a = m × be*。在任意一个这样的系统中，我们选择一个[基数](https://zh.wikipedia.org/wiki/%E5%9F%BA%E6%95%B0)*b*（记数系统的基）和[精度](https://zh.wikipedia.org/wiki/%E7%B2%BE%E5%BA%A6)*p*（即使用多少位来存储）。*m*（即[尾数](https://zh.wikipedia.org/w/index.php?title=%E5%B0%BE%E6%95%B0&action=edit&redlink=1)）是形如±d**.**ddd...ddd的p位数（每一位是一个介于0到b-1之间的整数，包括0和b-1）。如果*m*的第一位是非0整数，*m*称作**正规化**的。有一些描述使用一个单独的符号位（*s* 代表+或者-）来表示正负，这样*m*必须是正的。*e*是指数。

这种表示法的设计，来自于对于值的表现范围，与[精密度](https://zh.wikipedia.org/wiki/%E7%B2%BE%E5%AF%86%E5%BA%A6)之间的取舍：可以在某个固定长度的存储空间内表示出某个实数的近似值。例如，一个指数范围为±4的4位[十进制](https://zh.wikipedia.org/wiki/%E5%8D%81%E8%BF%9B%E5%88%B6)浮点数可以用来表示43210，4.321或0.0004321，但是没有足够的精度来表示432.123和43212.3（必须近似为432.1和43210）。当然，实际使用的位数通常远大于4。

此外，世界上第一款*商用计算机微处理器浮点数表示法通常还包括一些特别的数值：+∞和−∞（正负无穷大）以及NaN（'Not a Number'）。无穷大用于数太大而无法表示的时候，NaN则指示非法操作或者无法定义的结果。

其中，无穷大，可表示为inf，在内存中的值是阶码为全1，尾数全0。而NaN在内存中的值则是阶码全1，尾数不全0。

---

---

---

## 网络

---

### OSI七层模型

**应用层**
提供OSI用户服务，例如事务处理程序、文件传送协议和网络管理等。
***POP,DNS,FTP,HTTP,SSH***

**表达层**
代表应用进程协商数据表示；完成数据转换、格式化和文本压缩。
***弃***

**会话层**
提供两进程之间建立、维护和结束会话连接的功能；提供交互会话的管理功能，如三种数据流方向的控制，即一路交互、两路交替和两路同时会话模式 。
***弃***

**传输层**
提供建立、维护和拆除传送连接的功能；选择网络层提供最合适的服务；在系统之间提供可靠的透明的数据传送，提供端到端的错误恢复和流量控制
***TCP协议，UDP协议***

**网络层**
控制分组传送系统的操作、路由选择、用户控制、网络互连等功能，它的作用是将具体的物理传送对高层透明。
***IP协议,路由器***

**数据链路层**
在网络层实体间提供数据发送和接收的功能和过程；提供数据链路的流控。
***网卡，网桥***

**物png理层**
提供为建立、维护和拆除物理链路所需要的机械的、电气的、功能的和规程的特性；有关的物理链路上传输非结构的位流以及故障检测指示。
***中继器***

---

### TCP/IP协议

网络中计算机与计算机之间的通行依靠协议进行
Transmission Control Protocol/InternetProtocol的简写，中译名为传输控制协议/因特网互联协议，又名网络通讯协议，是Internet最基本的协议、Internet国际互联网络的基础，由网络层的IP协议和传输层的TCP协议组成。

TCP/IP定义了电子设备如何连入因特网，以及数据如何在它们之间传输的标准。协议采用了4层的层级结构，每一层都呼叫它的下一层所提供的协议来完成自己的需求。

通俗而言：TCP负责发现传输的问题，一有问题就发出信号，要求重新传输，直到所有数据安全正确地传输到目的地。而IP是给因特网的每一台联网设备规定一个地址。

#### 4层模型

![](http://zjqyy.top/pic/8.png)

---

### IP地址的划分

A类 0|......|...............| 
B类 10|......|..............| 
C类 110|......|.............| 

![](http://zjqyy.top/pic/4.jpg)

---

### DNS Domain Name System

域名系统（Domain Name System缩写[DNS](https://baike.baidu.com/item/DNS)，Domain Name被译为域名）是因特网的一项核心服务，它作为可以将[域名](https://baike.baidu.com/item/%E5%9F%9F%E5%90%8D/86062)和[IP地址](https://baike.baidu.com/item/IP%E5%9C%B0%E5%9D%80)相互映射的一个[分布式数据库](https://baike.baidu.com/item/%E5%88%86%E5%B8%83%E5%BC%8F%E6%95%B0%E6%8D%AE%E5%BA%93/1238109)，能够使人更方便的访问互联网，而不用去记住能够被机器直接读取的IP数串。

------

### internet

Internet是在[美国](https://baike.baidu.com/item/%E7%BE%8E%E5%9B%BD)早期的军用[计算机](https://baike.baidu.com/item/%E8%AE%A1%E7%AE%97%E6%9C%BA)网ARPANET（阿帕网）的基础上经过不断发展变化而形成的

---

#### 万维网 WWW

**万维网**（英语：*World Wide Web*），亦作“WWW”、“Web”，是一个由许多互相链接的[超文本](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC)组成的系统，通过[互联网](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91)访问[[1\]](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91#cite_note-1)。英国科学家[蒂姆·伯纳斯-李](https://zh.wikipedia.org/wiki/%E8%92%82%E5%A7%86%C2%B7%E4%BC%AF%E7%BA%B3%E6%96%AF-%E6%9D%8E)于1989年发明了万维网。1990年他在瑞士[CERN](https://zh.wikipedia.org/wiki/CERN)的工作期间编写了第一个[网页浏览器](https://zh.wikipedia.org/wiki/%E7%B6%B2%E9%A0%81%E7%80%8F%E8%A6%BD%E5%99%A8)[[2\]](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91#cite_note-2)[[3\]](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91#cite_note-AHT-3)。网页浏览器于1991年在CERN向外界发表，1991年1月开始发展到其他研究机构，1991年8月在互联网上向公众开放。

万维网是[信息时代](https://zh.wikipedia.org/wiki/%E8%B3%87%E8%A8%8A%E6%99%82%E4%BB%A3)发展的核心，也是数十亿人在互联网上进行交互的主要工具[[4\]](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91#cite_note-4)[[5\]](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91#cite_note-5)[[6\]](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91#cite_note-6)。[网页](https://zh.wikipedia.org/wiki/%E7%B6%B2%E9%A0%81)主要是文本文件[格式化](https://zh.wikipedia.org/wiki/%E6%A0%BC%E5%BC%8F%E5%8C%96%E6%96%87%E6%9C%AC)和[超文本标记语言](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E4%BB%B6%E6%A8%99%E7%A4%BA%E8%AA%9E%E8%A8%80)（HTML）。除了格式化文字之外，网页还可能包含[图片](https://zh.wikipedia.org/wiki/%E5%9C%96%E7%89%87)、[视频](https://zh.wikipedia.org/wiki/%E5%BD%B1%E7%89%87)、[声音](https://zh.wikipedia.org/wiki/%E8%81%B2%E9%9F%B3)和软件组件，这些组件会在用户的网页浏览器中呈现为[多媒体](https://zh.wikipedia.org/wiki/%E5%A4%9A%E5%AA%92%E9%AB%94)内容的连贯页面。

万维网并不等同[互联网](https://zh.wikipedia.org/wiki/%E7%B6%B2%E9%9A%9B%E7%B6%B2%E8%B7%AF)，万维网只是互联网所能提供的服务其中之一，是靠着互联网运行的一项服务。

---

#### 远程登录SSH

**Secure Shell**（安全外壳协议，简称**SSH**）是一种加密的[网络传输协议](https://zh.wikipedia.org/wiki/%E7%BD%91%E7%BB%9C%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)，可在不安全的网络中为网络服务提供安全的传输环境[[1\]](https://zh.wikipedia.org/wiki/Secure_Shell#cite_note-rfc4251-1)。SSH通过在网络中创建[安全隧道](https://zh.wikipedia.org/w/index.php?title=%E5%AE%89%E5%85%A8%E9%9A%A7%E9%81%93&action=edit&redlink=1)来实现SSH客户端与服务器之间的连接[[2\]](https://zh.wikipedia.org/wiki/Secure_Shell#cite_note-rfc4252-2)。虽然任何网络服务都可以通过SSH实现安全传输，SSH最常见的用途是远程登录系统，人们通常利用SSH来传输[命令行界面](https://zh.wikipedia.org/wiki/%E5%91%BD%E4%BB%A4%E8%A1%8C%E7%95%8C%E9%9D%A2)和远程执行命令。使用频率最高的场合[类Unix系统](https://zh.wikipedia.org/wiki/%E7%B1%BBUnix%E7%B3%BB%E7%BB%9F)，但是[Windows](https://zh.wikipedia.org/wiki/Windows)操作系统也能有限度地使用SSH。2015年，微软宣布将在未来的操作系统中提供原生SSH协议支持[[3\]](https://zh.wikipedia.org/wiki/Secure_Shell#cite_note-3)。

在设计上，SSH是[Telnet](https://zh.wikipedia.org/wiki/Telnet)和非安全[shell](https://zh.wikipedia.org/wiki/Unix_shell)的替代品。Telnet和Berkeley [rlogin](https://zh.wikipedia.org/w/index.php?title=Rlogin&action=edit&redlink=1)、[rsh](https://zh.wikipedia.org/wiki/%E8%BF%9C%E7%A8%8B%E5%A4%96%E5%A3%B3)、[rexec](https://zh.wikipedia.org/w/index.php?title=Rexec&action=edit&redlink=1)等协议采用[明文](https://zh.wikipedia.org/wiki/%E6%98%8E%E6%96%87)传输，使用不可靠的密码，容易遭到监听、[嗅探](https://zh.wikipedia.org/wiki/%E6%95%B8%E6%93%9A%E5%8C%85%E5%88%86%E6%9E%90%E5%99%A8)和[中间人攻击](https://zh.wikipedia.org/wiki/%E4%B8%AD%E9%97%B4%E4%BA%BA%E6%94%BB%E5%87%BB)[[4\]](https://zh.wikipedia.org/wiki/Secure_Shell#cite_note-4)。SSH旨在保证非安全网络环境（例如[互联网](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91)）中信息加密完整可靠。

不过，SSH也被指出有被嗅探甚至解密的漏洞。早在2011年，[中国的互联网审查机构](https://zh.wikipedia.org/wiki/%E4%B8%AD%E8%8F%AF%E4%BA%BA%E6%B0%91%E5%85%B1%E5%92%8C%E5%9C%8B%E7%B6%B2%E7%B5%A1%E5%AF%A9%E6%9F%A5)已经有能力针对SSH连线的刺探及干扰。[[5\]](https://zh.wikipedia.org/wiki/Secure_Shell#cite_note-5)[[6\]](https://zh.wikipedia.org/wiki/Secure_Shell#cite_note-6)而后[爱德华·斯诺登](https://zh.wikipedia.org/wiki/%E7%88%B1%E5%BE%B7%E5%8D%8E%C2%B7%E6%96%AF%E8%AF%BA%E7%99%BB)泄露的文件也指出，[美国国家安全局](https://zh.wikipedia.org/wiki/%E7%BE%8E%E5%9B%BD%E5%9B%BD%E5%AE%B6%E5%AE%89%E5%85%A8%E5%B1%80)有时能够把SSH协议传输的信息解密出来，从而读出SSH会话的传输内容[[7\]](https://zh.wikipedia.org/wiki/Secure_Shell#cite_note-Spiegel2014-7)。2017年7月6日，非营利组织[维基解密](https://zh.wikipedia.org/wiki/%E7%B6%AD%E5%9F%BA%E8%A7%A3%E5%AF%86)确认[美国中央情报局](https://zh.wikipedia.org/wiki/%E7%BE%8E%E5%9B%BD%E4%B8%AD%E5%A4%AE%E6%83%85%E6%8A%A5%E5%B1%80)已经开发出能够在[Windows](https://zh.wikipedia.org/wiki/Microsoft_Windows)或[Linux](https://zh.wikipedia.org/wiki/Linux)操作系统中窃取SSH会话的工具.

---

**调制解调器**（英语：Modem，**mo**dulator-**dem**odulator的英文缩写）是一个将[数字信号](https://zh.wikipedia.org/wiki/%E6%95%B0%E5%AD%97%E4%BF%A1%E5%8F%B7)[调变](https://zh.wikipedia.org/wiki/%E8%AA%BF%E8%AE%8A)到[模拟信号](https://zh.wikipedia.org/wiki/%E9%A1%9E%E6%AF%94%E4%BF%A1%E8%99%9F)上进行传输，并[解调](https://zh.wikipedia.org/wiki/%E8%A7%A3%E8%AA%BF)收到的模拟信号以得到[数字信号](https://zh.wikipedia.org/wiki/%E6%95%B8%E4%BD%8D%E8%A8%8A%E8%99%9F)的电子设备[[1\]](https://zh.wikipedia.org/wiki/%E8%B0%83%E5%88%B6%E8%A7%A3%E8%B0%83%E5%99%A8#cite_note-1)。它的目标是产生能够方便传输的模拟信号并且能够通过解码还原原来的数字信号。根据不同的应用场合，调制解调器可以使用不同的手段来传送模拟信号，比如使用[光纤](https://zh.wikipedia.org/wiki/%E5%85%89%E7%BA%A4)，[射频](https://zh.wikipedia.org/wiki/%E5%B0%84%E9%A0%BB)无线电或[电话线](https://zh.wikipedia.org/wiki/%E9%9B%BB%E8%A9%B1%E7%B7%9A)等

---

### 常见传输协议

---

**http(s)超文本传输**



**超文本传输协议**（[英文](https://zh.wikipedia.org/wiki/%E8%8B%B1%E6%96%87)：**H**yper**T**ext **T**ransfer **P**rotocol，[缩写](https://zh.wikipedia.org/wiki/%E7%B8%AE%E5%AF%AB)：**HTTP**）是一种用于分布式、协作式和[超媒体](https://zh.wikipedia.org/wiki/%E8%B6%85%E5%AA%92%E9%AB%94)信息系统的[应用层协议](https://zh.wikipedia.org/wiki/%E5%BA%94%E7%94%A8%E5%B1%82)[[1\]](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE#cite_note-ietf2616-1)。HTTP是[万维网](https://zh.wikipedia.org/wiki/%E5%85%A8%E7%90%83%E8%B3%87%E8%A8%8A%E7%B6%B2)的数据通信的基础。

设计HTTP最初的目的是为了提供一种发布和接收[HTML](https://zh.wikipedia.org/wiki/HTML)页面的方法。通过HTTP或者HTTPS协议请求的资源由[统一资源标识符](https://zh.wikipedia.org/wiki/%E7%B5%B1%E4%B8%80%E8%B3%87%E6%BA%90%E6%A8%99%E8%AD%98%E7%AC%A6)（Uniform Resource Identifiers，URI）来标识。

HTTP的发展是由[蒂姆·伯纳斯-李](https://zh.wikipedia.org/wiki/%E6%8F%90%E5%A7%86%C2%B7%E6%9F%8F%E5%85%A7%E8%8C%B2-%E6%9D%8E)于1989年在[欧洲核子研究组织](https://zh.wikipedia.org/wiki/%E6%AD%90%E6%B4%B2%E6%A0%B8%E5%AD%90%E7%A0%94%E7%A9%B6%E7%B5%84%E7%B9%94)（CERN）所发起。HTTP的标准制定由[万维网协会](https://zh.wikipedia.org/wiki/%E5%85%A8%E7%90%83%E8%B3%87%E8%A8%8A%E7%B6%B2%E5%8D%94%E6%9C%83)（World Wide Web Consortium，W3C）和[互联网工程任务组](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E5%B7%A5%E7%A8%8B%E4%BB%BB%E5%8A%A1%E7%BB%84)（Internet Engineering Task Force，IETF）进行协调，最终发布了一系列的[RFC](https://zh.wikipedia.org/wiki/RFC)，其中最著名的是1999年6月公布的 [RFC 2616](https://tools.ietf.org/html/rfc2616)，定义了HTTP协议中现今广泛使用的一个版本——HTTP 1.1。

2014年12月，[互联网工程任务组](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E5%B7%A5%E7%A8%8B%E4%BB%BB%E5%8A%A1%E7%BB%84)（IETF）的Hypertext Transfer Protocol Bis（httpbis）工作小组将[HTTP/2](https://zh.wikipedia.org/wiki/HTTP/2)标准提议递交至[IESG](https://zh.wikipedia.org/w/index.php?title=Internet_Engineering_Steering_Group&action=edit&redlink=1)进行讨论[[2\]](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE#cite_note-2)，于2015年2月17日被批准。[[3\]](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE#cite_note-approval2-3) HTTP/2标准于2015年5月以RFC 7540正式发表，取代HTTP 1.1成为HTTP的实现标准

**超文本传输安全协议**（英语：**Hypertext Transfer Protocol Secure**，[缩写](https://zh.wikipedia.org/wiki/%E7%B8%AE%E5%AF%AB)：**HTTPS**，常称为**HTTP over TLS**，**HTTP over SSL**或**HTTP Secure**）是一种透过[计算机网络](https://zh.wikipedia.org/wiki/%E8%A8%88%E7%AE%97%E6%A9%9F%E7%B6%B2%E7%B5%A1)进行安全通信的[传输协议](https://zh.wikipedia.org/wiki/%E7%B6%B2%E8%B7%AF%E5%82%B3%E8%BC%B8%E5%8D%94%E5%AE%9A)。HTTPS经由[HTTP](https://zh.wikipedia.org/wiki/HTTP)进行通信，但利用[SSL/TLS](https://zh.wikipedia.org/wiki/%E4%BC%A0%E8%BE%93%E5%B1%82%E5%AE%89%E5%85%A8)来加密数据包。HTTPS开发的主要目的，是提供对[网站](https://zh.wikipedia.org/wiki/%E7%B6%B2%E7%AB%99)服务器的[身份认证](https://zh.wikipedia.org/wiki/%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81)，保护交换数据的隐私与[完整性](https://zh.wikipedia.org/wiki/%E5%AE%8C%E6%95%B4%E6%80%A7)。这个协议由[网景](https://zh.wikipedia.org/wiki/%E7%B6%B2%E6%99%AF)公司（Netscape）在1994年首次提出，随后扩展到[互联网](https://zh.wikipedia.org/wiki/%E7%B6%B2%E9%9A%9B%E7%B6%B2%E8%B7%AF)上。

历史上，HTTPS连接经常用于[万维网](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91)上的交易支付和企业信息系统中敏感信息的传输。在2000年代晚期和2010年代早期，HTTPS开始广泛使用于保护所有类型网站上的网页真实性，保护账户和保持用户通信，身份和网络浏览的私密性。

---

**ftp文件传输**

The **File Transfer Protocol** (**FTP**) is a standard [network protocol](https://en.wikipedia.org/wiki/Network_protocol) used for the transfer of [computer files](https://en.wikipedia.org/wiki/Computer_file) between [a client and server](https://en.wikipedia.org/wiki/Client%E2%80%93server_model) on a [computer network](https://en.wikipedia.org/wiki/Computer_network).

FTP is built on a client-server model architecture using separate control and data connections between the client and the server.[[1\]](https://en.wikipedia.org/wiki/File_Transfer_Protocol#cite_note-for-1) FTP users may authenticate themselves with a [clear-text](https://en.wikipedia.org/wiki/Clear_text) sign-in protocol, normally in the form of a username and password, but can connect anonymously if the server is configured to allow it. For secure transmission that protects the username and password, and encrypts the content, FTP is often [secured](https://en.wikipedia.org/wiki/File_Transfer_Protocol#Security) with [SSL/TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security) ([FTPS](https://en.wikipedia.org/wiki/FTPS)) or replaced with [SSH File Transfer Protocol](https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol) (SFTP).

The first FTP client applications were [command-line programs](https://en.wikipedia.org/wiki/Command-line_interface) developed before [operating systems](https://en.wikipedia.org/wiki/Operating_system) had [graphical user interfaces](https://en.wikipedia.org/wiki/Graphical_user_interface), and are still shipped with most [Windows](https://en.wikipedia.org/wiki/Windows), [Unix](https://en.wikipedia.org/wiki/Unix), and [Linux](https://en.wikipedia.org/wiki/Linux) operating systems.[[2\]](https://en.wikipedia.org/wiki/File_Transfer_Protocol#cite_note-tcpip-2)[[3\]](https://en.wikipedia.org/wiki/File_Transfer_Protocol#cite_note-net+-3) Many FTP clients and automation utilities have since been developed for [desktops](https://en.wikipedia.org/wiki/Desktop_computer), servers, mobile devices, and hardware, and FTP has been incorporated into productivity applications, such as [web page editors](https://en.wikipedia.org/wiki/HTML_editor).

---

**IPX**



**Internetwork Packet Exchange** (**IPX**) is the [network layer](https://en.wikipedia.org/wiki/Network_layer) [protocol](https://en.wikipedia.org/wiki/Protocol_(computing)) in the [IPX/SPX](https://en.wikipedia.org/wiki/IPX/SPX) [protocol suite](https://en.wikipedia.org/wiki/Protocol_stack). IPX is derived from [Xerox Network Systems](https://en.wikipedia.org/wiki/Xerox_Network_Systems)' [IDP](https://en.wikipedia.org/wiki/Xerox_Network_Systems#Basic_internetwork_protocol). It may act as a [transport layer](https://en.wikipedia.org/wiki/Transport_layer) protocol as well.

The IPX/SPX protocol suite was very popular through the late 1980s into the mid-1990s because it was used by the [Novell](https://en.wikipedia.org/wiki/Novell,_Inc.) [NetWare](https://en.wikipedia.org/wiki/NetWare) [network operating system](https://en.wikipedia.org/wiki/Network_operating_system). Because of Novell NetWare popularity the IPX became a prominent [internetworking](https://en.wikipedia.org/wiki/Internetworking) protocol.

A big advantage of IPX was a small [memory footprint](https://en.wikipedia.org/wiki/Memory_footprint) of the IPX driver, which was vital for [DOS](https://en.wikipedia.org/wiki/DOS) and [Windows](https://en.wikipedia.org/wiki/Windows) up to the version [Windows 95](https://en.wikipedia.org/wiki/Windows_95) because of limited size of the [conventional memory](https://en.wikipedia.org/wiki/Conventional_memory). Another IPX advantage is an easy configuration of the client computers. However, IPX does not scale well for large networks such as the Internet,[[1\]](https://en.wikipedia.org/wiki/Internetwork_Packet_Exchange#cite_note-1) and as such, IPX usage decreased as the boom of the [Internet](https://en.wikipedia.org/wiki/Internet) made [TCP/IP](https://en.wikipedia.org/wiki/TCP/IP) nearly universal. Computers and networks can run multiple [network protocols](https://en.wikipedia.org/wiki/Network_protocol), so almost all IPX sites will be running TCP/IP as well to allow for Internet connectivity.[[2\]](https://en.wikipedia.org/wiki/Internetwork_Packet_Exchange#cite_note-2) It is also possible to run later Novell products without IPX, with the beginning of full support for both IPX and TCP/IP by NetWare version 5[[3\]](https://en.wikipedia.org/wiki/Internetwork_Packet_Exchange#cite_note-3) in late 1998.

---

**smtp发**

**简单邮件传输协议 (Simple Mail Transfer Protocol, SMTP)** 是在[Internet](https://zh.wikipedia.org/wiki/Internet)传输[email](https://zh.wikipedia.org/wiki/Email)的[事实标准](https://zh.wikipedia.org/wiki/%E4%BA%8B%E5%AF%A6%E6%A8%99%E6%BA%96)。

SMTP是一个相对简单的基于[文本](https://zh.wikipedia.org/wiki/%E6%96%87%E6%9C%AC)的[协议](https://zh.wikipedia.org/wiki/TCP/IP%E5%8D%8F%E8%AE%AE)。在其之上指定了一条[消息](https://zh.wikipedia.org/wiki/%E6%B6%88%E6%81%AF)的一个或多个接收者（在大多数情况下被确认是存在的），然后消息文本会被传输。可以很简单地通过[telnet](https://zh.wikipedia.org/wiki/Telnet)程序来测试一个SMTP服务器。SMTP使用[TCP](https://zh.wikipedia.org/wiki/TCP)端口25。要为一个给定的域名决定一个SMTP服务器，需要使用MX (Mail eXchange) [DNS](https://zh.wikipedia.org/wiki/DNS)。

[Sendmail](https://zh.wikipedia.org/wiki/Sendmail)是最早使用SMTP的邮件传输代理之一。到2001年至少有50个程序将SMTP实现为一个客户端（消息的发送者）或一个服务器（消息的接收者）。一些其他的流行的SMTP服务器程序包括了Philip Hazel的exim，[IBM](https://zh.wikipedia.org/wiki/IBM)的Postfix， [D. J. Bernstein](https://zh.wikipedia.org/w/index.php?title=D._J._Bernstein&action=edit&redlink=1)的[Qmail](https://zh.wikipedia.org/wiki/Qmail)，以及[Microsoft Exchange Server](https://zh.wikipedia.org/wiki/Microsoft_Exchange_Server)。

由于这个协议开始是基于纯[ASCII](https://zh.wikipedia.org/wiki/ASCII)文本的，它在[二进制](https://zh.wikipedia.org/wiki/%E4%BA%8C%E8%BF%9B%E5%88%B6)文件上处理得并不好。诸如[MIME](https://zh.wikipedia.org/wiki/MIME)的标准被开发来编码二进制文件以使其通过SMTP来传输。今天，大多数SMTP服务器都支持8位MIME扩展，它使二进制文件的传输变得几乎和纯文本一样简单。

SMTP是一个“推”的协议，它不允许根据需要从远程服务器上“拉”来消息。要做到这点，邮件客户端必须使用[POP3](https://zh.wikipedia.org/wiki/%E9%83%B5%E5%B1%80%E5%8D%94%E5%AE%9A)或[IMAP](https://zh.wikipedia.org/wiki/IMAP)。另一个SMTP服务器可以使用ETRN在SMTP上触发一个发送。

---

**pop3收**

**邮局协议**（**Post Office Protocol**，简称**POP**）是[TCP/IP](https://zh.wikipedia.org/wiki/TCP/IP)协议族中的一员，由 [RFC 1939](https://tools.ietf.org/html/rfc1939) 定义。本协议主要用于支持使用[客户端](https://zh.wikipedia.org/wiki/%E5%AE%A2%E6%88%B7%E7%AB%AF)远程管理在[服务器](https://zh.wikipedia.org/wiki/%E6%9C%8D%E5%8A%A1%E5%99%A8)上的[电子邮件](https://zh.wikipedia.org/wiki/%E7%94%B5%E5%AD%90%E9%82%AE%E4%BB%B6)。最新版本为**POP3**，全名“Post Office Protocol - Version 3”，而提供了[SSL](https://zh.wikipedia.org/wiki/SSL)加密的POP3协议被称为**POP3S**。

POP支持[离线](https://zh.wikipedia.org/wiki/%E5%9C%A8%E7%BA%BF%E5%92%8C%E7%A6%BB%E7%BA%BF)邮件处理。其具体过程是：邮件发送到服务器上，电子邮件客户端调用邮件客户机程序以连接服务器，并下载所有未阅读的电子邮件。这种离线访问模式是一种存储转发服务，将邮件从邮件服务器端送到个人[终端](https://zh.wikipedia.org/wiki/%E7%B5%82%E7%AB%AF)机器上，一般是[PC](https://zh.wikipedia.org/wiki/PC)机或MAC。一旦邮件发送到PC机或[MAC](https://zh.wikipedia.org/wiki/Macintosh)上，邮件服务器上的邮件将会被删除。但目前的POP3邮件服务器大都可以“只下载邮件，服务器端并不删除”，也就是改进的POP3协议。

---

**html超文本标记语言**

**超文本标记语言**（英语：**H**yper**T**ext **M**arkup **L**anguage，简称：**HTML**）是一种用于创建[网页](https://zh.wikipedia.org/wiki/%E7%BD%91%E9%A1%B5)的标准[标记语言](https://zh.wikipedia.org/wiki/%E6%A0%87%E8%AE%B0%E8%AF%AD%E8%A8%80)。HTML是一种基础技术，常与[CSS](https://zh.wikipedia.org/wiki/CSS)、[JavaScript](https://zh.wikipedia.org/wiki/JavaScript)一起被众多网站用于设计令人赏心悦目的网页、网页应用程序以及移动应用程序的用户界面[[3\]](https://zh.wikipedia.org/wiki/HTML#cite_note-3)。[网页浏览器](https://zh.wikipedia.org/wiki/%E7%BD%91%E9%A1%B5%E6%B5%8F%E8%A7%88%E5%99%A8)可以读取HTML文件，并将其渲染成可视化网页。HTML描述了一个网站的结构语义随着线索的呈现，使之成为一种标记语言而非[编程语言](https://zh.wikipedia.org/wiki/%E7%BC%96%E7%A8%8B%E8%AF%AD%E8%A8%80)。

[HTML元素](https://zh.wikipedia.org/wiki/HTML%E5%85%83%E7%B4%A0)是构建网站的基石。HTML允许嵌入图像与对象，并且可以用于创建交互式表单，它被用来结构化信息——例如标题、段落和列表等等，也可用来在一定程度上描述文档的外观和[语义](https://zh.wikipedia.org/wiki/%E8%AF%AD%E4%B9%89)。HTML的语言形式为[尖括号](https://zh.wikipedia.org/wiki/%E6%8B%AC%E5%8F%B7)包围的HTML元素（如`<html>`），浏览器使用HTML标签和脚本来诠释网页内容，但不会将它们显示在页面上。

HTML可以嵌入如[JavaScript](https://zh.wikipedia.org/wiki/JavaScript)的[脚本语言](https://zh.wikipedia.org/wiki/%E8%84%9A%E6%9C%AC%E8%AF%AD%E8%A8%80)，它们会影响HTML网页的行为。网页浏览器也可以引用[层叠样式表](https://zh.wikipedia.org/wiki/%E5%B1%82%E5%8F%A0%E6%A0%B7%E5%BC%8F%E8%A1%A8)（CSS）来定义文本和其它元素的外观与布局。维护HTML和CSS标准的组织[万维网联盟](https://zh.wikipedia.org/wiki/%E4%B8%87%E7%BB%B4%E7%BD%91%E8%81%94%E7%9B%9F)（W3C）鼓励人们使用CSS替代一些用于表现的HTML元素[[4\]](https://zh.wikipedia.org/wiki/HTML#cite_note-deprecated-4)。

| [扩展名](https://zh.wikipedia.org/wiki/%E6%89%A9%E5%B1%95%E5%90%8D) | `.html``.htm`                                                |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [互联网媒体类型](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E5%AA%92%E4%BD%93%E7%B1%BB%E5%9E%8B) | `text/html`                                                  |
| [类型代码](https://zh.wikipedia.org/w/index.php?title=%E7%B1%BB%E5%9E%8B%E4%BB%A3%E7%A0%81&action=edit&redlink=1) | TEXT                                                         |
| 开发者                                                       | [W3C](https://zh.wikipedia.org/wiki/World_Wide_Web_Consortium) & [WHATWG](https://zh.wikipedia.org/wiki/WHATWG) |
| 初始版本                                                     | 1993年，24年前                                               |
| [最新版本](https://zh.wikipedia.org/wiki/%E8%BD%AF%E4%BB%B6%E7%89%88%E6%9C%AC%E5%91%A8%E6%9C%9F) | [5.2](https://zh.wikipedia.org/wiki/HTML5)[[1\]](https://zh.wikipedia.org/wiki/HTML#cite_note-1) / 5.3（工作草案）[[2\]](https://zh.wikipedia.org/wiki/HTML#cite_note-2) (2017年12月14日，9个月前) |
| 格式类型                                                     | [文档文件格式](https://zh.wikipedia.org/wiki/%E6%96%87%E4%BB%B6%E6%AA%94%E6%A1%88%E6%A0%BC%E5%BC%8F) |
| 延伸自                                                       | [SGML](https://zh.wikipedia.org/wiki/%E6%A0%87%E5%87%86%E9%80%9A%E7%94%A8%E6%A0%87%E8%AE%B0%E8%AF%AD%E8%A8%80) |
| 延伸成                                                       | [XHTML](https://zh.wikipedia.org/wiki/XHTML)                 |
| 标准                                                         | ISO/IEC 15445[W3C HTML 5.1](http://www.w3.org/TR/html/)[HTML活动标准](http://whatwg.org/html) |
| [自由格式](https://zh.wikipedia.org/wiki/%E8%87%AA%E7%94%B1%E6%AA%94%E6%A1%88%E6%A0%BC%E5%BC%8F)？ | 是                                                           |
| 网站                                                         | [www.w3.org/html/](https://www.w3.org/html/)[whatwg.org](https://whatwg.org/) |

---

### 中国网络

我国1994.4接入因特网

**CHINANET**

Chinanet是邮电部门经营管理的基于Internet网络技术的[中国](https://baike.baidu.com/item/%E4%B8%AD%E5%9B%BD)公用计算机互联网，是国际计算机互联网(Internet)的一部分，是中国的Internet骨干网。通过Chinanet的灵活接入方式，用户可以方便地接入全球[Internet](https://baike.baidu.com/item/Internet)，享用Chinanet及全球Internet上的丰富资源和各种服务，是国际计算机互联网(Internet)的一部分。此外，ChinaNet还为中国电信提供的一种无线网络接入的服务名称，即公用WiFi名。

**CHINAGBN**

ChinaGBN(China Golden Bridge Network)也称做中国国家公用经济信息通信网。它是中国国民经济信息化的基础设施，是建立[金桥工程](https://baike.baidu.com/item/%E9%87%91%E6%A1%A5%E5%B7%A5%E7%A8%8B)的业务网，支持金关、金税、金卡等“金”字头工程的应用。目前该网络已初步形成了全国骨干网、省网、[城域网](https://baike.baidu.com/item/%E5%9F%8E%E5%9F%9F%E7%BD%91)3层网络结构，其中骨干网和城域网已初具规模，覆盖城市超过100个。

**CERNET**

国教育和科研计算机网（China Education and Research Network）简称CERNET，是由国家投资建设，教育部负责管理，[清华大学](https://baike.baidu.com/item/%E6%B8%85%E5%8D%8E%E5%A4%A7%E5%AD%A6/111764)等高等学校承担建设和管理运行的全国性学术计算机互联网络。

CERNET(China Education and Research Network)分四级管理，分别是全国网络中心、地区网络中心和地区主结点、省教育科研网、校园网。全国网络中心设在清华大学，负责全国主干网运行管理。

**CSTNET**

1994年中国科学技术网CSTNET首次实现和Internet直接连接，同时建立了中国最高域名·服务器，标志着中国正式接入Internet。接着，相继又建立了中国教育科研网（Cernet）计算机互联网（ChinaNet）和中国金桥网（Genet），从此中国用户日益熟悉并使用Internet。



---

### 其他



---

冯诺依曼理论
存储程序
存储器，运算器，控制器，输入设备，输出设备

---
计算机应用邻域：科学计算，信息处理，自动控制，计算机辅助技术，人工智能，网络应用

​    

---
计算机是由CPU和内存储器

---

---

---



## P&NP&NPC

---

在[计算复杂度理论](https://zh.wikipedia.org/wiki/%E8%AE%A1%E7%AE%97%E5%A4%8D%E6%9D%82%E5%BA%A6%E7%90%86%E8%AE%BA)中，**P**是在[复杂度类](https://zh.wikipedia.org/wiki/%E8%A4%87%E9%9B%9C%E5%BA%A6%E9%A1%9E%E5%88%A5)问题中可于[决定性图灵机](https://zh.wikipedia.org/wiki/%E5%9C%96%E9%9D%88%E6%A9%9F)以[多项式](https://zh.wikipedia.org/wiki/%E5%A4%9A%E9%A0%85%E5%BC%8F)量级（或称[多项式时间](https://zh.wikipedia.org/wiki/%E5%A4%9A%E9%A0%85%E5%BC%8F%E6%99%82%E9%96%93)）求解的[决定性问题](https://zh.wikipedia.org/wiki/%E6%B1%BA%E5%AE%9A%E6%80%A7%E5%95%8F%E9%A1%8C)。



**非确定性多项式**（英语：**non-deterministic polynomial**，缩写：**NP**）时间[复杂性类](https://zh.wikipedia.org/wiki/%E5%A4%8D%E6%9D%82%E6%80%A7%E7%B1%BB)，包含了可以在[多项式时间](https://zh.wikipedia.org/wiki/%E5%A4%9A%E9%A0%85%E5%BC%8F%E6%99%82%E9%96%93)内，对一个[判定性](https://zh.wikipedia.org/wiki/%E5%88%A4%E5%AE%9A%E6%80%A7%E9%97%AE%E9%A2%98)算法问题的实例，一个给定的解是否正确的算法问题。



**NP完全**或**NP完备**（**NP-Complete**，缩写为**NP-C**或**NPC**），是[计算复杂度理论](https://zh.wikipedia.org/wiki/%E8%AE%A1%E7%AE%97%E5%A4%8D%E6%9D%82%E5%BA%A6%E7%90%86%E8%AE%BA)中，[决定性问题](https://zh.wikipedia.org/wiki/%E6%B1%BA%E5%AE%9A%E6%80%A7%E5%95%8F%E9%A1%8C)的档次之一。NPC问题，是[NP](https://zh.wikipedia.org/wiki/NP_(%E8%A4%87%E9%9B%9C%E5%BA%A6))（非决定性[多项式时间](https://zh.wikipedia.org/wiki/%E5%A4%9A%E9%A0%85%E5%BC%8F%E6%99%82%E9%96%93)）中最难的[决定性问题](https://zh.wikipedia.org/wiki/%E6%B1%BA%E5%AE%9A%E6%80%A7%E5%95%8F%E9%A1%8C)。因此NP完备问题应该是最不可能被化简为[P](https://zh.wikipedia.org/wiki/P_(%E8%A4%87%E9%9B%9C%E5%BA%A6))（多项式时间可决定）的决定性问题的集合。若**任何**NPC问题得到多项式时间的解法，那此解法就可应用在所有NP问题上。更详细的定义容下叙述。

一个NPC问题的例子是[子集合加总问题](https://zh.wikipedia.org/wiki/%E5%AD%90%E9%9B%86%E5%90%88%E5%8A%A0%E7%B8%BD%E5%95%8F%E9%A1%8C)，题目为

给予一个有限数量的整数集合，找出任何一个此集合的非空子集且此子集内整数和为零。

意即：是一个包括若干整数的集合，找出任一一个![{\displaystyle S'\subset S}](https://wikimedia.org/api/rest_v1/media/math/render/svg/a82d0bca0d060ab870e85fa22e4de075763a8376)且![\sum _{{x\in S'}}x=0](https://wikimedia.org/api/rest_v1/media/math/render/svg/e07e779b5f35cfcfba963363e68e7b322df33ef1)

这个问题的答案非常容易验证，但目前没有任何一个够快的方法可以在合理的时间内（意即多项式时间）找到答案。只能一个个将它的子集取出来一一测试，它的时间复杂度是Ο(2n)，n是此集合的元素数量。

![](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/Complexity_classes.svg/250px-Complexity_classes.svg.png)

**NP困难**（**NP-hard**, non-deterministic polynomial-time hard）问题是[计算复杂性理论](https://zh.wikipedia.org/wiki/%E8%AE%A1%E7%AE%97%E5%A4%8D%E6%9D%82%E6%80%A7%E7%90%86%E8%AE%BA)中最重要的复杂性类之一。某个问题被称作NP困难，当所有[NP](https://zh.wikipedia.org/wiki/NP_(%E8%A4%87%E9%9B%9C%E5%BA%A6))问题可以在[多项式时间图灵归约](https://zh.wikipedia.org/wiki/%E5%A4%9A%E9%A1%B9%E5%BC%8F%E6%97%B6%E9%97%B4%E5%9B%BE%E7%81%B5%E5%BD%92%E7%BA%A6)到这个问题。

因为NP困难问题未必可以在多项式的时间内验证一个解的正确性（即不一定是NP问题），因此即使NP完全问题有多项式时间内的解（若[P=NP](https://zh.wikipedia.org/wiki/P/NP%E9%97%AE%E9%A2%98#P.3DNP)），NP困难问题依然可能没有多项式时间内的解。因此NP困难问题“至少与NPC问题一样难”。

![](http://zjqyy.top/pic/10.png)

---

## 数学

------

------

### 组合数学

------

**加法原理**

几类独立完成

------

**乘法原理**

完成一件事有若干中步骤

------

#### 排列

```c++
A[n][m]=n!/(n-m)!
```

------

##### 圆排

```
[n][m]=n!/((n-m)!*r)
```

4男4女围圆桌交替就坐有多少方式？

答：

```A[ 4 ][ 4 ]
A[ 4 ][ 4 ]
```

------

pn##### 无限重排列

```
[n][m]=n^m
```

------

##### 有限重排列

```
[n][m]=n!/(n1!*n2!*n3!...*nt!)
```

------

#### 组合

```
C[n][m]=n!/((n-r)!*r!)
c[n][m]=c[n][n-m]
```

从1~300之间任意选3个不同的数，使得这三个数的和正好被3整除

思路：分成%3=1/2/3的3类，进行组合计算

------

##### 重组合

定义：从n种不同元素中取r个允许重复的元素而且不考虑次序

等价于：把r只相同颜色的球放到n个编号不同的盒子中，每个盒子放球数不限

```
h[n][m]=c[n+m-1][r]
```

------

问$((X+Y+Z)^{1986}$有多少项？

答：$C_{1986+3-1}^{1986}$

还不会

------

不定方程

$x1+x2+x3+...+xn=r$的非负整数解的组数

答案：$C_{n+m+1}^{n-1}$

还不会

------

对于没有三条对角线交于一点的凸n多边形，计算各边及对角线所组成的互不重叠的区域个数

还不会

---

母函数

还不会

---

容斥

搞清量的关系

---

错排

```
[n]=n!-c[n][1]*(n-1)!+c[n][2]*(n-2)!-c[n][3]*(n-3)!...+(-1)^k*c[n][k]*(n-k)!
```

取数I分别与它的N-1个数与之交换，其余N-2错排

或I以外的数n-1个数进行错排，将i与其他进行交换

最后加法原理

```
[n]=(n-1)*([n-2]+[n-1])
```



---

数学归纳法

证明：

（1）假设n取no时结论正确

（2）假设n取k时结论正确，可以证明n=k+1时结论正确

---

博弈

较难的可以考虑用递推的方式

---

概率

---

拓扑排序及应用

---

关键路径

---

NIM为什么要xor

一位的xor=0表示该位是0/1出现过偶数次

若对手可取，那么该位有偶数个1（可以包含退位的1）

否则对手不可取

所以每一位，只要对手可取1，我们也可以取1

而每一个数都可以用二进制位表示

xor=0表示一个数没有出现/出现偶数次

那么对手每取一个数，我们都可以取和它一样的数

（也就是说，对手能取的数都是成对出现的，故我们也可以取这个数）

---
# 个人算法漏洞

---

---

---

### 循环队列

插入新元素

```pascal
procedure Add2( var q:equeue;   x:qtype;    var r:integer  );
begin
t=r mod m+1;
if t=f then writeln('full')
else begin
r=t;q[r]=x;
end;
end;
```
过程DEL2(Q,Y,F)从循环队列q中取出队首元素
```pascal
procedure del2(var q:equeue;     var y:qtype;    var f:integer);
begin
if f=r then writeln('empty')
else begin
f=f mod m+1;y=q[f];
end;
end;
```
---

---
### 排序

---
***稳定***：归并，冒泡，插入，基数
定义：假定在待排序的记录序列中，存在多个具有相同的关键字的记录，若经过排序，这些记录的相对次序保持不变，即在原序列中，r[i]=r[j]，且r[i]在r[j]之前，而在排序后的序列中，r[i]仍在r[j]之前，则称这种排序算法是稳定的；否则称为不稳定的。

就地排序：冒泡，选择，插入，快排

---

#### 分块查找

当采用分块查找时，数据的组织方式为数据分成若干块，每块内数据不必有序，但块间必须有序，每块内最大（或最小）的数据组成索引块

---

#### 散列表的平均查找长度
与处理冲突方法有关而与表的长度无关

---

#### 直接插入排序

直接插入排序应当指从i往前为i找位置，并和比它大的前一个交换

---

#### 快排
pascal 经典快排

```pascal
procedure sort(l,r: longint);
var
  i,j,x,y: longint;
begin
  i:=l;
  j:=r;
  x:=a[(l+r) div 2];
  repeat
    while a[i]<x do inc(i);
    while x<a[j] do dec(j);
    if not(i>j) then
    begin
      y:=a[i];
      a[i]:=a[j];
      a[j]:=y;
      inc(i);
      dec(j);
    end;
  until i>j;
  if l<j then sort(l,j);
  if i<r then sort(i,r);
end;
```

c++的**sort**

http://www.udpwork.com/item/12284.html

震撼

---

#### 基数排序

将数的队列放入基数的桶，在从一个个桶（按其大小顺序）中顺序取出
时间复杂度最少$O(nlog_2n)$(正常$O(nlog_rm)$)

空间效率：O（nr)

---

桶排复杂度基于数据随机

---

#### 希尔排序

实验得时间级$O(n^\frac{3}{2} )$到$O(n^\frac{7}{6})$
平均：$O(n^{1.3})$
最优：O(n)
最坏：$O(n^2)$

---

#### 一些结论

基于比较的排序时间复杂度最小nlog(n)

---
#### 一张表

![](http://www.zjqyy.top/pic/6.png)
注：shell:插入排序
而且有很多错，仅供参考

---
#### 巨佬wangyicheng's笔记

  https://www.zybuluo.com/scrolllock/note/1297938

---

---

### prim

---
1).输入：一个加权连通图，其中顶点集合为V，边集合为E；
2).初始化：Vnew = {x}，其中x为集合V中的任一节点（起始点），Enew = {},为空；
3).重复下列操作，直到Vnew = V：
a.在集合E中选取权值最小的边<u, v>，其中u为集合Vnew中的元素，而v不在Vnew集合当中，并且v∈V（如果存在有多条满足前述条件即具有相同权值的边，则可任意选取其中之一）；
b.将v加入集合Vnew中，将<u, v>边加入集合Enew中；
4).输出：使用集合Vnew和Enew来描述所得到的最小生成树。

---

---

### 递归时间复杂度

---

![](http://zjqyy.top/pic/master.png)

---

---

---

# 未AC的题

---

---

15、四面体的顶点和各棱中点共10个点，从中取4个不共面的点，不同的取法有多少种？

解析：

答案：****

---

16、以一个正方体的顶点为顶点，能组成多少个不同的四面体？ 

解析：

答案：****

---

17、6本不同的书全部分给5名同学每人至少一本，有多少种不同的分法？

解析：

答案：****

---

20、8本不同的书分给3名同学，其中1名同学2本、另两人3本，有多少种不同分法？

解析：

答案：****

---

22、将5名实习教师分配到高一年级的3个班实习，每个班至少1名，最多2名，则不同的分配方案有多少？ 

解析：

答案：****

---

23、7个相同的小球，任意放入4个不同的盒子中，共有多少种不同的方法？ 

解析：

答案：****

---

27、10双不相同的鞋子混装在一只口袋中，从中任取4只，4只鞋子没有成双的方法数？

解析：

答案：****

---

28、10双不相同的鞋子混装在一只口袋中，从中任取4只，4只鞋子恰有2只成双的方法数？ 

解析：

答案：****

---

29、8名外交工作者，其中3人只会英语，2人只会日语，3人既会英语又会日语，现从则8人中选3个会英语，3个会日语的人去完成一项任务，有多少种不同的选法？

解析：

答案：****

---

30、5对姐妹站成一圈，要求每对姐妹相邻，有多少种不同站法？ 

解析：

答案：****

---

31、6本不同的书分给甲、乙、丙三人，每人至少一本，有多少种不同的分法？

解析：

答案：****

---

32、从5男3女中选5人担任5门不同学科的课代表，有女生担人数必须少于男生时，不同选法是？ 

解析：

答案：****

---

33、从5男3女中选5人担任5门不同学科的课代表，男生只能担任数学化学物理课代表时，不同选法是？ 

解析：

答案：****

---

34、3张卡片正反面分别写着数字0与1、3与4、5与6，将三张卡片并排组成三位数，共可以组成多少个不同的三位数？

解析：

答案：****

---

37、一些学生接受调查，这些学生中准备参加会计师考试的有63人，准备参加英语考试的有89人，准备参加计算机考试的有47人，三种都准备参加的有24人，只准备参加两种考试的有46人，不参加其中任何一种考试的有15人。请问有多少学生接受调查？

解析：

答案：****

---

39、某班统计考试成绩，数学得90分上的有25人;语文得90分以上的有21人;两科中至少有一科在90分以上的有38人。问两科都在90分以上的有多少人?

解析：

答案：****

---

45、对集合{1，2，…，n}及其每一个非空子集，定义一个唯一确定的“交替和”如下：按照递减的次序重新排列该子集，然后交替地减或加后继的数所得的结果，例如，集合{1,2,4,6,9}的“交替和”是9-6+4-2+1=6. {5,6}的“交替和”是6-5=1，{2}的交替和是2。那么，对于n=7。求所有子集的“交替和”的总和。

解析：

答案：****

---

46、将与105互素的所有正整数，从小到大排成一个数列，试求出该数的第1000项．

解析：

答案：****

---

47、对于任何的集合S，记|S|为集合的元素个数，记n（S）为集合S的子集个数，若A，B，C是三个集合，满足：n(A)+n(B)+n(C)=n(A∪B∪C)。|A|=|B|=100。求|A∩B∩C|的最小值。

解析：

答案：****

---

57、一些苹果和梨混放在一个筐里，小明把这筐水果分成了若干堆，后来发现无论怎么分，总能从这若干堆里找到两堆，把这两堆水果合并在一起后，苹果和梨的个数是偶数，那么小明至少把这些水果分成了多少堆？ 

解析：

答案：****

---

58、从1，3，5，……，99中，至少选出多少个数，其中必有两个数的和是100。 

解析：

答案：****

---

60、某个年级有202人参加考试，满分为100分，且得分都为整数，总得分为10101分，则至少有多少人得分相同？

解析：

答案：****

---

62、某校派出学生204人上山植树15301株，其中最少一人植树50株，最多一人植树100株，则至少有多少人植树的株数相同？ 

解析：

答案：****

---

68、任意多少个自然数中，必可找出3个数，使这三个数的和能被3整除。

解析：

答案：****

---

2、	给定一个01字符串，请你找出长度介于a，b之间，重复出现次数最多的01串。
输入：a，b(0<=A<=B<=12)
由0、1组合的序列，由“.”结尾。
输出：重复出现的最多次数以及所有满足要求的串。
提示：本程序中将01序列转换为2进制存储。

```c++
#include<iostream> 
using namespace std;  
int m[8193],two[21],v[21];
int main() {
	for(int i=1;i<=13;i++) two[i]= (1) ;
	int a,b;
	cin>>a>>b>>c;
	int s=1,k=1;
	while(c!='.'){
		s=(s<<1)+c-'0';
		if( (2) )s=(s-two[b+1])%two[b]+two[b];
		m[s]++;
		if(k<b)
			for(int i=a;i<k;i++)  (3) ;
		k++;
		cin>>c;
	}
	for(int i=two[b];i<=two[b+1];i++)
		if(m[i]>0)
			for(int j=a;j<b;j++) m[i%two[j]+two[j]]= (4) ;
	int Max=0;
	for(int i=two[a];i<=two[b+1];i++)
		if(m[i]>Max) Max=m[i];
	cout<<Max<<endl;
	for(int i=two[a];i<=two[b+1];i++)
		if(m[i]==Max){
			int j=0,k=i;
			do{
				j++;v[j]=k%2;k/=2;
			}while( (5) );
			while(j>0){cout<<v[j];j--;}
			cout<<endl;
		}
    return 0;
}
```

答案
(1) 1<
(2) s>=two[b+1]
(3) m[s%two[i]+two[i]]++
(4) m[i%two[j]+two[j]]+m[i]
(5) k!=1 

---

3、	

```c++
#include<iostream> 
#include<iomanip>   
using namespace std;  
int a[33],b[33];
void ssort(int x,int y){
	if(y-x>1){
		int m=(x+y)/2;
		ssort(x,m);
		ssort(m+1,y);
		int k=x;
		for(int i=x;i<=m;i++){
			b[k]=a[i];b[k+1]=a[m+i-x+1];
			k+=2;
		}
		for(int i=x;i<=y;i++) a[i]=b[i];
	}
}
int main() {
	for(int i=1;i<=16;i++) a[i]=i;
	ssort(1,16);
	for(int i=1;i<=16;i++) cout<<setw(3)<<a[i];
	cout<<endl;
    return 0;
}
```

//这道题请严格按照输出格式来，注意行首和行间空格，行末空格忽略
输出：

答案： 1 9 5 13 3 11 7 15 2 10 6 14 4 12 8 16 

---

4.

```c++
#include<iostream>    
using namespace std;   
int w[10];
int n,m,weight;
int main() {
	cin>>weight;cout<<weight<<'=';
	m=1;int i=0;w[i]=1;
	while(m<weight){
		i++;w[i]=w[i-1]*3;m+=w[i];
	}
	bool flg=false;
	n=weight;i=0;
	while(n>0){
	      switch(n%3){
		case 0:n/=3;break;
		case 1:
			n/=3;if(flg) cout<<'+';
			cout<<w[i];flg=true;break;
		case 2:
			n=n/3+1;cout<<'-'<<w[i];
			flg=true;break;
	      }
	i++;
	}
return 0;
}
```

输入：518  
输出：

答案：	518=-1-3+9+27-243+729 

---

8．一个平面的法线是指与该平面垂直的直线。过点(1,1,1)、（0,3,0）、(2,0,0)的平面的法线是（   ）。

A．过点（1，1，1）、（2，3，3）的直线   

B．过点（1，1，1）、（3，2，1）的直线

C．过点（0，3，0）、（-3，1，1）的直线   

D．过点（2，0，0）、（5，2，1）的直线

解析：

答案：**D**

---

计算机中，使用的基本存储单位是（ ）
A、 字   B、 位  C、 字节   D、 字符

解析：

答案：**C**

---

19、若A=True，B=False，C=True，D=False，则下列逻辑运算真的有（ABC）

A、(A∧B)V(C∧DV ¬D)       B、((¬A∧B)VC)∧¬B   

C、(¬A→B)∧(CVD)          D、A∧(DV¬C)∧B

解析：A→B表示A导致B，所以只有A0B1时值才为假

答案:**ABC**

------

20、以下人物与其贡献对应的是（BCD）。

​	A．阿兰·图灵-制造人类历史上第一台计算机	ENIAC	

 B. 冯·诺依曼-“存储程序”概念和二进制原理

​	C．姚期智-建立量子计算机理论基础		

 D. 王选-汉字激光照排系统

---

1. 将2006个人分成若干不相交的子集，每个子集至少有三个人，并且：

1. 在每个子集中，没有人认识该子集的所有人。

2. 
3. 同一子集的==任何==3个人中，至少有2个人互不认识。

4. 
5. 对同一子集中任何2个不相识的人，在该子集中恰好只有1个人认识这两个人。

 则满足条件的子集最多能有   401    个。

解析：用一个结点表示一个人，两个人互相认识就用线连上，不认识就不连。

因此，对于题目描述，可以发现三个节点、四个节点、六、七结点是不行的，五边形、八边形可以（正八边形，每点再向正对的点连线）

此题是NOIP2006年真题，但是有争议

标准解答：但是此题要求最多，2006/5=401

不同理解：标准解答中最后一个集合为6，不符合要求，因此应该列5*x+8*y=2006

解得x+y最大为400（398+2）

---

---

# 未完待续