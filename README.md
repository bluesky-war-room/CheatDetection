# CheatDetection
This code is prepared for CV contest held by deepshare.net

## Contest introduction
###赛题-AI 视频分析大赛
（除填写成绩外，请勿随意改动表格，凡参赛队员均需要添加客服）
将开放采集自摄像机的原始视频数据集，从提供的视频中找出并判断所有的预先定义的n种人体行为。

###评价标准
Criteria：Maximum [AUC](https://blog.csdn.net/cherrylvlei/article/details/52958720)
Constraints：
阈值t从0.5到0.95，步长0.05，negative定义为没有作弊，即正常答题以及休息时间，
positive定义为有作弊行为时间段，TP定义为预测positive与真实postive的tIOU>t且作弊类别相同
[code of performance evaluation](https://github.com/activitynet/ActivityNet/tree/master/Evaluation)
###提交地址
[石墨文档](https://shimo.im/sheets/m2Rgtg64tQ4geBsr/MODOC)


## Requirements
data resource and packages are listed as following

### data resource
[Activity data for trainning](https://pan.baidu.com/s/1dnpqtyRo8EKPpXRrBDQeVQ)

### packages
tensorflow GPU
pandas
pandas_profiling


## Installation




## How it works



## Reference
[Two Stream R-C3D用于时序区域行为检测](https://blog.csdn.net/weixin_44402973/article/details/95654807)






