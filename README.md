## BW情绪指标投资者情绪指标基于中国市场数据的实现
计算了以下六个市场情绪指标
1. 股票融资占比(PDND)是指股权融资占股权融资和债务融资总和的比例。Baker和Wurgler(2000)发现股票融资的高占比预示着较低的市场回报。
2. 换手率(TRate)是指股票转手买卖的频率。Baker和Stein(2004)认为一定时间内的成交量可以代表流动性，而流动性可以作为情绪指数。在市场中，非理性投资者只有在乐观的时候才会参与进来，从而增加流动性。因此，高流动性是乐观情绪与价格高估的征兆。
3. IPO数量(IPON)补充下
4. IPO首日回报(IPOR)是指首次公开募股的回报。首次公开募股的高首日汇报通常被认为是投资者热情的标志。
5. 股利溢价(SRate)是指支付者和非支付者的平均市净率的对数差。由于支付者通常是规模更大、利润更高、增长机会较少的公司，股利溢价可能代表对这系列特征组合的相对需求。
6. 基金折价率(FDP)是指封闭式股票基金净值和它们市场价格之间的平均差额，Lee等人(1991)认为情绪是封闭式基金折价背后的原因。

参照文献[2]的做法，取前五个主成分平均值，方差解释度达到83.8%，通过相关性分析，最终选出6个因子得出SENTIMENT指标，与原来主成分的相关度达到95%。

## 参考文献
[1]Baker M , Wurgler J . Investor Sentiment and the Cross-Section of Stock Returns[J]. NBER Working Papers, 2004.

[2]易志高,茅宁.中国股市投资者情绪测量研究:CICSI的构建[J].金融研究,2009(11):174-184.