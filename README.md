# China-CPI-Weight-Guesstimate
Based on YoY data from Bloomberg, guesstimate the weights of each major category of prices using optimiser. 
The CPI weights will be updated every 5 years.
For Jan 2020 - Dec 2025, the CPI weights are based on price indices from year 2020.
Similarly, for Jan 2016 - Dec 2020, the CPI weights are based on price indices from year 2015.
For next update in Jan 2026, the weights will be based on prices in year 2025.

###
Future updates might add on MoM and YTD data to increase bounds and constraints for optimisation



### From Doubao AI:
2021年的CPI基期轮换启动于2021年1月，基期年设定为2020年全年。以下是具体说明：
一、基期轮换的时间安排
启动时间：2021年1月
国家统计局自2021年1月起实施新一轮CPI基期轮换，调整“商品篮子”分类及权重，以反映居民消费结构变化。
基期年定义：2020年全年
新基期以2020年居民消费支出结构为基准，固定篮子商品和服务的数量，用于计算后续年份的CPI。
二、基期轮换的调整内容
商品分类调整
大类保持8类（食品烟酒、衣着、居住等），基本分类从262个增至268个。
新增外卖、新能源小汽车、网约车等新兴消费项目，删除或合并部分传统项目。
权重调整方向
下调：食品烟酒（-1.2%）、衣着（-1.7%）、教育文化娱乐（-0.5%）、其他用品及服务（-0.4%）。
上调：居住（+2.1%）、交通通信（+0.9%）、医疗保健（+0.9%）。
趋势：食品权重持续下降（反映恩格尔系数降低），服务类权重上升（契合消费升级）。

# Reference:
https://www.bloomberg.com/professional/insights/trading/china-insight-cpi-basket-decoded-food-dominates-services-key/
