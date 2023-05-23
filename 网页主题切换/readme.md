### 网页主题切换

不知从什么时候起，各种设备都出现了暗黑模式和白天模式，有人喜欢暗黑颜色，有人喜欢浅色，切换主题颜色在网站和各种应用上也流行起来

### 切换原理

> 创建自定义css变量
>
> 改变自定义css变量
>
> 媒体查询当前设备模式是黑色还是浅色
>
>  *JavaScript* 读取 *css* 变量，写入 *css* 变量

### 主题媒体查询

```css
/* 媒体查询浏览器白色背景模式 */
@media screen and (prefers-color-scheme: light) {

}
        
/* 媒体查询浏览器深色背景模式 */
@media screen and (prefers-color-scheme: dark) {

}
```

