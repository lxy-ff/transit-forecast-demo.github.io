# transit-forecast-demo
项目概要介绍
1.前言：
随着国内各个城市轨道交通的持续高速发展，轨交乘客数量不断增长，在缓解城市整体交通拥堵的同时，轨道交通本身也面临着较大的客流管理压力。在数据层面主要普遍存在几个问题：①客流监测能力不足②缺乏客流精准管控方法③缺乏对突发客流的提前评估和预测。因此，A09计划团队以八维通提供的乘客行程数据与站点信息为基础，完成基于地铁出行行程大数据的分析建模和算法研究，实现对地铁的线路级别与站点级别的客流进行分析和预测，以达到设施和设备的全息感知、实现数据信息与业务管理的有机融合，减少地铁站台出现大客流现象，确保地铁客站的有序、安全运行。

2.创意描述：
⑴平台能够实现多源数据融合、客流预警预测、车站客流风险评估、灵活查询等功能和服务。
⑵通过大数据处理和AI建模，能够对站点客流、线路客流、线网客流、断面客流等进行精准预测。
⑶微观上解析车站各瓶颈点客流压力的具体情况，宏观上呈现全市轨道交通的客流变化趋势，实现纵深比较。
⑷数据分析结果实现图表的动态呈现，更加清晰人性化。

3.功能简介：
 系统是使用Pycharm开发的利用Layui框架，采用B/S架构、Ajax、Echarts等技术搭建的web平台。前端通过动态页面向用户进行数据图表展示，实现与用户的交互，后端使用数据库、Hadoop集群对静态、动态数据进行挖掘处理和流程化管理。

4.特色综述：
⑴以热力图的形式实时反应各个地铁站的拥挤情况。根据热力图可精准看到车站的布局结果和拥挤的赌点，从而采取措施进行客流疏导。
⑵通过OD客流可视化，基于OD客流的复杂性、多样性特点，从宏观与微观两个层面掌握网络 OD的时空分布。
⑶通过断面客流分析展现站点在不同时段(早晚高 峰)、不同时期(工作日、双休日与节假日)的差异性，又体现了其在发生位置与发生方向 (上下行)的差异。用户可根据断面绝对量与断面满载率两个指标来实现不同目的的客流分析。
⑷通过构建实时的动态信息服务体系，深度挖掘运维管理所需的相关数据，设计出了适合该城市轨道交通客流分析与预测的创新模型。
⑸本平台运用黑色背景和色彩饱和度高的图表样式，合理划分模块，友好清晰，操作简单。
 
5.开发工具与技术：
开发工具：Pycharm、Navicat 15 for MySQL、Visual Studio 2019
技术：系统架构：Ajax
      后端语言：Python
      前端架构：B/S架构、Layui框架
数据分析技术：
对原始数据进行数据清洗,并且转换成JSON格式进而实现数据的可视化。根据数据特性，从多层次、多角度分析设计最终以Web页面形式进行效果展示。
 
客流预测的方法及模型：
    首先利用MySQL和Python对多源数据进行预处理和融合，其次使用K-means、混合高斯模型和相关统计方法，用来将OD车站间的客流分配到有效路径上，计算每位乘客选择某条有效路径的概率，并对城市轨道交通短时OD客流的影响因素进行研究。在此基础上，构建基于多模型集成的城市轨道交通客流预测模型，并对预测结果进行详细对比分析。
将各个模型预测的结果相结合在实践中，集成结果可能会提高鲁棒性和预测准确性。

6.应用对象：
   该城市轨道交通调度部门、运营管理部门

7.应用环境：
服务器操作系统	Windows 2010 Server
数据库管理系统	MySQL
Web服务器	Apache HTTP Server
客户端操作系统	Windows 2010
客户端Web浏览器	全部浏览器（IE6/7，Safari除外）

8.结语：
A09计划团队按照企业的要求基本实现了所有功能并在此基础上有所创新。对数据的实时计算和客流预测是该平台的重要部分，本次设置的影响因子仍具有较大的不稳定性，需要进一步探索实际情况中影响客流的各项因素和因子参数。


