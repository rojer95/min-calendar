# wxc-calendar

> 日历组件 - 小程序组件

## Install

``` bash
$ min install wxc-calendar
```


## API

### Calendar

| 名称                  | 描述                         | 默认值                         |
|----------------------|------------------------------|------------------------------|
|`enterDirection`      | 入场方向 <br>vertical: 垂直 <br>horizontal: 水平         | vertical |
|`locale`              | 语言本地化，<br>请加载moment的语言包         | zh-cn |
|`title`               | 标题         | 日期选择 |
|`type`                | 选择类型 <br>one: 单日 <br>range: 日期区间         | range |
|`defaultDate`         | 日历表开始渲染的日期<br>类型： (`Date` or `String`)        | new Date() |
|`dateExtra`           | 日期扩展数据，<br>类型为object<br>其中<br>key 为YYYY-MM-DD<br>value项含：<br>- rtext：底部数据<br>- disable：禁止<br>- replace：替换文本<br>- tag：角标内容          | {} |
|`infiniteOpt`         | 无限滚动，<br>true会忽略<br>`initalMonths`参数        | false |
|`initalMonths`        | 初始化显示月个数，<br>显示月份很多建议使用`infiniteOpt`        | 6 |
|`maxDate`             | 最大可选日期        | null |
|`minDate`             | 最小可选日期        | null |
|`rowSize`             | 行大小 `normal` or `xl`        | normal |
|`defaultValue`        | 默认值,数组        | [] |
|`color`               | 主色调        | #068EEF |
|`fontColor`           | 文本色调        | #FFFFFF |


### Calendar【methods】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`show`         | 【说明】显示 `Calendar` <br>【params】void<br>【return】void        |
|`hide`			| 【说明】隐藏 `Calendar` <br>【params】void<br>【return】void		|


## ChangeLog

#### v1.0.0（2018-3-29）

- 初始版本
