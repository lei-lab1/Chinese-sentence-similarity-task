# Chinese sentence similarity
中文问题句子相似度计算
## 相关比赛

### [CHIP 2019 task2](https://biendata.com/competition/chip2019/)

#### 赛题任务描述

> 本次比赛是chip2019中的评测任务二，由平安医疗科技主办。chip2019会议详情见链接：http://cips-chip.org.cn/evaluation
>
> 迁移学习是自然语言处理中的重要一环，其主要目的是通过从已学习的相关任务中转移知识来改进新任务的学习效果，从而提高模型的泛化能力。
>
> 本次评测任务的主要目标是针对中文的疾病问答数据，进行病种间的迁移学习。具体而言，给定来自5个不同病种的问句对，要求判定两个句子语义是否相同或者相近。所有语料来自互联网上患者真实的问题，并经过了筛选和人工的意图匹配标注。

#### 解决方案

- 1st [report](https://github.com/ShuaichiLi/Chinese-sentence-similarity-task/blob/master/CHIP2019_top3/%E8%AF%84%E6%B5%8B2-%E7%AC%AC1%E5%90%8D-%E5%9F%BA%E4%BA%8EBERT%E4%B8%8E%E6%8F%90%E5%8D%87%E6%A0%91%E6%A8%A1%E5%9E%8B%E7%9A%84%E8%AF%AD%E4%B9%89%E5%8C%B9%E9%85%8D%E6%96%B9%E6%B3%95-wzm.pptx)
- 2nd [report](https://github.com/ShuaichiLi/Chinese-sentence-similarity-task/blob/master/CHIP2019_top3/%E8%AF%84%E6%B5%8B2-%E7%AC%AC2%E5%90%8D-%EF%BC%88upside-down%E5%9B%A2%E9%98%9F%EF%BC%89%E5%B9%B3%E5%AE%89%E5%8C%BB%E7%96%97%E7%A7%91%E6%8A%80%E7%96%BE%E7%97%85%E9%97%AE%E7%AD%94%E8%BF%81%E7%A7%BB%E5%AD%A6%E4%B9%A0%E6%AF%94%E8%B5%9B-%E8%AF%84%E6%B5%8B%E6%8A%A5%E5%91%8A.pptx)
- 3rd [report](https://github.com/ShuaichiLi/Chinese-sentence-similarity-task/blob/master/CHIP2019_top3/%E8%AF%84%E6%B5%8B2-%E7%AC%AC3%E5%90%8D-CHIPS_%E4%BB%BB%E5%8A%A1%E4%BA%8C_%E8%AF%84%E6%B5%8B%E6%8A%A5%E5%91%8A.pptx)
- A2B4 [code](https://github.com/woaiwwc/chip2019_task2)
- A9B7 [code](https://github.com/ZhengZixiang/chip2019_task2_question_pairs_matching)
- unknown [code](https://github.com/jacky5124/CHIP2019)

### [CCKS 2018 微众银行智能客服问句匹配大赛](https://biendata.com/competition/CCKS2018_3/)

#### 赛题任务描述

> 评测任务的主要目标是针对中文的真实客服语料，进行问句意图匹配。集给定两个语句，要求判定两者意图是否相同或者相近。所有语料来自原始的银行领域智能客服日志，并经过了筛选和人工的意图匹配标注。

#### 解决方案

- 1st [report](http://ceur-ws.org/Vol-2242/paper09.pdf)
- 2nd [report](http://ceur-ws.org/Vol-2242/paper10.pdf)
- 4th [report](http://ceur-ws.org/Vol-2242/paper08.pdf)
- 5th [report](http://ceur-ws.org/Vol-2242/paper11.pdf)


### [2018 ATEC 蚂蚁金服 金融大脑-金融智能NLP服务](https://dc.cloud.alipay.com/index#/topic/intro?id=3)

#### 赛题任务描述

> 问题相似度计算，即给定客服里用户描述的两句话，用算法来判断是否表示了相同的语义。

> 示例：  
a.“花呗如何还款” --“花呗怎么还款”：同义问句  
b.“花呗如何还款” -- “我怎么还我的花被呢”：同义问句  
c.“花呗分期后逾期了如何还款”-- “花呗分期后逾期了哪里还款”：非同义问句  
> 对于例子a，比较简单的方法就可以判定同义；对于例子b，包含了错别字、同义词、词序变换等问题，两个句子乍一看并不类似，想正确判断比较有挑战；对于例子c，两句话很类似，仅仅有一处细微的差别 “如何”和“哪里”，就导致语义不一致。

#### 解决方案

- 12th [code](https://github.com/raven4752/huabei)
- 14th [code](https://github.com/world2vec/atec_2018_nlp)
- 15th [code](https://blog.csdn.net/cuihuijun1hao/article/details/82318792)
- 16th [code](https://github.com/zle1992/atec)
- 18th [code](https://github.com/ziweipolaris/atec2018-nlp)
- other [code](https://jianwenjun.xyz/2018/07/13/%E8%9A%82%E8%9A%81%E9%87%91%E8%9E%8DNLP%E7%AB%9E%E8%B5%9B%E2%80%94%E2%80%94%E6%96%87%E6%9C%AC%E8%AF%AD%E4%B9%89%E7%9B%B8%E4%BC%BC%E5%BA%A6%E8%B5%9B%E9%A2%98%E6%80%BB%E7%BB%93/)


### [第三届魔镜杯大赛](https://ai.ppdai.com/mirror/goToMirrorDetail?mirrorId=1)

#### 赛题任务描述

> 智能客服聊天机器人场景中，待客户提出问题后，往往需要先计算客户提出问题与知识库问题的相似度，进而定位最相似问题，再对问题给出答案。

#### 解决方案

- 6th [code](https://github.com/qrfaction/paipaidai)
- 9th [report](https://blog.csdn.net/u012891055/article/details/86624033)
- 12th [report](https://www.jianshu.com/p/827dd447daf9) [code](https://github.com/LittletreeZou/Question-Pairs-Matching)


### [CHIP 2018 task2](https://www.biendata.com/competition/chip2018/)

#### 赛题任务描述

> 主要目标是针对中文的真实患者健康咨询语料，进行问句意图匹配。给定两个语句，要求判定两者意图是否相同或者相近。所有语料来自互联网上患者真实的问题，并经过了筛选和人工的意图匹配标注。

#### 解决方案

- 1st [report](<https://github.com/ShuaichiLi/Chinese-sentence-similarity-task/blob/master/CHIP2018_top3/1st_team_DUTIR.pdf>)
- 2nd [report](<https://github.com/ShuaichiLi/Chinese-sentence-similarity-task/blob/master/CHIP2018_top3/2nd_team_deadline%20.pdf>)
- 3rd [report](<https://github.com/ShuaichiLi/Chinese-sentence-similarity-task/blob/master/CHIP2018_top3/3rd_team_chip2018-%E6%B9%96%E4%BA%BA%E6%80%BB%E5%86%A0%E5%86%9B%40InplusLab.pdf>)
- 6th [report](https://linux.ctolib.com/TianyuZhuuu-CHIP2018.html)
- 9th [report](https://blog.csdn.net/cuihuijun1hao/article/details/84554012)


To be continued...





