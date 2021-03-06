# 图表的应用

- [特点介绍](#特点介绍)

  - [指标图](#指标图)
  - [柱状图](#柱状图)
  - [折线图](#折线图)
  - [饼图](#饼图)
  - [条形图](#条形图)

- [指标说明](#指标说明)

## <span id='特点介绍'>特点介绍</span>

### <span id='指标图'>指标图</span>

指标图是数据最直观的体现，常用来对某个数据的监测，根据指标的值衡量是否符合预定要求。

- 单指标。可用来计数或求总和

![单指标](./images/metric-0-1.png)

- 单维度单指标。

![单维度单指标](./images/metric-1-1.png)

### <span id='柱状图'>柱状图</span>

用来显示一段时间内数据的变化或者各组数据之间的比较关系。通常横轴为分类项，纵轴为数值项。

![柱状图](./images/chart-bar.png)

### <span id='折线图'>折线图</span>

将同一系列的数据在图中表示成点并用直线连接起来，适用于显示某段时间内数据的变化及其变化趋势。

![折线图](./images/chart-line.png)

### <span id='饼图'>饼图</span>

只适用于单个数据系列间各数据的比较，显示数据系列中每一项占该系列数值总和的比例关系，比例总和只能是 100%。

![饼图](./images/chart-pie.png)

### <span id='条形图'>条形图</span>

类似于柱形图，强调各个数据项之间的差别情况。纵轴为分类项，横轴为数值项，这样可以突出数值的比较。

![条形图](./images/chart-column.png)

## <span id='指标说明'>指标说明</span>

各类图表的说明如下:

| 图表类型 | 支持维度/指标                                |
| -------- | -------------------------------------------- |
| 指标图   | 0 个维度，1 个指标；1 个维度，1 个指标       |
| 柱形图   | 1 个维度，1 个或多个指标；2 个维度，1 个指标 |
| 折线图   | 1 个维度，1 个或多个指标；2 个维度，1 个指标 |
| 饼图     | 1 个维度，1 个指标                           |
| 条形图   | 1 个维度，1 个或多个指标；2 个维度，1 个指标 |
