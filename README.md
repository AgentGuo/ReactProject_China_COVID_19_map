# React小项目--中国肺炎疫情地图

### 关于本项目

> 使用React制作中国肺炎疫情地图，最近几天React学习的一个小demo，只有一个页面，如下：

![1](https://github.com/AgentGuo/ReactProject_China_COVID_19_map/tree/master/images/react_china_map.png)

主要有三个功能组件：

1. 地图组件：用于显示中国地图以及相关数据

![2](https://github.com/AgentGuo/ReactProject_China_COVID_19_map/tree/master/images/1.png)

2. 搜索组件：用于搜索相关省份的疫情信息，支持子串搜索

![3](https://github.com/AgentGuo/ReactProject_China_COVID_19_map/tree/master/images/2.png)

3. 表格组件：将疫情数据按照感染人数排序的一个表格信息

![4](https://github.com/AgentGuo/ReactProject_China_COVID_19_map/tree/master/images/3.png)

### 如何使用?

在项目文件夹下运行如下命令即可（需要安装react）

~~~
npm start
~~~

### 没有安装React？

可以参考网上一些教程，或者[点击这里](https://blog.csdn.net/weixin_44338712/article/details/108755086)

### 关于代码的一些说明

* 我这里直接将肺炎数下载下来了（`feiyan.json`），你当然可以选择实时获取，但可能就会非常依赖其他网站的数据，为了防止页面奔溃，所以选择了本地读取
* 代码主要就是三个组件部分的代码，分布在`index.js`以及`searchCom.js`中。
* 中国地图是采用[echarts](https://github.com/AgentGuo/ReactProject_China_COVID_19_map)的图表，但是最近其最近有下架了中国地图的一些服务，所以我这里直接是从网上下载的一个`china.js`图表T_T
* 另外就是，我太菜辣，大佬勿喷T_T