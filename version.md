## devfeel/mapper

#### Version 0.2
* 新增兼容Json-tag标签
* 识别顺序：私有Tag > json tag > field name
* 当tag为"-"时，将忽略tag定义，使用struct field name
* 2017-11-15 10:00

#### Version 0.1
* 初始版本
* 支持不同结构体相同名称相同类型字段自动赋值
* 支持tag标签，tag关键字为 mapper
* 2017-11-14 21:00