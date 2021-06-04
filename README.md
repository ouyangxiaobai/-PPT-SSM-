# -PPT-SSM-
高校智能排课系统设计毕业论文+开题报告+答辩PPT+项目源码（SSM）及数据库
下载地址：https://download.csdn.net/download/qq_31293575/19387909
摘  要
教育不仅是提高国民素质的重要途径同时也是提高国家现代化生产力水平的关键内容，因此教育事业越来越受到人们的重视。其中在高校教育事业中排课系统不仅是教学管理的一项重要内容同时也成为高校实现现代化的一项重要内容。目前，很多大学的排课工作都尝试用一定的排课算法来完成，结合学院情况，通过对学校的排课情况进行深入了解，并查阅和浏览了相关资料、软件，在此基础上我们对系统需求进行较彻底的分析，考虑到算法的复杂性及开发时间的限制，我们将排课系统定位于算法实现简单，但实用性强且人性化的系统，所以在设计该排课系统时应当满足如下要求：掌握学校所有课程和教师的信息，包括教室，班级，任课老师及课程时间。提供灵活的浏览和查询功能，可查看某个班级课程信息。可对课程信息和教师信息进行删除和编辑。可对课程进行变动管理和自动排课功能。在自动排课完成后，将排课异常信息给予反馈。
本课题所开发的系统将在Windows 10操作系统运行，以Java作为开发语言，利用合适的算法进行编排，并使用MySQL数据库技术设计一个排课系统，以期替代或部分替代人工，节省教务人员的精力，并有效减少手工排课中的各种冲突，提高排课效率。通过自己所学的知识完成登录和排课，管理课程及删除、添加、搜索所排课程的详细信息，在最终完成本系统的过程中对基于Java构架的项目开发有进一步的了解。使得教务管理人员能很好了解并运用排课系统来实现排课。
关键词：自动排课；智能排课；Java；Mysql
Abstract
Education is not only an important way to improve the quality of the people, but also a key content to improve the level of the country's modern productive forces. The scheduling system is not only an important content of teaching management, but also an important content of realizing modernization in colleges and universities. At present, many universities try to complete the scheduling work with a certain scheduling algorithm, combined with the college situation, through in-depth understanding of the school scheduling situation, and access to and browse the relevant information, software, on the basis of which we have a more thorough analysis of the system requirements, considering the complexity of the algorithm And the time limit of development, we will arrange the system to achieve simple algorithm, but practical and humanized system, so in the design of the scheduling system should meet the following requirements: master all the school curriculum and teacher information, including classroom, class, teacher and course time. Provides flexible browsing and query capabilities to view class information. course information and teacher information can be deleted and edited. Can carry on the change management and the automatic scheduling function to the course. After the automatic class scheduling is completed, the abnormal information of class scheduling will be given feedback.
The system developed in this project will run in the Windows 10 operating system, use Java as the development language, use appropriate algorithms to arrange, and use MySQL database technology to design a class scheduling system, with a view to replacing or partially replacing labor, saving the energy of academic staff, and effectively reducing all kinds of conflicts in manual class scheduling, and improving the efficiency of class scheduling. Complete the login and scheduling through the knowledge you have learned, manage the course and delete, add and search the details of the scheduled course, and have a further understanding of the project development based on the Java framework during the final completion of the system. To enable educational administration  People can understand and use scheduling system to achieve scheduling.
Keywords: automatic class scheduling; intelligent class scheduling; Java;Mysql
目  录
摘  要 I
Abstract II
1绪论 1
1.1选题背景及意义 1
1.2国内外研究现状 2
1.3研究主要内容 2
2系统工具 4
2.1 B/S结构 4
2.2 JSP技术 4
2.3 Tomcat虚拟服务器 5
2.4 MVC模式 5
2.5 SSM框架 6
2.6 MySQL数据库 10
3系统分析 11
3.1需求分析 11
3.2系统功能分析 12
3.3系统开发环境 12
4系统设计 14
4.1设计思想 14
4.2系统功能设计 14
4.3数据库设计 15
5系统实现 18
5.1登陆 18
5.2首页 18
5.3课程管理 19
5.4课程增加 19
5.5教师管理 20
5.6班级管理 20
5.7学生管理 21
5.8排课 21
5.9排课统计 22
5.10用户管理 23
6系统测试 24
6.1 程序调试 24
6.2 程序的测试 24
6.2.1 测试的重要性及目的 24
6.2.2 测试的步骤 25
6.2.3 测试的主要内容 26
总  结 28
参考文献 29
致  谢 31
                    

