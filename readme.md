# [KDD-CUP 2017](http://tianchi.aliyun.com/competition/information.htm?raceId=231597")

Highway Tollgates Traffic Flow Prediction

Travel Time & Traffic Volume Prediction

### Background
Highway tollgates are well known bottlenecks in traffic networks.  During rush hours, long queues at tollgates can overwhelm traffic management authorities.   Effective preemptive countermeasures are desired to solve this challenge.  Such countermeasures include expediting the toll collection process and streamlining future traffic flow.  The expedition of toll collection could be simply allocating temporary toll collectors to open more lanes.  Future traffic flow could be streamlined by adaptively tweaking traffic signals at upstream intersections.  Preemptive countermeasures will only work when the traffic management authorities receive reliable predictions for future traffic flow.  For example, if heavy traffic in the next hour is predicted, then traffic regulators could immediately deploy additional toll collectors and/or divert traffic at upstream intersections.  
Traffic flow patterns vary due to different stochastic factors, such as weather conditions, holidays, time of the day, etc.  The prediction of future traffic flow and ETA (Estimated Time of Arrival) is a known challenge.  An unprecedented large amount of traffic data from mobile apps such as Waze (in the US) or Amap (in China) can help us take up that challenge.  If the contestants in this proposed KDD CUP could design reliable approaches for future traffic flow and ETA prediction, then the traffic management authorities might be able to capitalize on big data & algorithms for fewer congestions at tollgates.

### Project Task
This project mainly focuses on task2, Traffic Volume Prediction.

### Program Language
Python 2

### Dependancy
* [xgboost](https://github.com/dmlc/xgboost)
* [pandas](http://pandas.pydata.org/)
* [numpy](http://www.numpy.org/)

### Lincence
[MIT](https://opensource.org/licenses/MIT)
