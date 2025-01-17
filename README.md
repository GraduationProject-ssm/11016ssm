# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 11016ssm网上生鲜销售系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 第1章  绪论
## 1.1  课题背景及研究意义
### 1.1.1  课题背景
经过互联网近几年的蓬勃发展，整个现代社会的网上管理系统方式已经慢慢地从本质上发生了变化。上世纪90年代以后，我们国家整体经济水平逐渐提高，人民的生活水平有了极大的进步。互联网行业，乃至与其有关联的传统行业，例如生鲜销售行业的蓬勃发展，《电子商务法律法规》等一系列关于网络商品信息法规的出台，阻碍网上商品信息的各个难关被一一攻破，电子商务的趋势越来越壮大。
### 1.1.2  研究意义
社会主义进入新时代，经济实力越来越强。我们也变得越来越忙碌、对生活的要求也变得更加严格，对快速和方便的服务的需求也在逐渐增加。因此，对销售行业的管理、服务的要求也越来越严格。为适应时代的发展，各大用户开始广泛地使用电脑来进行管理，并推出在线网上生鲜销售系统，为提高工作人员效率提供了一种新的方式，并且减轻了他们的工作强度，为用户提供更加方便、快捷而高效的服务，实现双赢。

于此同时，实现网上生鲜销售系统的计算机化也是顺应时代潮流的举措，现如今生鲜销售正逐渐增加，引起了用户青睐，生鲜销售的管理工作变得越来越轻松，在这一客观需要的推动下，建立、完善、发展网上生鲜销售系统，可以为管理员与用户带来极大的方便。

本系统即为方便管理员和用户而制作的网上网上生鲜销售系统，结合了用户的需求，设计出的一个基于jsp语言、MySQL数据库的网上网上生鲜销售系统。
## 1.2  开发工具的选用及语言介绍
本次毕业设计是一个基于B/S模式的网上生鲜销售系统，是一个在网络环境下运行的网站，采用jsp语言，应用的技术有JSP,Tomcat作为服务器，MySQL作为后台数据库[4]。
## 1.2.1  jsp简介
JSP(Java脚本页面)是Sun和许多参与建立的公司所提倡的动态web技术。将Java程序添加到传统的web页面HTML文件(\*)。htm,\*。Html)。

JSP这种能够独立使用的编程语言可以嵌入在html语言里面运行，正因为JSP参照了许多编程语言的特性，使得JSP在web的脚本技术当中也占有一定的重要位置，对于刚入门编程行业的初学者来讲，jsp这种编程语言不仅容易学习，而且还具备许多高级的特性[7]。在程序的开发过程中，使用jsp也不失为一种正确的选择，像表单数据的收集操作以及字符串信息的处理方面等等，jsp都能很轻松地解决，这样节省程序开发员开发设计的时间，JSP 最大的特点就是操作简单，并且具有很好的面向对象性，因此很多的系统开发设计都喜欢用jsp技术。同时，设计开发时，有两种选择，一种是面向过程，另一种是面向对象，或者也可以两种都使用，可以称为混和方式设计。
### 1.2.2 本文的内容
本文主要介绍了网上生鲜销售系统的课题背景，说明了该系统开发的意义，整个系统开发过程中使用的主要技术，分析了该系统开发的可行性，归纳并分析了用户对于该系统开发的主要需求。
## 1.2.3 MYSQL数据库
网站的开发必须配套相应数据库，数据库具有一定的组织结构，能够存放和管理数据信息，在以前数据库的功能仅仅是数据保存和管理操作，但是时代的变迁和发展，现在的数据库演变成了数据处理的方式，数据库从最开始的简单存放数据表格信息到现在的能够存放成千上万数据的大型数据库，期间还是经历了许多的改革。

