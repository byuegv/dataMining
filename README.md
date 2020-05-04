# 互评作业1: 数据探索性分析与数据预处理
## 数据预处理方法
1. 数据摘要

    标称属性，给出每个可能取值的频数
    数值属性，给出5数概括及缺失值的个数
2. 数据可视化

    使用直方图、盒图等检查数据分布及离群点

## 数据缺失值处理
观察数据集中缺失数据，分析其缺失的原因。分别使用下列四种策略对缺失值进行处理:
1. 将缺失部分剔除
2. 用最高频率值来填补缺失值
3. 通过属性的相关关系来填补缺失值
4. 通过数据对象之间的相似性来填补缺失值

注意：在处理后，要可视化地对比新旧数据集。

# 数据集
## 1 Wine Reviews[https://www.kaggle.com/zynicide/wine-reviews]
130k wine reviews with variety, location, winery, price, and description
### description
#### Context
After watching Somm (a documentary on master sommeliers) I wondered how I could create a predictive model to identify wines through blind tasting like a master sommelier would. The first step in this journey was gathering some data to train a model. I plan to use deep learning to predict the wine variety using words in the description/review. The model still won't be able to taste the wine, but theoretically it could identify the wine based on a description that a sommelier could give. If anyone has any ideas on how to accomplish this, please post them!

#### Content
This dataset contains three files:

winemag-data-130k-v2.csv contains 10 columns and 130k rows of wine reviews.

winemag-data_first150k.csv contains 10 columns and 150k rows of wine reviews.

winemag-data-130k-v2.json contains 6919 nodes of wine reviews.

## 2 Consumer & Visitor Insights For Neighborhoods[https://www.kaggle.com/safegraph/visit-patterns-by-census-block-group]
Consumer Insights & Visitation Data At The Census Block Group Level
### description
#### SafeGraph
SafeGraph is democratizing access to data about places in the world. At SafeGraph's online data bar, you can download foot traffic data for points of interest in the U.S.

#### About This Data
A Census Block Group (CBG) is the most granular level the US Census Bureau reports data on.

SafeGraph derived the popularity of a CBG or distances traveled to a CBG by analyzing a large panel of GPS movement data.

We also combined this GPS data with our dataset of 5 million building footprints for Points-of-Interest in the U.S. (SafeGraph Places) to determine visits to places like stores or restaurants. We used these visit counts to derive consumer insights such as top brands (ex. McDonald's) visited in a CBG.

#### Questions Our Data Can Answer
What are the most popular brands in a neighborhood? Are there regional preferences for some brands over others?
How do people travel between neighborhoods? How does distance traveled compare for suburban and urban communities?
What times do people visit certain census block groups (ex. Manhattan during the day vs. night)?
Which neighborhoods are the most mobile? Which neighborhoods receive the most outside visitors?
You can also join this dataset with Census data to get demographic insights alongside these visit patterns.
