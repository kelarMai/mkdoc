# Welcome to qhdata.API

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

    what is a change?

## Project Doc
**这是一个测试文档**，如果单纯的使用 md 文件是否能写好文档？\  
[link1](./class/trading_date.md#get_trading_date)
[link2](./class/TradingDate.md#class TradingDate)

## FutQuoteTableCfg - 期货相关类

`FutQuoteTableCfg(data_type,order_level=1,data_class='ac',column_type='v')`

不同期货表的相关配置信息类

**参数**

|参数|类型|说明|
|:----|:----|:----|
|data_type|str|数据类型， tick,bar,daily|
|order_level|int|k档行情；</br>对于 tick 来说，有 1 5 10，即包含k档行情的数据；</br>对于 bar 来说，是由该 k 档 tick 数据生成的 bar 数据；</br>daily 默认使用 1 档|
|data_class|str|数据分类；ac,mc,msnfc|
|column_type|str|b , v ,m|

```
def get_db_name():
    a = 10
    print(a)
```
