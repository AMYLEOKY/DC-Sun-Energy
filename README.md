# DC-数据比赛项目
# 有关太阳能辐射强度预测；
# 官方地址：https://challenge.datacastle.cn/v3/cmptDetail.html?id=262
# 附件文件：
- train_label.csv：训练集的标签，以日期为单位，最终标签属性为电场实际太阳辐射指数；
- train_feature.csv：训练集数据，记录的是每个日期，每个时刻监控到的辐照度、风速、风向、温度、湿度、气压数据，为训练特征用；
- test_feature.csv：测试集数据，记录的是每个日期，每个时刻监控到的辐照度、风速、风向、温度、湿度、气压数据，需要经过训练集学习后预测对应日期的电场实际太阳辐射指数；

###### 2018当时做出的效果，使用随机森林，Baseline达到0.1608，差不多排名16左右；
######
当时XGBOOST了解不太深，也不会神网；
况且此数据集相对较少，神网和XGB可能也不太会发挥其自身的优势；