摘  要
教育不仅是提高国民素质的重要途径同时也是提高国家现代化生产力水平的关键内容，因此教育事业越来越受到人们的重视。其中在高校教育事业中排课系统不仅是教学管理的一项重要内容同时也成为高校实现现代化的一项重要内容。目前，很多大学的排课工作都尝试用一定的排课算法来完成，结合学院情况，通过对学校的排课情况进行深入了解，并查阅和浏览了相关资料、软件，在此基础上我们对系统需求进行较彻底的分析，考虑到算法的复杂性及开发时间的限制，我们将排课系统定位于算法实现简单，但实用性强且人性化的系统，所以在设计该排课系统时应当满足如下要求：掌握学校所有课程和教师的信息，包括教室，班级，任课老师及课程时间。提供灵活的浏览和查询功能，可查看某个班级课程信息。可对课程信息和教师信息进行删除和编辑。可对课程进行变动管理和自动排课功能。在自动排课完成后，将排课异常信息给予反馈。
本课题所开发的系统将在Windows 10操作系统运行，以Java作为开发语言，利用合适的算法进行编排，并使用MySQL数据库技术设计一个排课系统，以期替代或部分替代人工，节省教务人员的精力，并有效减少手工排课中的各种冲突，提高排课效率。通过自己所学的知识完成登录和排课，管理课程及删除、添加、搜索所排课程的详细信息，在最终完成本系统的过程中对基于Java构架的项目开发有进一步的了解。使得教务管理人员能很好了解并运用排课系统来实现排课。
关键词：自动排课；智能排课；Java；Mysql
Abstract
Education is not only an important way to improve the quality of the people, but also a key content to improve the level of the country's modern productive forces. The scheduling system is not only an important content of teaching management, but also an important content of realizing modernization in colleges and universities. At present, many universities try to complete the scheduling work with a certain scheduling algorithm, combined with the college situation, through in-depth understanding of the school scheduling situation, and access to and browse the relevant information, software, on the basis of which we have a more thorough analysis of the system requirements, considering the complexity of the algorithm And the time limit of development, we will arrange the system to achieve simple algorithm, but practical and humanized system, so in the design of the scheduling system should meet the following requirements: master all the school curriculum and teacher information, including classroom, class, teacher and course time. Provides flexible browsing and query capabilities to view class information. course information and teacher information can be deleted and edited. Can carry on the change management and the automatic scheduling function to the course. After the automatic class scheduling is completed, the abnormal information of class scheduling will be given feedback.
The system developed in this project will run in the Windows 10 operating system, use Java as the development language, use appropriate algorithms to arrange, and use MySQL database technology to design a class scheduling system, with a view to replacing or partially replacing labor, saving the energy of academic staff, and effectively reducing all kinds of conflicts in manual class scheduling, and improving the efficiency of class scheduling. Complete the login and scheduling through the knowledge you have learned, manage the course and delete, add and search the details of the scheduled course, and have a further understanding of the project development based on the Java framework during the final completion of the system. To enable educational administration  People can understand and use scheduling system to achieve scheduling.
Keywords: automatic class scheduling; intelligent class scheduling; Java;Mysql
目  录
摘  要 I
Abstract II
1绪论 1
1.1选题背景及意义 1
1.2国内外研究现状 2
1.3研究主要内容 2
2系统工具 4
2.1 B/S结构 4
2.2 JSP技术 4
2.3 Tomcat虚拟服务器 5
2.4 MVC模式 5
2.5 SSM框架 6
2.6 MySQL数据库 10
3系统分析 11
3.1需求分析 11
3.2系统功能分析 12
3.3系统开发环境 12
4系统设计 14
4.1设计思想 14
4.2系统功能设计 14
4.3数据库设计 15
5系统实现 18
5.1登陆 18
5.2首页 18
5.3课程管理 19
5.4课程增加 19
5.5教师管理 20
5.6班级管理 20
5.7学生管理 21
5.8排课 21
5.9排课统计 22
5.10用户管理 23
6系统测试 24
6.1 程序调试 24
6.2 程序的测试 24
6.2.1 测试的重要性及目的 24
6.2.2 测试的步骤 25
6.2.3 测试的主要内容 26
总  结 28
参考文献 29
致  谢 31
   转存失败重新上传取消    转存失败重新上传取消        转存失败重新上传取消  转存失败重新上传取消   转存失败重新上传取消


