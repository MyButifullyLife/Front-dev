# Front-dev


**## 本DEMO 运用手淘 flxible.JS ##**
github地址

    https://github.com/amfe/lib-flexible    

运用 flexible.js 后会帮你生成 移动端meta 缩放比例之类 ，不用自己手动创建


## common.less ##

封装了 文字根据dpr自适应和
根据750设计图 转rem方案


#  本案例适用于  750设计图 #

可以完全按照设计图的 具体px，

例如 文字为  28px ，调用common.less 的方法  .fs(28)即可

例如 图片距离顶部为 55px ，调用common.less 方法， .setMarginTop(55)  就会生成  margin-top：xx(转换后)rem  适应不同尺寸屏幕

#  flexible.js  文字出现放大缩小问题解决方案#

1. 添加 display:inline-block;
2. position:absolute, 或者 position:relative
3. 设置max-height：9999999px

