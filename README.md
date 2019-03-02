之前在公众号提过，我写了一本书，现在这本书终于面世了，这本书就是『对比Excel，轻松学习Python数据分析』，这本书是写什么的，以及这本书怎么写的，相信大家通过书名就能了解一二，但还是有必要专门写一篇文章来详细介绍一下。
![书就是长这个样子啦](https://i.loli.net/2019/02/17/5c68ede45d4e8.jpg)


# 1.本书简介
集Python、Excel、数据分析为一体是本书的一大特色。 

本书围绕整个数据分析的常规流程：熟悉工具—明确目的—获取数据—熟悉数据—处理数据—分析数据—得出结论—验证结论—展示结论进行Excel和Python的对比实现，告诉 你每一个过程中都会用到什么，过程与过程之间有什么联系。本书既可以作为系统学习数 据分析操作流程的说明书，也可以作为一本数据分析师案头必备的实操工具书。 

本书通过对比Excel功能操作去学习Python的代码实现，而不是直接学习Python代码，大大降低了学习门槛，消除了读者对代码的恐惧心理。适合刚入行的数据分析师，也适合对Excel比较熟练的数据分析师，以及从事其他岗位想提高工作效率的职场人。 
# 2.为什么要写这本书
本书既是一本数据分析的书，也是一本Excel数据分析的书，同时还是一本Python数据分析的书。在互联网上，无论是搜索数据分析，还是搜索Excel数据分析，亦或是搜索Python数据分析，我们都可以找到很多相关的图书。既然已经有这么多同类题材的书了，为什么我还要写呢？因为在我准备写这本书时，还没有一本把数据分析、Excel 数据分析、Python数据分析这三者结合在一起的书。 

为什么我要把它们结合在一起写呢？那是因为，我认为这三者是一个数据分析师必备的技能，而且这三者本身也是一个有机统一体。数据分析让你知道怎么分析以及分析什么；Excel和Python是你在分析过程中会用到的两个工具。
# 3.为什么要学习Python 
既然Python在数据分析领域是一个和Excel类似的数据分析工具，二者实现的功能都一样，为什么还要学 Python，把Excel学好不就行了吗？我认为学习Python的主要原因有以下几点：

#### 1．在处理大量数据时，Python的效率高于Excel

当数据量很小的时候，Excel和Python的处理速度基本上差不多，但是当数据量较大或者公式嵌套太多时，Excel 就会变得很慢，这个时候怎么办呢？我们可以使用Python，Python对于海量数据的处理效果要明显优于 Excel。用Vlookup函数做一个 实验，两个大小均为23MB的表（6 万行数据），在未作任何处理、没有任何公式嵌套之前，Excel中直接在一个表中用 Vlookup 函数获取另一个表的数据需要20秒（我的 计算机性能参数是 I7、8GB 内存、256GB 固态硬盘），配置稍微差点的计算机可能打开这个表都很难。但是用Python实现上述过程只需要580毫秒，即 0.58 秒，是 Excel 效率的 34 倍。 

#### 2．Python可以轻松实现自动化

你可能会说Excel的VBA也可以自动化，但是VBA主要还是基于Excel内部的 自动化，一些其他方面的自动化VBA 就做不了，比如你要针对本地某一文件夹下面的文件名进行批量修改，VBA就不能实现，但是Python可以。 

#### 3．Python可用来做算法模型

虽然你是做数据分析的，但是一些基础的算法模型还是有必要掌握的，Python可以让你在懂一些基础的算法原理的情况下就能搭建一些模型，比如你可以使用聚类算法搭建一个模型去对用户进行分类。 

# 4.为什么要对比Excel学习Python 

Python虽然是一门编程语言，但是在数据分析领域实现的功能和Excel的基本功 能一样，而Excel又是大家比较熟悉、容易上手的软件，所以可以通过Excel数据分析去对比学习Python数据分析。对于同一个功能，本书告诉你在Excel中怎么做，并告诉你对应到Python中是什么样的代码。例如数值替换，即把一个值替换成另一个值， 对把“Excel”替换成“Python”这一要求，在Excel中可以通过鼠标点选实现，如下图所示。:

![](https://i.loli.net/2019/02/17/5c68cdc702ce9.png)
 
在 Python 中则通过具体的代码实现，如下所示: 
```
df.replace(“Excel”,”Python”)#表示将表df中的Excel替换成Python 
```
本书将数据分析过程中涉及的每一个操作都按这种方式对照讲解，让你从熟悉的Excel操作中去学习对应的 Python实现，而不是直接学习Python代码，**大大降低了学习门槛，消除了大家对代码的恐惧心理**。这也是本书的一大特色，也是我为什么要写本书的主要原因，就是希望帮助你不再惧怕代码，让你可以像学Excel数据分析一 样，轻松学习Python数据分析。 

# 5.本书目录
本书分为三篇，入门篇主要讲数据分析的一些基础知识，介绍数据分析是什么，为什么要做数据分析，数据分析究竟在分析什么，以及数据分析的常规流程；实践篇围绕数据分析的整个流程，为了让大家便于理解，又将数据分析整个过程与买菜做饭相联系，分别介绍每一个步骤中的操作，这些操作用Excel如何实现，用Python又如何实现；进阶篇：介绍几个实战案例，让你体会一下在实际业务中如何使用Python。

**入门篇**
第 1 章  数据分析基础

**实践篇**
第 2 章  熟悉锅——Python 基础知识
第 3 章  Pandas 数据结构 
第 4 章  准备食材——获取数据源
第 5 章  淘米洗菜——数据预处理
第 6 章  菜品挑选——数据选择
第 7 章  切配菜品——数值操作
第 8 章  开始烹调——数据运算
第 9 章  炒菜计时器——时间序列
第 10 章  菜品分类——数据分组/数据透视表
第 11 章  水果拼盘——多表拼接 
第 12 章  盛菜装盘——结果导出
第 13 章  菜品摆放——数据可视化

**进阶篇**
第 14 章  典型数据分析案例 
第 15 章  NumPy数组

# 6.专家推荐
来看看一些行业大佬怎么讲，在此再次感谢为这本书写推荐的各位老师。
 ---
数据分析的门槛可以很高，也可以很低，但它一定很重要！这本书不是晦涩难懂的学术教材，而是适合不同层次职场人士学习的工具书，通俗易懂的阐述了数据分析的基础及在不同工具下的主要实践，对于初学者或是资深数据爱好者都有很好的启发和助益。

by--黄小伟 有赞数据分析团队负责人/R语言中文社区创始人
 ---
大数据时代，数据分析是每个职场人士的必备技能之一，你掌握了吗？本书以一种人人都熟悉的炒菜的故事作为主线，用轻松的语言深入浅出的讲述数据分析的各个核心要素，是初入数据分析领域的同学一个很好的入门教材，同时也是有一定分析经验同学的参考工具书。

by--黄崇杰 平安壹钱包数据营销总监
 ---
数据分析工作中的80%以上的时间都在处理底层数据。一份“高大上”的报告实际上只占了分析师不到20%的时间。张老师的这本书出现的正是时候——Excel好用但是在大数据是的效率低，但是结合上Python的能力以后，会让分析师如虎添翼。数据分析师们动动手指产出INSIGHT的美好时光指日可待了！

by--刘洋 阿里巴巴高级产品专家
 ---
本书为传统数据分析人员迈向大数据时代指明方向，并终将带来竞争优势

by--闵军 找钢网数据中心总经理
 ---
一本少见的结合了Excel及Python来学习数据分析的好书。作为基本的数据分析工具，Excel技能及Python技能的掌握，对于数据分析师来说都是十分必要的，相信任何一个有志于学习数据分析的朋友，都能从此书收获良多。

by--张浩彬 广东柯内特环境科技有限公司首席数据科学家
 ---
本书是实用并且可操作，通过Python来分析数据，从书中内容看出作者在陈列操作步骤过程中包括了大量的分析思维，对于那些想转型或者入门想从事数据分析的同学，是一步很好的教材级书本。

by--赵良 中国统计网联合创始人 
 ---
作为这几年最火的语言之一，Python在数据分析方面的能力几乎是无限的，可能唯一的限制就在于使用者本身的能力和认知。对数据分析师而言，用Python做数据分析已经成为必需技能。这本Python数据分析基于熟知的Excel做对照和解释，深入浅出，娓娓道来。既兼顾到不同工具的应用场景，又将使用技巧融入其中。推荐刚入门的数据分析师阅读。

by--宋天龙 《Python数据分析与数据化运营》作者
 ---
Excel与Python都是数据分析利器，本书从Excel与Python的实际作用出发，书中的知识都是作者多年一线工作的经验总结。

by-- 王颖祥 永辉超市大数据合伙人

# 7.本书样章

全书采用对比Excel操作的方式来讲解Python代码，以下为书中介绍数据透视表的部分内容：

数据透视表实现的功能与数据分组相类似但又不同，数据分组是在一维(行)方向上不断进行拆分，而数据透视表是在行列方向上同时进行拆分。

下图为数据分组与数据透视表的对比图：

![](https://ws1.sinaimg.cn/large/006JdmJily1fuvf0sw8qcj30tf0ep0th.jpg)

数据透视表不管是在Excel还是Python中都是一个很重要的功能，大家都需要熟练掌握。

**Excel实现**

Excel中的数据透视表在插入菜单栏中，选择插入透视表以后就会看到下图的界面。下图左侧为数据表中的所有字段，右侧为数据透视表选项，把左侧字段拖到右侧对应的框中即完成了数据透视表的制作。

![](https://ws1.sinaimg.cn/large/006JdmJily1fuvf6i1dafj30hs0c8q51.jpg)

下图为让客户分类作为行标签，区域作为列标签，用户ID作为值，且值字段的计算类型为计数的结果。

![](https://ws1.sinaimg.cn/large/006JdmJily1fuvf84m0r9j30c703xwek.jpg)

在数据透视表中把多个字段作拖到行对应的框作为行标签，把多个字段拖到列对应的框作为列标签，把多个字段拖到值对应的框作为值，且可以对不同的值字段选择不同的计算类型，大家自行练习。

**Python实现**

在Python中的数据透视表制作原理与Excel制作原理是一样的。Python中的数据透视表用到的是pivot_table()方法。

pivot_table的全部参数如下：
```
pd.pivot_table(data, values=None, index=None, columns=None, aggfunc='mean',
                   fill_value=None, margins=False, dropna=True, margins_name='All')
                   
#data表示要做数据透视表的整个表
#values对应Excel中值那个框
#index对应Excel中行那个框
#columns对应Excel中列那个框
#aggfunc表示对values的计算类型
#fill_value表示对空值的填充值
#margins表示是否显示合计列
#dropna表示是否删除缺失,一整行全为缺失值
#margins_name表示合计列列名
```

接下来看一些具体实例：

客户分类作为index，区域作为columns，用户ID作为values，对values执行count运算运行结果：
```
>>>pd.pivot_table(df,values = "用户ID",columns = "区域",index = "客户分类",aggfunc='count')
区域	一线城市  三线城市	二线城市
客户分类			
A类	    1.0       NaN	    2.0
B类	    NaN	      2.0	    NaN
C类	    1.0	      NaN	    NaN
```

上面的运行结果和Excel的不同的就是没有合计列，Python透视表中的合计列默认是关闭，让其等于True就可以显示出来。
```
pd.pivot_table(df,values = "用户ID",columns = "区域",index = "客户分类",aggfunc='count',margins = True)
区域	一线城市  三线城市	二线城市  All
客户分类				
A类	    1.0	      NaN	    2.0	      3
B类	    NaN	      2.0	    NaN	      2
C类	    1.0 	  NaN	    NaN	      1
All	    2.0	      2.0	    2.0	      6
``` 

合计列名称默认为All，可以通过设置参数margins_name的值进行修改。

```
pd.pivot_table(df,values = "用户ID",columns = "区域",index = "客户分类",aggfunc='count',margins = True,margins_name = "总计")
区域	一线城市  三线城市	二线城市  总计
客户分类				
A类	    1.0	      NaN	    2.0	      3
B类	    NaN	      2.0	    NaN	      2
C类	    1.0 	  NaN	    NaN	      1
总计	   2.0	     2.0	   2.0	     6
``` 

NaN表示缺失值，我们可以通过设置参数fill_value的值对缺失值进行填充。

```
#将缺失值填充为0
pd.pivot_table(df,values = "用户ID",columns = "区域",index = "客户分类",aggfunc='count',margins = True,fill_value = 0)
区域	一线城市  三线城市	二线城市  All
客户分类				
A类	    1         0   	    2	      3
B类 	   0   	     2     	   0	     2
C类	    1   	  0     	0      	  1
All	    2   	  2     	2	      6
``` 

aggfunc用来表示计算类型，当只传入一种类型时，表示对所有的值字段都进行同样的计算；如果需要对不同的值进行不同的计算类型，需要传入一个字典，键为列名，值为计算方式,下面对用户ID进行计数、对7月销量进行求和：

```
pd.pivot_table(df,values = ["用户ID","7月销量"],,columns = "区域",index = "客户分类",aggfunc={"用户ID":"count","7月销量":"sum"})
     7月销量	                    用户ID
区域 一线城市 三线城市 二线城市	一线城市 三线城市	二线城市
客户分类						
A类	 6.0	  NaN	   50.0	    1.0	     NaN	    2.0
B类	 NaN      46.0 	   NaN	    NaN	     2.0	    NaN
C类	 7.0	  NaN	   NaN	    1.0	     NaN	    NaN
```

为了便于进一步的分析与处理，我们一般对数据透视表的结果也会重置索引，利用的方法同样是reset_index()。

```
pd.pivot_table(df,values = "用户ID",columns = "区域",index = "客户分类",aggfunc='count')
区域	一线城市  三线城市	二线城市
客户分类			
A类	    1.0       NaN	    2.0
B类	    NaN	      2.0	    NaN
C类	    1.0	      NaN	    NaN
pd.pivot_table(df,values = "用户ID",columns = "区域",index = "客户分类",aggfunc='count').reset_index()
区域	客户分类	    一线城市	    三线城市	    二线城市
0	    A类	        1.0     	NaN	        2.0
1   	 B类     	 NaN	      2.0     	 NaN
2	    C类	        1.0	        NaN	        NaN
```

# 8.福利时刻
**福利1**
在微信公众号后台回复『我想试读』，即可获得本书试读部分+Python数据分析师知识图谱电子版一份。
![这样输入](https://i.loli.net/2019/02/19/5c6b4e7fd31f7.png)

**福利2**
购买纸质书可获得以下福利：
1、赠送纸质Python数据分析师知识图谱一份
2、赠送价值89元的『入职数据分析师』电子书一份
3、赠送价值99元的『数据分析师入职第一课』视频课程一套
4、加入读者群与作者随时交流
5、加入我组建的打卡圈子，30天学会Python数据分析
tip:可加入读者群咨询上述福利获取方式
![Python数据分析师知识图谱](https://i.loli.net/2019/02/17/5c68ef1340ec8.jpg)
![数据分析师入职第一课](https://i.loli.net/2019/02/19/5c6b52708f03b.jpg)

# 9.购买方式
目前书籍已经在京东、淘宝、当当网全面上线，大家搜索『对比Excel，轻松学习Python数据分析』即可进行购买，请认准小黄书哦。也可以直接扫描下方二维码进行购买，本书目前在当当网可以**享受满100减50**的活动哦。
![](https://i.loli.net/2019/02/19/5c6c12fc9bc0d.jpg)
![](https://i.loli.net/2019/02/19/5c6c12fc98218.jpg)
![](https://i.loli.net/2019/02/20/5c6d3a50b8442.jpg)
![当当.jpg](https://i.loli.net/2019/02/23/5c715a915e80a.jpg)
如果你已经购买了纸质书，可添加我为好友(请备注“读者”)，我会邀请你进读者群，同时也会邀请你进入打卡圈子，30天带你学会Python数据分析，有任何关于书相关的问题也都可以咨询我。

![个人微信](https://i.loli.net/2019/02/20/5c6d3adbda39c.jpg)