本次开发的网上生鲜销售系统使用的数据库是MYSQL数据库，该数据库运行速度快，安全性能也很高，而且对使用的平台没有任何的限制，所以被广泛应运到系统的开发中。MySQL是一个开源和多线程的关系管理数据库系统，MySQL是开放源代码的数据库，具有跨平台性，虽然功能未必强大，导致很多人都了解这个数据库的基本应用，在数据库中，总共建立了10几个表，这里面每个表都是相对应的，都各自有各自的联系，数据库意义重大，如果没有数据库的链接，就没办法运行程序，这显然可以看见数据库与程序的重要性，是紧密相连接的。
## 1.2.4 B/S结构	
B/S（浏览器/服务器）结构是目前主流的网络化的结构模式，它能够把系统核心功能集中在服务器上面，可以帮助系统开发人员简化操作，便于维护和使用。只需要用户在电脑上安装360浏览器、谷歌浏览器、QQ浏览器等当前大众浏览器，在电脑里面安装sqlserver、mysql数据库等数据库。安装好的浏览器与服务器端的数据库进行信息数据的交互。很多专门软件能够做到的事情，采用B/S结构模式也能实现，它能够结合Web浏览器技术，ActiveX技术以及多种脚本语言等技术。帮助程序开发者节约了不少开发成本。目前B/S结构成为程序开发主流结构，它最好的地方就是没有地点限制还不用专门安装软件，笔记本或者电脑能够上网就能访问系统。系统使用B/S进行开发在后期系统维护上面就会很省事，不用什么问题都在服务器上面操作，简单的用户端处理就解决部分问题，开发出来的程序跟用户交互性上面也会增强，还可以实时刷新浏览器进行程序局部的数据信息更新。
# 第2章  需求分析与可行性分析
## 2.1  功能需求分析
网上生鲜销售系统主要是为了提高工作人员的工作效率和更方便快捷的满足用户，更好存储所有数据信息及快速方便的检索功能，对系统的各个模块是通过许多今天的发达系统做出合理的分析来确定考虑用户的可操作性，遵循开发的系统优化的原则，经过全面的调查和研究。

系统所要实现的功能分析，对于现在网络方便的管理，系统要实现用户可以直接在平台上进行查看所有数据信息，根据需求可以进行在线添加，删除或修改生鲜销售信息，这样既能节省时间，不用再像传统的方式耽误时间，真的很难去满足用户的各种需求。所以网上生鲜销售系统的开发不仅仅是能满足用户的需求，还能提高管理员的工作效率，减少原有不必要的工作量。
## 2.2  可行性分析
### 2.2.1技术可行性：技术背景

本网上生鲜销售系统网站在Windows操作系统中进行开发，并且目前PC机的性能已经可以胜任普通网站的web服务器。系统开发所使用的技术也都是自身所具有的，也是当下广泛应用的技术之一。

系统的开发环境和配置都是可以自行安装的，系统使用jsp开发工具，使用比较成熟的Mysql数据库进行对系统前台及后台的数据交互，根据技术语言对数据库，结合需求进行修改维护，可以使得网站运行更具有稳定性和安全性，从而完成实现网站的开发。

（1）硬件可行性分析

网上生鲜销售系统及信息分析的设计对于所使用的计算机没有什么硬性的要求，计算机只要可以正常的使用进行代码的编写及页面设计就可行，主要是对于服务器有些要求，对于平台搭建完成要上传的服务器是有一定的要求的，服务器必须选择安全性比较高的，然后就是在打开网站必须顺畅，不能停顿太长时间；性价比高；安全性高。

（2）软件可行性分析

开发整个系统使用的是云计算，流量的可扩展性和基于流量的智能调整云计算的优点就是流量的可扩展性和基于流量的智能调整，保障系统的安全及数据信息的及时备份。

因此，我们从两个方面进行了可行性研究，可以看出系统的开发没有问题。
### 2.2.2经济可行性
在网上生鲜销售系统开发之前所做的市场调研及其他的相关管理系统，都是没有任何费用的，都是通过开发者自己的努力，所有的工作的都是自己亲力亲为，在碰到自己比较难以解决的问题，大多是通过同学和指导老师的帮助进行相关信息的解决，所以对于网上生鲜销售系统的开发在经济上是完全可行的，没有任何费用支出的。

使用比较成熟的技术，系统是基于jsp的开发，采用Mysql数据库。所以系统在开发人力、财力要求不高，具有经济可行性。
### 2.2.3操作可行性： 
可操作性主要是对网上生鲜销售系统设计完成后，用户的使用体验度，以及管理员可以通过系统随时管理相关的数据信息，并且对于管理员、用户二个权限角色，都可以简单明了的进入到自己的系统界面，通过界面导航菜单可以简单明了地操作功能模块，方便用户信息的操作需求和管理员管理数据信息，对于系统的操作，不需要专业人员都可以直接进行功能模块的操作管理，所以在系统的可操作性是完全可以的。本系统的操作使用的也是界面窗口进行登录，所以操作人员只要会简单的电脑操作就完全可以的。

2.3 系统性能分析

（1）系统响应效率：页面响应时问应该在3秒以内，最长不能超过4秒，并支持至少10000人同时在线所有系统。

（2）界面简洁清晰：系统界面要求简单明了，容易操作，符合用户操作习惯。

（3）储存性高：因为网上生鲜销售系统中有很多的信息需要存储，因此对于系统的存储量有很大的要求，需要有一个强大的数据库的支持才能确保所有的信息都能安全稳定的进行存储。

