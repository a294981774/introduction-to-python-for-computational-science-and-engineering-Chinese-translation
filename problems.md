# 数学建模作业
## A
* 该题目要求设计具有普遍性的方法，不提供数据，但提供样例方便大家理解和进行简单测试

第二次世界大战时期   
（1）英国皇家空军从沦陷国征募了大量外籍飞行员。由皇家空军派出的每一架飞机都需要配备在航行技能和语言上能互相配合的2 名飞行员，其中1 名是英国飞行员，另1名是外籍飞行员。在众多的飞行员中，每一名外籍飞行员都可以与其他若干名英国飞行员很好地配合。如何选择配对飞行的飞行员才能使一次派出最多的飞机。对于给定的外籍飞行员与英国飞行员的配合情况，试设计一个算法找出最佳飞行员配对方案，使皇家空军一次能派出最多的飞机。    
> 样例（为方便展示，数字表示外籍飞行员编号，字母表示英国飞行员编号）  
> 1 b   
> 1 c   
> 2 a   
> 2 d   
> 2 e   
> 3 b   
> 3 c   
> 4 b   
> 4 c   
> 5 e   
> 答案（配对方案）：    
> 1 b   
> 2 d   
> 3 c   
> 5 e
  
（2）战争结束后，大家在一起聚餐。假设有来自n 个不同单位的代表参加聚餐。每个单位的代表数分别为 ri,i=1,2,...,n 。餐厅共有m张餐桌，每张餐桌可容纳ci(i=1,2, ,m) 个代表就餐。 为了使代表们充分交流，希望从同一个单位来的代表不在同一个餐桌就餐。试设计一个算法， 给出满足要求的代表就餐方案。
> 样例     
> 每个单位的代表数：4 5 3 5     
> 每个餐桌容纳人数：3 5 2 6 4   
> 方案（每一表示各单位代表的就餐餐桌）：    
> 1 2 4 5   
> 1 2 3 4 5
> 2 4 5
> 1 2 3 4 5
## B
* 该题目所需的任何数据均可来源于网络，数据有准确的依据即可

考虑由于预计全球温度上升而导致的北极冰盖的融化对陆地的影响。尤其考虑由于北极冰盖融化对我国的影响，可以侧重于大城市及周边城市群。并且尝试提出应对措施来处理这个问题。
## C
* 该题目所需的任何数据均可来源于网络，数据有准确的依据即可

配送问题是生活中一个十分常见的问题，也是一个亟待优化的问题。某物流企业共有3辆车服务于13个顾客。主要配送生鲜食品，售价平均为60元/件。每辆车运送的容量为200件，车辆平均行驶速率为50km/h，车辆每次运送产生的其余消耗为300元/次。此外可以考虑你能够想到的任何成本。  
（1）根据客户位置选一个地点作为配送中心，并说明为什么。 
（2）考虑到各种因素，给车辆规划配送路线。   
（3）如果有n辆车，m个客户，选取x个配送点，问题怎么解决？换言之，试找到具有普遍性的方法。
> 附件：13个顾客的位置、需求量以及希望的配送时间（时间窗，以分钟计，且以早上八点为零时刻）和服务时间见下表：    

| 顾客编号 | 需求量 | 服务时间 | 时间窗上界 | 时间窗下界 | 坐标 |
|-|-|-|-|-|-|
|1|60|4.0|137|169|3.90, 9.09|
|2|50|3.3|124|154|15.10, 17.90|
|3|61|4.1|297|327|0.33, 11.47|
|4|35|2.3|172|202|12.28, 0.34|
|5|14|0.9|55|85|2.33, 15.85|
|6|27|1.8|148|178|11.92, 13.10|
|7|23|1.5|184|214|10.48, 10.76|
|8|36|2.4|148|178|10.00, 19.27|
|9|49|3.3|144|174|13.60, 7.89|
|10|42|2.8|247|277|19.14, 8.53|
|11|32|2.1|24|54|11.74, 8.43|
|12|17|1.1|211|241|11.59, 2.67|
|13|54|3.6|69|99|18.02,10.56|