# HodaESMS
A Email Server. Support SMTP/POP3/IMAP4/Online WebMail/FTP/GPG Encryption......

### 基于嵌入式Linux操作系统
基于LINUX内核开发的专用的嵌入式加密操作系统。

### 全链路加密
操作系统级加密，"芯片级"的封装，军用级的标准，使系统具备了防监听、防钓鱼、防伪造、防篡改、防抵赖、防病毒、防黑客、防内鬼的能力，抗攻击能力强。

### 运行效率高/速度快
包括 WebMail 在内，整体采用C语言开发，读写效率高，速度快。

### 内置 Hoda-Webmail，支持SSL / GPG，直接在浏览器中收发加密的邮件
Webmail采用FastCGI、XHTML、AJAX、ZIP压缩、非对称数字证书等技术。
用户可直接通过浏览器在线完成编辑邮件/给邮件添加数字签名/加密解密邮件/验证邮件等工作。
而不必随身携带证书密钥，即便是临时借用他人的电脑，也可以放心的使用Hoda-Webmail收发安全邮件，不用担心密钥被盗。
天然支持防伪造、防篡改功能。

![](https://raw.githubusercontent.com/lz9168/HodaESMS/master/snaps/w1.png)     
![](https://raw.githubusercontent.com/lz9168/HodaESMS/master/snaps/w3.png)

### 智能化全自动安装维护
系统会自动检测硬盘类型、数量，智能识别是否可以创建并使用RAID，真正免除了系统安装、调试的麻烦。

### 强大的系统管理功能
强大的菜单化控制台管理工具和基于WEB的管理工具，使日常管理维护工作变得更简便、更轻松、更高效。
管理员不必学习复杂的操作系统维护技术，只要会上网，就会使用管理工具，不用担心发生误操作事故。

![](https://raw.githubusercontent.com/lz9168/HodaESMS/master/snaps/m3.png)    
![](https://raw.githubusercontent.com/lz9168/HodaESMS/master/snaps/c1.png)

### 去中心化的证书发布管理机制
取消CA证书管理中心，每个用户自主管理各自的证书，避免因CA原因造成的任何安全问题。

### 独创的智能前端安全网关
传统的反垃圾系统，必须等待把所有的数据都接收完毕后，才能进行扫描。
HodaESMS借鉴了传统智能分析引擎的原理，结合先进的人工智能技术研发了智能前端安全网关系统，这允许HodaESMS系统一边接收邮件数据、一边分析邮件数据，在接收的过程中，一旦发现垃圾邮件或病毒邮件的特征，就可以直接将数据连接断开，而不再接收下面的垃圾数据。
这项技术的使用可有效的节约网络带宽、服务器CPU、内存等宝贵资源，显著降低系统的负载，提高系统的整体数据吞吐能力。

### 完善的数据备份机制
凭借自主开发的嵌入式操作系统的优势，HodaESMS系统不仅对多种硬件RAID设备提供了驱动支持，还为没有硬件RAID设备的用户，提供了软件RAID(级别0,1)的支持，并且提供了方便、实用的软RAID管理维护工具。
数据的实时备份从未如此简便。

### 灵活的个性配置
系统管理员可以自由定制：LOGO图标、登陆页面、WEB-MAIL的浏览器标题、WEB-MAIL底部版权区信息、多个域的登陆方式、TLS/SSL连接所用安全证书等。
用户可以自由定制：个人资料、WEB-MAIL的显示设置、个性化签名、私人邮件过滤器、自动应答回复器、黑名单等。

### 丰富的协议支持
支持TCP/IP、XHTML、MIME、HTTP、HTTP+SSL、SMTP、SMTP+SSL、POP3、POP3+SSL、IMAP4、IMAP4+SSL、FTP、SSH2、TLS/SSL等众多标准协议。





