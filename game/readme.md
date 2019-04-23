# 用户贷款风险预测

竞赛信息来源[DC竞赛](https://www.dcjingsai.com/common/cmpt/%E7%94%A8%E6%88%B7%E8%B4%B7%E6%AC%BE%E9%A3%8E%E9%99%A9%E9%A2%84%E6%B5%8B_%E8%B5%9B%E4%BD%93%E4%B8%8E%E6%95%B0%E6%8D%AE.html)


# 数据

1. 数据总体概述
参赛者可用的训练数据包括用户的基本属性user_info.txt、银行流水记录bank_detail.txt、用户浏览行为browse_history.txt、信用卡账单记录bill_detail.txt、放款时间loan_time.txt，以及这些顾客是否发生逾期行为的记录overdue.txt。（注意：并非每一位用户都有非常完整的记录，如有些用户并没有信用卡账单记录，有些用户却没有银行流水记录。）
相应地，还有用于测试的用户的基本属性、银行流水、信用卡账单记录、浏览行为、放款时间等数据信息，以及待预测用户的id列表。

| 数据表 | 数据表说明 |
| :---: | :---:|
| user_info.txt | 用户的基本属性|
