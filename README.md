# 技术文档总结说明

|姓名   |学号  |搭档1 |搭档2|
| ----- | ----- | ----- | -----|
|李婷  |181013062|陈婷  |陈朗|

#### 项目背景

    1、此项目主要面向对象为即将面临实习和就业，对就业和实习方向迷茫的人群。
    2、爬取boss直聘的全国关于大数据区块链、物联网、人工智能、云计算的招聘信息，有全国各省的最低薪资平均水平与岗位数量的地图、岗位描述词的词云、学历要求的饼状图、工作经验的条形图。
    3、从宏观上，为有意愿从事这五个互联网职业的职场小白择业提供可视化的参考。  

#### [协作](https://github.com/cocofantuan/visual_job)
|开发人员   |产品经理 |
| ----- | ----- |
|网页美化、文档描述、网站部署  |数据抓取、网页美化、数据可视化、web框架|

在此项目中，本人主要负责前端的网页设计，包括html框架、css样式以及js动画效果的实现，还有网站的部署。尝试书写推导式但失败了。

[Pythonanywhere入口](ltco.pythonanywhere.com/)
[Github_URL含README文档](https://github.com/cocofantuan/Python)

#### 数据传递描述：
 - 运用条件判断语句：
 - 首先使用if语句配合try语句使用，用户点击复选框，
 - 使用post方法（提交下面的表单）向/visual发起请求

#### HTML档：
- index.html:此html档用于实现复选框、提交按钮,并用bootstrap前端框架美化了页面
- nothing.html:实现动态背景；当用户没有选择复选框或选择大于二时将返回nothing页面，提示用户进行选择后继续搜索
- visual.html:此为非地图可视化页面，当用户选择两个复选框选项后跳转至此，panel实现自适应高度，并且实现了词云。 

#### Python档：

- 调用了faker模块,用于伪造数据
- 调用可视化模块pyecharts，导入了Pie,Bar,Map,Tab，实现了地图可视化及非地图可视化（饼图，柱状图及可拖动布局）

#### Web App动作：
- 此项目使用了复选框，选中两个复选框结果进行对比，点击确定，页面由全国数据的地图跳转到各职业对比的可视化图表及词云。

