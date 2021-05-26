# Expanded-knowledge-for-data-analysis

從事數據分析，除了分析技術外，我們也必須盡可能的了解所涉及的上下游。被我們inpute的數據怎麼來的？後端是怎麼處理的？技術是怎麼實現的？數據是怎麼管理的？也就是**數據的生產**，盡量貼近業務，能更進一步思考開發時程、實現架構、乃至產品化等，讓數據發揮出價值，也就是**數據的消費**。

這些知識外面書籍相對較少，大多是碎片化的，因此把近年在學習工作中看到不錯內容做了整理，記錄大佬們分享的知識點。方便review也分享出來，後續會不斷更新。
1. 大數據：關注大數據平台，例如hadoop、數據治理、數倉設計、數據中台等內容
2. 數據知識：偏向數據賦能的**泛知識**，例如數據體系、數據產品、用戶畫像等內容
3. 職涯：站在他人肩膀上，分享數據從業者在職場上的心路歷程
4. 互聯網人物誌：互聯網人物的浪漫故事

update time | comment 
--- | ---
2021-05-25 | 新增28篇，其中大數據新增5篇、埋點新增4篇、業務應用增加8篇、職涯新增11篇

## 大數據
- [有赞数据仓库元数据系统实践](https://mp.weixin.qq.com/s/JqNAKjG2Ug497YMfgtad1A)
- [有赞大数据平台安全建设实践](https://mp.weixin.qq.com/s/4G_OvlD_5uYr0o2m-qPW-Q)
- [大数据开发平台(Data Platform)在有赞的最佳实践](https://mp.weixin.qq.com/s/6udocRhscwv-mB5zW9lRwA)
- [腾讯、百度、小米等7家互联网各大厂的中台建设怎么样了？](https://mp.weixin.qq.com/s?__biz=MzI5OTk5OTM2Mw==&mid=2247498834&amp;idx=1&amp;sn=c64581e4ffbb55e38ba3b9c86a7466d0&source=41#wechat_redirect)
- [数据中台VS业务中台、数据中台VS数据仓库，到底有什么区别？](https://mp.weixin.qq.com/s?__biz=MzI5OTk5OTM2Mw==&mid=2247498772&amp;idx=1&amp;sn=22cfa162c17e00f864b988b03e552bc1&source=41#wechat_redirect)
- [数据库的前世今生](https://mp.weixin.qq.com/s/y1Q9S7QZjL4zbxuFzeTVBQ)
- [数据清洗(2)-checklist规范数据清洗的流程](https://mp.weixin.qq.com/s/9FDZF632dxn3vPmeC-wz1A)
- [大数据存储的进化史：从 RAID 到 Hadoop Hdfs](https://mp.weixin.qq.com/s/46uTHhSPhfhIaeTAaYKYBg)
- [美团配送数据治理实践](https://tech.meituan.com/2020/03/12/delivery-data-governance.html)
- [从数据仓库到大数据平台再到数据中台（内附13张架构图）](https://mp.weixin.qq.com/s/ys49a3wiu266q7q82przTg)
- [Hive千亿级数据倾斜解决方案](https://mp.weixin.qq.com/s/tg0T2gwJCl8ZvRO47HJywA)
- [数据分析引擎黑马 ClickHouse 最新技术的实践与应用](https://mp.weixin.qq.com/s/eJxR__fNFavBnI8sUJVnOQ)
- [通透！剖析数据仓库的谜底|学习笔记](https://mp.weixin.qq.com/s/9b3NGQ6N86Zk7Zt_OFBFTg)
- [Apache kudu在网易的实践](https://mp.weixin.qq.com/s/GgBnuB7r4G3Px7YHDARutQ)
- [关于数据中台的深度思考与总结（干干货）](https://mp.weixin.qq.com/s/zM_RxY65xfHp0d-26dWxvQ)

## 數據知識
 ### 指標與可視化
- [产品|作为数据产品经理，该如何搭建数据指标体系？](https://zhuanlan.zhihu.com/p/44687337)
- [腾讯QQ：产品指标体系如何搭建](http://www.199it.com/archives/743217.html)
- [腾讯QQ：数据体系建设之路 ](http://www.199it.com/archives/743254.html)
- [【干货】基于电商平台的数据分析基本指标体系](https://mp.weixin.qq.com/s/ukTmoK_fguG8_x9Q4C9ibw)
- [数据分析体系是什么？该怎么搭建？](https://mp.weixin.qq.com/s/_CB_KEQ8wCpwarfKGS4_OA)
- [如何做好一个BI项目的规划和需求定义？](https://mp.weixin.qq.com/s/y3SuF4e-A6anQmW7Mn2b0w)
 - [深度長文｜數據可視化的秘密](https://www.bfa.com.tw/blog/data-visualization-detail)
 -[推荐三款开源的BI报表分析和数据可视化工具](https://www.afenxi.com/65757.html)
- [开源 BI，我最终选择了 Metabase](https://juejin.im/post/6844904200728641550)
 
 ### 埋點
 - [有赞埋点实践](https://tech.youzan.com/track-1/)
 - [前端监控和前端埋点方案设计](https://segmentfault.com/a/1190000015864670)
 - [深度揭秘用户数据埋点采集技术 | 您的行踪已暴露](http://api.woshipm.com/data-analysis/3195604.html?sf=mobile&from=timeline&isappinstalled=0)
 - [想看埋点数据？产品经理有必要了解的埋点知识](https://mp.weixin.qq.com/s/djKo2uBDPUKADXX0wwmIDA)
 - [数据埋点是什么？设置埋点的意义是什么？](https://www.zhihu.com/question/36411025/answer/562103367?utm_source=wechat_session&utm_medium=social&utm_oi=812991846207868928)
 - [如何准确的标识用户 · 神策分析使用手册](https://manual.sensorsdata.cn/sa/latest/标识用户-7540285.html)
 - [数据模型 · 神策分析使用手册](https://manual.sensorsdata.cn/sa/latest/page-1573771.html)
 - [数据要埋点](https://mp.weixin.qq.com/s/kjpnA-XaeHjGCbMToLhiYg)
 - [数据人该知道的埋点体系（一）](https://mp.weixin.qq.com/s/GqOF61qvlgEQVI9oARVPfQ)
 - [日志异常检测初步实践与探索](https://mp.weixin.qq.com/s/ame9XL218FK1Du_by3_L5A)
 - [数据中台实战（一）：以B2B电商亿订为例谈数据埋点（产品经理视角）](https://mp.weixin.qq.com/s/3wpX1mEyNJ1y3zxESpsEYQ)
 
 ### 業務應用
 - [腾讯QQ大数据 ：从“增长黑客”谈数据驱动的方法](http://www.199it.com/archives/743270.html)
 - [内容APP如何给用户打标签&内容推送？](http://www.woshipm.com/pd/3214800.html)
 - [神策数据杜明翰：打造趁手、好用的标签&用户画像系统](http://baijiahao.baidu.com/s?id=1638778544586181095&wfr=spider&for=pc)
 - [百万标签发布了，这是怎样一种体验？](https://mp.weixin.qq.com/s?__biz=MzIwNDI0ODY1OA==&mid=2655929812&idx=1&sn=915d950405758a98cd0e4b098b2e88ef&chksm=8d79e6e9ba0e6fff48bf73966a648f3fdef4a87a2e18d0bd8e0a954015b46a0c0205004d423f&scene=21#wechat_redirect)
 - [如何有效推进百万标签库的治理？](https://www.afenxi.com/78491.html)
 - [DMP用户画像使用指南](https://mp.weixin.qq.com/s/DiUmT4HUXUIm8AVqsE9WCg)
 - [如何打造可以支撑N条产品线的标签平台](https://mp.weixin.qq.com/s/TX6V1dT17Ikiba4xpThXUA)
 - [第一个辟谣双黄连，为什么是腾讯医典？](https://mp.weixin.qq.com/s/4q6D5z4Uk5aNf0zzcteLcQ)
 - [如何在企业中从0-1建立一个数据/商业分析部门？](https://mp.weixin.qq.com/s/ADblJqYIaiDRTwE2IZWulg)
 - [产品人如何向女票解释，淘宝push的个性化推荐](https://www.cnwebe.com/articles/80704.html)
 - [荐读 | 用户画像](https://mp.weixin.qq.com/s/aaT_jj5fBVH6FuqLB5zlIw)
 - [如何精准推送不垃圾](https://mp.weixin.qq.com/s/Qe3HRvrbYlqdmnJ4Sgc6fg)
 - [用户画像标签体系包括哪些维度？有哪些应用场景？（附完整导图）](https://mp.weixin.qq.com/s/FrtzMfugEo83J96-2-xpwQ)
 - [用户画像如何从搭建到应用实战？](http://www.yoozai.com/archives/15332)
- [数据分析成果落地难？你需要注意这五个问题](https://mp.weixin.qq.com/s/2MftQhsfuIkzaoGAbvrndg)
- [“数据主义者”们的毒鸡汤](https://mp.weixin.qq.com/s/_8L8B7xvt_fe6GjQdZhylg)
- [我在字节看到的AB实验](https://mp.weixin.qq.com/s/2Ib_AxipX6bd6gkVAOAljQ)
- [思考产品架构的4个视角：业务、场景、数据/功能、实现](https://mp.weixin.qq.com/s/I-f-kX7sVSnx-FO4wg4e9Q)
- [工作七年后，我梳理了自己的产品工作流程](https://mp.weixin.qq.com/s/58fY_Z8Yj2YQjW5wrCyJ-g)
- [权限体系设计 | 网易有数BI功能品鉴](https://mp.weixin.qq.com/s/HLABe1FtzzPfH17h5fxG3g)
- [应用层数据安全管控实践—权限模型篇](https://mp.weixin.qq.com/s/pyF-H7BEmjyLNiF13tZ5oQ)
- [数据安全第3期|阿里、腾讯数据安全治理简览](https://mp.weixin.qq.com/s/5Hv6d9BfRkya-VicreWs2A)
- [数据安全第4期 | 数据安全中心建设思路分享](https://mp.weixin.qq.com/s/Flo8DkFk_89BK9SaNBuxyw)
- [从数据蛮荒到数据中台，数据产品演进的5个阶段](https://mp.weixin.qq.com/s/c7g2Xo9foYKtC9S79P386A)
- [深入解析SaaS产品的6种定价策略](https://mp.weixin.qq.com/s/7sXfHqZG6j5lIv2_IxqefA)
 
 
 ## 職涯
- [什麼！？資料科學家≠商業資料分析師？](https://www.hbrtaiwan.com/article_content_AR0007924.html)
- [屡屡碰壁之后，我终于拿下了 Airbnb 数据科学家岗位 ](https://36kr.com/p/1722741145601)
- [年薪 50 万以上的数据分析师？](https://www.zhihu.com/question/36850899)
- [在腾讯的八年，我的职业思考](https://mp.weixin.qq.com/s/E0TGTBCQA1jdmYMkGC_ucg)
- [营销转数据，两年半到P7，我都做了哪些？](https://www.sohu.com/a/169618084_398736)
- [斩获BATOffer！面试经历](https://www.infoq.cn/article/f3P6pLlWNK84qc*hI30A)
- [29岁年薪百万，晋升阿里最年轻P8之一，我想分享8点成长经验](https://maimai.cn/article/detail?fid=1358953876&efid=RWBT7VSn7kNOokpYLU3MWA)
- [会停下来思考的人，往往走得更远](https://36kr.com/p/1724611248129)
- [平台能力不是个人能力 | 职场14 点干货建议](https://mp.weixin.qq.com/s/BgyTAzgIGTAEQY1qDXHAfw)
- [Airbnb数据团队主管：如何将数据科学家的工作一分为三？](https://xw.qq.com/cmsid/20180817A0SS2C00)
- [BI取数者的职业发展之路？](https://mp.weixin.qq.com/s?__biz=MzIwNDI0ODY1OA==&mid=2655928843&idx=1&sn=86280eda790970682b2ee4183801cb7a&chksm=8d79e136ba0e6820140d7c6a4c1ab808ec9b3c63e7b99446ba7fa2cb4796e3228e67001de88e&scene=21#wechat_redirect)
- [一个电商数据分析师的经验总结](http://www.woshipm.com/operate/36334.html)
- [2020年，陆奇59岁：我给20、30、40岁年轻人的建议](https://mp.weixin.qq.com/s/ERro30-usUgJN-du3KDaCQ)
- [阿里五年老员工有什么话想对大家说？](https://mp.weixin.qq.com/s/Mq2E0xO_ng9V4GzmFuhq8g)
- [皮克斯两大创始人：如何“管理”我的老板乔布斯](https://mp.weixin.qq.com/s/pWay-ZcUWhBFgKN4d2xCVQ)
- [半年面100个数据分析师仅录取3个，真的是要求太高么？](https://zhuanlan.zhihu.com/p/42432339?utm_source=wechat_session&utm_medium=social&utm_oi=812991846207868928)
- [一个前腾讯员工自述：腾讯6年，我的月薪没有7万，但收获不止薪水](http://api.woshipm.com/zhichang/2350853.html?sf=mobile)
- [那些厉害的人，都是怎么走出迷茫的？](https://mp.weixin.qq.com/s/c2DFgtRsdfOVCT2YsCmqPg)
- [真正的高手，是如何判断趋势的？](https://mp.weixin.qq.com/s/VZGQ1jTwwIK-jmSPiSrf_w)
- [15种方法让你在工作中变得不可或缺](https://mp.weixin.qq.com/s/UA2p-9EB5jP0jfAEKutuiQ)
- [为什么技术同学需要有更多的业务思考？](https://mp.weixin.qq.com/s/cbGjoI9HW0E1dKFIbGDQFw)
- [一位互联网老兵的五次认知升级](https://mp.weixin.qq.com/s/i-e45K9-u_fbizWJ0adKhw)
- [能力和职位，总有一个要走在前面](https://mp.weixin.qq.com/s/e2US2sYN2yg-zEytGcHw9Q)
- [Facebook副总裁：给近百人做职业辅导，我发现了职业跃迁的秘密](https://mp.weixin.qq.com/s/DWTAj4cCvAldTV2eBPk8IQ)
- [认真读完，助你月薪2W到3W（系列之一）](https://mp.weixin.qq.com/s/2SsE_GQpm04zneG64d4s0A)
- [认真读完，助你月薪2W到3W（系列之二）](https://mp.weixin.qq.com/s/Wv3kahQGAeBZdPvVafwc5Q)
- [认真读完，助你月薪2W到3W（系列之三）](https://mp.weixin.qq.com/s/7rnWW4QpYn-lXNScKLJOXg)
- [工作 10 年后转行程序员，如今 35+ 岁并不焦虑！](https://mp.weixin.qq.com/s/hlTBU1UX590q67w4rK7AOQ)
- [陆奇最新演讲：2021年，程序员们应该如何提升自我？](https://mp.weixin.qq.com/s/EEKHkLZTrp6SE3G7xQXb)EA
- [全面认识数据产品经理](https://mp.weixin.qq.com/s/asVS1Aj8AOK32zcFUX5TJA)
- [从2K到大厂Offer，外包数仓逆袭需贵人相助！](https://mp.weixin.qq.com/s/rUU55LWjJe524G9_bX785g)
- [【必读】我如何做面试官](https://mp.weixin.qq.com/s/Rf8H0fkprtYm2WzvJ8piBw)



## 互聯網人物誌
- [阿里云这群疯子](http://www.woshipm.com/it/1520333.html)
- [张小龙的四小时演讲没有用哪些词？](https://mp.weixin.qq.com/s/hT45I5TsNv18AAfNsx81PA)
- [永远跟用户在一起 —— 张小龙 4 小时现场分享 2 万字原汁原味呈现](https://mp.weixin.qq.com/s?__biz=MzU4NDc3NzUyMw==&mid=2247487778&amp;idx=1&amp;sn=29a40f10dbf2d4f5e1a7e14fc4a36851&source=41#wechat_redirect)
- [全面反思腾讯的战略](https://mp.weixin.qq.com/s/bgDgyu1D6DpvhARd0drEYw)
- [阿里接班人张勇的用人观](https://mp.weixin.qq.com/s/lnCQVgCwJ0zwKZbexy_NAQ)
- [互联网诞生记：风起于青萍之末](https://mp.weixin.qq.com/s/ccXQKPvYN2Kgh_alUutKvA)
- [金山办公上市，雷军心愿了却！](https://mp.weixin.qq.com/s/KnwLvnMXyi8pypPrJewrSg)
- [马云、马化腾、贝索斯···中美互联网巨头爱情史](https://mp.weixin.qq.com/s/UPH6BUh9azKcMPHFjBbOXg)
- [刘强东第二次“二次创业”](https://mp.weixin.qq.com/s/MgwKCwKkiyLRONFW2Jtm3A)
- [5000字一文读懂人人网与Facebook的前世今生](https://mp.weixin.qq.com/s/WDU-6cU51LofnPIr9zTp_Q)
- [字节跳动空降COO, Kevin Mayer什么来路？](https://mp.weixin.qq.com/s/QPNcPkYNtLni-AyfsJaNHg)
- [大佬们的35岁](https://mp.weixin.qq.com/s/w2kvHWoFxMW24bSz6QmXLA)


