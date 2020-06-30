# pride

【为梦想而奋斗，Day0】2020.06.25

1.熟悉rasa开源平台，可以下载并尝试官方demo
https://rasa.com/

2.目前对话系统领域比较前沿的竞赛DSTC（Dialogue System Technology Challenge），今年是第九届，如果感兴趣可以组队参加
https://www.aclweb.org/portal/node/4444
如果做细分，可以从这个DSTC入手，但是对资源要求较高

3.讨论结果


（1）需要从已有个人经验中和对话数据中，穷举多样的应用场景

（2）需要明确系统的主要功能场景：
信息查询（查询号码、号码反查、来电查询），电话转接、信息增改
信息查询分为三类：一是通过名字、职务、单位查电话号码；二是通过电话号码查询姓名、职务、单位；三是询问总机什么时间有人接过他

4.推荐1片博客，关于对话系统发展方向的5个层级，目前主要还是停留在第二等级
https://blog.rasa.com/5-levels-of-conversational-ai-2020-update/

【为梦想而奋斗，Day1】2020.06.26

讨论结果

1.首先不关注技术细节，首先把系统通用平台进行熟悉

【为梦想而奋斗，Day2】2020.06.27

1.完成project的创建，计划首先将其替换为简单英文查询系统

2.替换的步骤，首先更改系统的domain.yml主要是增加2个intents，然后增加2个stories，详情看相关文件.

【为梦想而奋斗，Day4】2020.06.29

1.齐航完成rasa系统的安装

讨论结果
1.完成信息查询的场景枚举

2.将系统改为中文系统