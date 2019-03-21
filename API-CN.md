#### btcwinex市场行情 

获取所有交易对行情数据

Request:

 GET
 ``` 
https://api.btcwinex.com/api/v1/allticker
```
Response:    
```
{
    "date":"1410431279",//返回数据时服务器时间 
    "ticker":[
        {
            "symbol":"ltc_usdt",//交易对（交易对1简称_交易对2简称）
            "buy":"33.15",//买一价
            "high":"34.15",//最高价 (最近的24小时)
            "last":"33.15",//最新成交价
            "low":"32.05",//最低价 (最近的24小时)
            "sell":"33.16",//卖一价 
            "change":"4.5",//涨跌幅(最近的24小时) 
            "vol":"10532696.39199642"//成交量(最近的24小时)
        },
        {
            "symbol":"btc_usdt",
            "buy":"33.15",
            "high":"34.15",
            "last":"33.15",
            "low":"32.05",
            "sell":"33.16",
            "change":"-4.5",
            "vol":"10532696.39199642"
        }
        ,
       // more data here
    ]
}
```
