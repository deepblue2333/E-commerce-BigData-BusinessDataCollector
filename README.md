# E-commerce-BigData-BusinessDataCollector
业务系统数据采集模块

采集架构为：使用DataX进行全量同步，使用Maxwell进行增量同步

## 全量同步
全量数据由DataX从MySQL业务数据库直接同步到HDFS中。
![alt text](image.png)