（4）易学性：该系统在操作上必须简单好上手，没有很多复杂的操作，只需要简单的进行学习就能操作该系统。

（5）稳定性需求：开发的网上生鲜销售系统要求运行稳定，运行过程中无界面不清楚、字体模糊等现象。
# 第3章  系统总体设计
## 3.1  系统的结构划分
本网站可以分为:用户使用的功能、管理员进行管理的功能。

用户使用功能：个人中心、订单评价管理、我的收藏管理、订单管理等。

管理员管理功能：个人中心、用户管理、商品资讯管理、商品分类管理、商品信息管理、订单评价管理、系统管理、订单管理等。
### 3.1.1  系统结构图
网上生鲜销售系统的结构图3-1所示：

网

络

管理员

服务器和程序

用户

![](/md/blog.001.png)

图3-1 系统结构

登录系统结构图，如图3-2所示：

网上生鲜销售系统登录界面

用户登录

密码正确

管理员界面

用户界面

![](/md/blog.002.png)

图3-2 登录结构图

这些功能可以充分满足网上生鲜销售系统的需求。此系统功能较为全面如下图系统功能结构如图3-3所示。

![](/md/blog.003.png)

图3-3系统功能结构图
## 3.2  系统的流程分析
### 3.2.1操作流程
系统登录流程图，如图所示：

管理员是系统的管理者，因此管理员对管理也是不可或缺的部分，通过该操作登录账号密码，创建管理员信息，通过数据库的信息反馈到页面，判断该管理员是否存在，管理员时序图如图3-4所示。

![](/md/blog.004.png)

图3-4 管理员时序图

用户登录也是本系统重要的部分，该模块主要对用户的信息进行添加、删除、修改、查询操作，与其他各个功能模块有着密不可分的关联，我们无论用哪种身份对系统进行操作时，都需要用身份去完成相应的操作。用户登录时序图如图3-5所示。

![](/md/blog.005.png)

图3-5 用户时序图
### 3.2.2删除信息流程
删除信息流程图，如图所示：

![](/md/blog.006.png)

图3-5删除信息流程图
## 3.3. 数据库设计
### 3.3.1 数据库实体	
管理员信息结构图，如图4-5所示：

![](/md/blog.007.png)

` `图4-5 管理员信息实体结构图

用户信息：用户名、姓名、头像、性别、联系电话、余额，实体属性图，如图4-6所示：

![](/md/blog.008.png)

图4-6用户信息实体属性图

商品信息：商品名称、分类、图片、规格、产地、保质期、商品详情、价格、单限、库存，实体属性图如图4-7所示。

![](/md/blog.009.png)

图4-7商品信息实体属性图

### 3.3.2数据表
数据库是计算机信息系统的基础。目前，电脑系统的关键与核心部分就是数据库。数据库开发的优劣对整个系统的质量和速度有着直接影响。

4.3.1 数据库设计原则

数据库的概念结构设计采用实体—联系（E-R）模型设计方法。E-R模型法的组成元素有：实体、属性、联系，E-R模型用E-R图表示，是提示用户工作环境中所涉及的事物，属性则是对实体特性的描述。在系统设计当中数据库起着决定性的因素。下面设计出这几个关键实体的实体—关系图。

4.3.2 数据库实体

数据模型中的实体（Entity），也称为实例，对应现实世界中可区别于其他对象的“事件”或“事物”。例如，公司中的每个员工，商铺中的每个商品。

本系统的E-R图如下图所示：。

allusers表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|username||150||255||
|3|pwd||150||255||
|4|cx||150||255||
|5|addtime|DateTime|8||19||

dingdanpingjia表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|3|dingdanbianhao||150||255||
|4|shangpinmingcheng|DateTime|8||255||
|5|yonghupingfen||150||255||
|6|tianjiatupian|DateTime|8||255||
|7|pingjianeirong||150||255||
|8|pingjiariqi|DateTime|8||255||
|9|yonghuming||150||255||
|10|lianxidianhua|DateTime|8||255||

shangpinxinxi表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|3|shangpinmingcheng||150||255||
|4|fenlei|DateTime|8||255||
|5|tupian||150||255||
|6|guige|DateTime|8||255||
|7|chandi||150||255||
|8|baozhiqi|DateTime|8||255||
|9|shangpinxiangqing||150||255||

shangpinzixun表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|4|zixunbiaoti|DateTime|8||255||
|5|leixing||150||255||
|6|tupian|DateTime|8||255||
|7|neirong||150||255||
|8|faburiqi|DateTime|8||255||

