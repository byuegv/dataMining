# 数据挖掘互评作业三：分类与预测
## 数据集-Hotel booking demand
### description
#### Context
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests?

This hotel booking dataset can help you explore those questions!

#### Content
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

All personally identifying information has been removed from the data.

#### Acknowledgements
The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

The data was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020.

## 探索问题
利用Logistic Regression预测客户是否预订酒店。
### 数据挖掘过程
1. 分析数据集
2. 选择适当的特征
3. 将非数值特征转化为数值特征
4. 使用LogisticsRegression进行训练和测试
### 结果
测试集准确率98.8660%

## 作业说明 
### 1. 问题描述
本次作业中，将从下面的3个问题中任选一个进行。

### 2. 可选问题
#### 2.1 Hotel booking demand, 酒店预订需求
数据集：Hotel booking demand

该数据集包含城市酒店和度假酒店的预订信息，包括预订时间、停留时间，成人/儿童/婴儿人数以及可用停车位数量等信息。

数据量：32列共12W数据。

基于这个数据集，可进行以下问题的探索：

基本情况：城市酒店和假日酒店预订需求和入住率比较；  
用户行为：提前预订时间、入住时长、预订间隔、餐食预订情况；  
一年中最佳预订酒店时间；  
利用Logistic预测酒店预订。  
也可以自行发现其他问题，并进行相应的挖掘。  

#### 2.2 Video Game Sales 电子游戏销售分析
数据集：Video Game Sales

该数据集包含游戏名称、类型、发行时间、发布者以及在全球各地的销售额数据。

数据量：11列共1.66W数据。

基于这个数据集，可进行以下问题的探索：

电子游戏市场分析：受欢迎的游戏、类型、发布平台、发行人等；  
预测每年电子游戏销售额。  
可视化应用：如何完整清晰地展示这个销售故事。  
也可以自行发现其他问题，并进行相应的挖掘。  

#### 2.3 US Accidents 美国交通事故分析（2016-2019）
数据集：US Accidents

该数据集覆盖全美49州的全国性交通事故数据集，时间跨度：2016.02-2019。12，包括事故严重程度、事故开始和结束时间，事故地点、天气、温度、湿度等数据。

数据量：49列共300W数据。

基于这个数据集，可进行以下问题的探索：

发生事故最多的州，什么时候容易发生事故；  
影响事故严重程度的因素；  
预测事故发生的地点；  
可视化应用：讲述4年间美国发生事故的总体情况。  
也可以自行发现其他问题，并进行相应的挖掘。  

### 3. 提交的内容
对数据集进行处理的代码
数据挖掘代码
挖掘过程的报告：展示挖掘的过程、结果和你的分析
所选择的问题在README中说明，数据文件不要上传到Github中
乐学平台提交注意事项：
### Tips
仓库地址：记得加上  
报告：附件，word，pdf，html格式都可以
