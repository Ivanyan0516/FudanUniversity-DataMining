# Homework2 火锅团购数据分析

## 数据介绍

`HotPoT.csv`：案例数据提供了某线上团购网站的西安市区内在2017年01月05日这一时间节点的共2688个火锅团购产品的销售数据，数据说明表如下：

![数据介绍](https://jrothschild.oss-cn-shanghai.aliyuncs.com/FDU_Data_Mining/HW2/data_introduction.jpg)

## 分析任务
1. 请完成数据读入与简单清洗；
2. 将团购的季均销量转换为对数，对季均销量、团购上线天数、折扣力度绘制分布直方图，简单陈述你观察到的现象；
3. 将火锅团购商家店名高频词统计出来，并绘制出词云，简单陈述你观察到的现象；提示：在统计火锅团购商家店名高频词时，可以将一些无意义的词组剔除，如“区”、“路”、“火锅”、“小区”、“分店”、“店”等；同时还需要先剔除非中文字符（数字和字母）。
4. 用箱线图表示销量与团购价的关系，及销量与节假日通用的关系；尝试解读这两个箱线图呈现的现象；
5. 用箱线图表示店名中包含的各类词汇与团购销量的关系，并尝试解读箱线图的含义；
6. 建立线性回归模型，探究影响团购销量的主要因素，并对模型结果进行适当解读。