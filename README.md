# easy-tabs

简单易用**uniapp**的选项卡组件,组件的唯一特色就是可以随意修改组件tab的样式，其他tab组件都没有这一点，不过在修改过程中需要注意`tabBar`的宽度获取的问题，外边框是获取不到的

## 组件参数说明

参数|说明|类型|默认值|必传
:-:|:--:|:-:|:-:|---
list|tab的列表数据|array|[]|是
v-model|同步选中的tab-index|number|0|是
label|展示的字段名|string|label|否
activeColor|选中状态颜色|string|#62C085|否
inactiveColor|未选中状态颜色|string|#666666|否
duration|滚动动画时间|number|0.5s|否
barHeight|tabBar的高度|number|6rpx|否
barWidth| tabBar的宽 设置为auto的时候，会根据tab的宽度自动变化 |number｜string|50rpx|否
barRadius| 设置tabbar的圆角值 |String|0rpx|否
barColor| 设置tabbar的颜色，不设置则跟文本颜色同步 |String|Null|否
flexBetween|                   是否开启均匀分布                   |boolean|false|否
itemStyle|                  tabItem的内联样式                   |Object|{}|否
customClass|                  最外层自定义class                   |string|null|否
fixed| 是否开启固定定位 |boolean|false|否
height| tabItem的高度 |string|60rpx|否
padding| tabItem的内边距 |string|0 30rpx|否



#### 触发事件事件

触发事件自**v1.1.1**起使用以下用法，旧版本传出参数为` {index,tab}`

| 事件名 |      说明       | 传参 |
| :----: | :-------------: | :--: |
| change | tab切换事件监听 | tab  |

