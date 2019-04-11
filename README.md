# Knowledge-driven-dialogue
## 2019 Language and Intelligence Challenge--BaiDu
---  
### 竞赛详情
1. 竞赛任务  
给定对话目标g及相关知识信息M=f1,f2,...,fn。要求参评的对话系统输出适用于当前对话序列H=u1,u2,...,ut-1的机器回复ut 使得对话自然流畅、信息丰富而且符合对话目标的规划。 在对话过程中，机器处于主动状态，引导用户从一个话题聊到另一个话题。因此，对话系统为机器设定了一个对话目标，g 为“START->TOPIC_A->TOPIC_B”, 表示从冷启动状态主动聊到话题A，然后进一步聊到话题B， 提供的相关知识信息包括：话题A的知识信息，话题B的知识信息，话题A和话题B的关联信息。  
2. 数据简介  
数据中的知识信息来源于电影和娱乐人物领域有聊天价值的知识信息，如票房、导演、评价等，以三元组SPO的形式组织，对话目标中的话题为电影或娱乐人物实体。  
数据集中共有3万session，约12万轮对话，其中10万训练集，1万开发集，1万测试集，报名后可在数据下载区域下载。  
3. 评价方法  
3.1 自动评估指标  
 (1) F1: 评估输出回复相对于标准回复在字级别上的准确召回性能，是评估模型性能的主指标；  
 (2) BLEU: 评估输出回复相对于标准回复在词级别上的性能，是评估模型性能的辅助指标；  
 (3) DISTINCT: 评估输出回复的多样性，是评估模型性能的辅助指标；  
以上自动指标将用于排行榜上的排行。  
3.2 人工评估指标  
排行榜前10个对话系统进入人工评估阶段，从流畅性、一致性和主动性等几个维度进行评估，最终排名以人工评估结果为依据。  

---
### 竞赛环境
#### 利用基线开源系统测试
- 基于pytorch框架实现的生成式模型

---
Updated 11 April 2019.  
