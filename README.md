# easy-tabs

简单易用**uniapp**的选项卡组件

## 组件参数说明

参数|说明|类型|默认值|必传
:-:|:--:|:-:|:-:|---
list|tab的列表数据|array|[]|是
current|当前选中的tabIndex，支持.sync修饰符|number|0|否
label|展示的字段名|string|label|否
activeColor|选中状态颜色|string|#62C085|否
inactiveColor|未选中状态颜色|string|#666666|否
duration|滚动动画时间|number|0.5s|否
barHeight|tabBar的高度|number|6rpx|否
barWidth| tabBar的宽 设置为auto的时候，会根据tab的宽度自动变化 |number｜string|50rpx|否
flexBetween|                   是否开启均匀分布                   |boolean|false|否
itemStyle|                  tabItem的内联样式                   |Object|{}|否

#### 触发事件事件

| 事件名 |      说明       |     传参     |
| :----: | :-------------: | :----------: |
| change | tab切换事件监听 | {index, tab} |
