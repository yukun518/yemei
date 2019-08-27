# yemei
野莓资料
获取bitmex的各种合约对应的日K线，并且计算定期合约与永续XBTUSD合约的high/low之间的比例（(定high-永high）/永high)
获取bitmex的1小时K线数据，考虑到时区问题，显示时间比抓取时间多7小时。
利用bitmex的1小时K线合成对应的8小时K线（跟资金费率的时间段一样）
获取bitmex的资金费率历史记录
进行对比输出为pyecharts