yonghu表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|4|yonghuming|DateTime|8||255||
|5|mima||150||255||
|6|xingming|DateTime|8||255||
|7|touxiang||150||255||
|8|xingbie|DateTime|8||255||
|9|lianxidianhua||150||255||





# 第四章 系统实现

管理员、用户登录功能是系统中一个非常重要的功能模块。这个函数模块需要做的第一件事是设计系统的安全性。不能说任何打开登录界面的人都可以进入系统。我们想控制管理。用户的用户名和密码，只有拥有权限的用户才能通过这个登录界面进入系统管理界面，这是非常重要的。用户想要登录和使用系统首先进入登录用户名和登录密码，然后我们使用程序来检索，检索数据库中的用户名信息一致输入用户名密码，如果输入用户名信息让用户登录时，如果它不存在，给一个提示,非法登陆，所以这个功能模块是非常重要的。

4.1管理员功能模块

登陆，管理员输入个人的用户名、密码、角色登录系统，如图4-1所示。

![](/md/blog.010.png)

图4-1登陆界面图


首页，管理员在首页页面查看个人中心、用户管理、商品资讯管理、商品分类管理、商品信息管理、订单评价管理、系统管理、订单管理等详细内容，如图4-2所示。

![](/md/blog.011.png)

图4-2首页界面图



个人中心，管理员对个人中心进行填写原密码、新密码、确认密码并进行添加、删除、修改以及查看，如图4-3所示。

![](/md/blog.012.png)

图4-3密码修改界面图

用户管理，管理员在用户信息可以查看用户名、姓名、头像、性别、联系电话、余额等详细内容，可进行添加、修改、删除操作，如图4-4所示。

![](/md/blog.013.png)

图4-4用户管理界面图



商品资讯管理，管理员在商品资讯管理页面中可以查看资讯标题、类型、图片、发布日期、内容等信息，并可根据需要对已有商品资讯信息进行查看、添加、修改等操作，如图4-5所示。

![](/md/blog.014.png)

图4-5商品资讯管理界面图

商品信息管理，管理员在商品信息管理页面中可以查看商品名称、分类、图片、规格、产地、保质期、商品详情、价格、单限、库存，进行搜索、添加、修改、删除操作，如图4-6所示。

![](/md/blog.015.png)

图4-6商品信息管理界面图

系统管理:管理员通过系统管理页面查看轮播图进行上传图片。进行添加、删除、修改以及查看并对整个系统进行维护等操作。，如图4-7所示。

![](/md/blog.016.png)


图4-7系统管理界面图


### 4.2.前台功能模块
网上生鲜销售系统，用户在系统首页可以查看首页、商品资讯、商品信息、我的、跳转到后台、购物车、客服等内容，如图4-8所示。

![](/md/blog.017.png)

图4-8前台首页功能界面图

用户注册、登录，在用户注册页面中可以填写用户名、密码、姓名、联系电话等信息进行注册、登录，如图4-9所示。

![](/md/blog.018.png)

![](/md/blog.019.png)

图4-9用户注册、登录界面图

商品信息，用户在商品信息页面中查看商品名称、分类、图片、规格、产地、保质期、商品详情、价格、单限、库存，可进行收藏、加入购物车、购买操作，如图4-10所示。

![](/md/blog.020.png)

图4-10商品信息界面图

我的，用户在个人中心页面中可以查看用户名、密码、姓名、头像、性别、联系电话、余额等内容，并点击余额可进行余额充值，且根据需要对已有个人信息可进行添加、修改、删除操作，如图4-11所示。

![](/md/blog.021.png)

![](/md/blog.022.png)

图4-11个人信息界面图

我的地址，用户在我的地址页面中进行添加联系人、手机号码、默认地址、选择地址等进行添加提交，如图4-12所示。

![](/md/blog.023.png)

图4-12我的地址界面图


4.3用户功能能模块


首页，用户在首页页面查看主页、个人中心、订单评价管理、我的收藏管理、订单管理等详细内容，如图4-13所示。

![](/md/blog.024.png)

图4-13首页界面图



个人中心，用户对个人信息进行查看用户名、密码、姓名、头像、性别、联系电话、余额并进行添加、删除、修改以及提交操作，如图4-14所示。

![](/md/blog.025.png)

图4-14个人信息界面图

订单评价管理，用户可以等已购买的商品进行评价，评价信息经过管理员进行审核，用户可订单评价进行查看、修改、删除操作，如图4-15所示。

![](/md/blog.026.png)

图4-15订单评价界面图



我的收藏管理，用户在前台页面收藏的商品进行查看，可进行查看、修改等操作，如图4-16所示。

![](/md/blog.027.png)

图4-16我的收藏管理界面图












