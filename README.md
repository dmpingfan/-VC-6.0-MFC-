# -VC-6.0-MFC-
本工程利用ADO方式链接Access数据库文件
之所以用VC++6.0做MFC是因为我们这学期c++的课设。
作品分为页面设计、软件设计两个环节。
基于MFC开发一个管理学生成绩的程序，该系统主要功能有:
(1) 学生基本信息和学生成绩的管理
学生基本信息:姓名、学号、专业、班级、所属院系。
各科成绩:高数、英语、VC+ +程序设计、物理、体育。
系统可以完成对各类信息的添加、修改、删除、浏览。
(2)成绩的统计汇总
可以计算班级平均成绩，某科最高成绩，最低成绩，优、良、中、及格、不及格各个成绩等级的人数。
每位同学的总成绩、班级总成绩，总成绩排名等。可以自己根据需要合理设计。
(3) 成绩信息查询
可以按照班级、成绩范围、科目等查询。可以自己根据需要合理设计。
(4)系统登录功能
进入系统，需要登录，具有用户登录和密码功能。
都是些基本功能，经过几天的爆肝，简单的了解到如果不用链接数据库文件的方式话，对于存储和删除一类的操作要用到链表，我个人数据结构学的很渣，所以果断放弃了这种方法。
我上传到Github上供大家学习，其实CSDN上也有许多不错的帖子和工程文件，我反正是看不太懂，所以我的工程当然是按照我的方式和理解来搭建的。有哪里有BUG欢迎大家提出来！
大家互相促进学习！
注：有一些小bug还是要说的，本工程并未对所有的功能进行实现，一是本人还是太菜，上课基本是水过去的，二是老师给的时间比较少，中途还突然加了需求。
(1)在登录的时候，链接的Access数据库文件只能用第一个人的账号和密码登录，后面的都不可以，即便在注册功能里新注册的用户也不能登录，我认为这里是因为没有加循环语句，最后也没有时间去添加了。
(2)在教师进行查、改操作时，如果误将数字输入成非数字时，系统并不会对其进行提醒。
(3)本工程以下功能未实现:
成绩的统计汇总，成绩信息查询。
## www.humorous.top这个我的个人小站，欢迎大家来访，上面也会不定期更新一些文章。
