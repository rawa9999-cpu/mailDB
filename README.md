# mailDB
一种新型的基于整个互联网的电子邮件协议的分布式的网络存储系统

mailDB计划书

关于一种新型的使用电子邮件协议作为存储的分布式数据库系统。

我们当年因特网的联立，是基于四中服务，新闻组、Http（web）、电子邮件、远程登录，还有两种直接控制计算机的FTP和TelNET服务。随着区块链技术的发展，分布式存储成为一种新的存储技术，但是区块链技术需要复制大量的同样的数据，我们很多其他的云计算技术也是一样，总是脱离不了服务器和数据库服务的投入。

我长期研究Email协议发现，可以利用电子邮件协议的一个附加的存储空间，很多邮件系统是支持附件和一些格式化信息的，比如附加一个背景图案，我们把互联网上的每一封电子邮件作为一个移动的存储单元，那么使用哈希和签名的操作，就可以把这些大量的无机的存储空间，进行有效的利用，并且采用一种新型的算法，可以有效的利用电子邮件之间的传输，把需要的数据传送和复制到应该得到他们的用户，把整个互联网视为一个分布式的巨大的，并且在运转的存储空间，把大量的无序的邮件传递，进行有机的运算和利用，然后把需要的数据传递给需要他们的用户。

我管这种新的存储和传输技术叫做mailDB技术,这种技术的特点就是使用很小的数据传递可以从互联网上复制极大的数据到自己的硬盘。

这种新的存储技术，可以让中国的长城防火墙成为垮塌柏林墙，国内是不可能拿到钱了，希望美国政府给我资助。

mailDB基本存储块的格式，包含四个部分和四种状态。
四个部分：发送的原地址，目标地址，1M字节的数据，hash值(使用MD5，没有专利限制，速度快)。
四种状态：创始态，计算态，传递和生长态，稳定态（复制100~200份自己达到这个状态）。

下面是英文部分：

MailDB plan
--About a new type of distributed database system using E-mail protocol as storage.
Our Internet was based on four services: newsgroups, HTTP (Web), E-mail,
remote login, and two direct Control your computer's FTP and Telnet services.With the development of blockchain technology, distributed storage has become a new storage technology, but blockchain technology needs to replicate a large number
of the same numbers The same is true of many of our other cloud computing technologies, which are always tied to server and database services.
I have long studied the Email protocol and found that it is possible to take
advantage of the Email protocol with an additional storage space. Many Email
systems are supported by attachments and attachments Some formatting of the
message, such as attaching a background pattern, we put every email on the
Internet as a mobile storage sheet So using the operation of hashing and signature,
you can make efficient use of these large amounts of inorganic storage space, and
adopt a new kind of algorithm can efficiently utilize the transmission of E-mail to
send and copy the required data to the users who deserve them , which treats the
entire Internet as a distributed, vast, functioning storage space for the vast,
unordered flow of mail and then pass the data to the users who need them.
I call this new storage and transport technology MailDB technology.This
technology is characterized by the use of very little data transfer that can be made
from the Internet Copy a maximum of data to your hard disk.
This new storage technology could turn the Great Firewall of China into the Berlin
Wall and make it impossible for the domestic government to get the money out of it,
hope the U.S. government Give me a grant.
The format of the MailDB basic storage block, consisting of four parts and four
states.Four parts: the original address sent, the destination address, the 1M bytes of data,
the hash value (using MD5, no patent restrictions, fast).There are four states: the initial state, the computational state, the transfer and growth state, and the stable state (100~200 copies of themselves to reach this state).
