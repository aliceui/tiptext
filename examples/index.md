# 演示文档

---

<link type="text/css" rel="stylesheet" media="screen" href="../src/tiptext.css">

<style>
@font-face {
    font-family: "rei";
    src: url("https://i.test.alipay.net/common/fonts/rei.eot"); /* IE9*/
    src: url("https://i.test.alipay.net/common/fonts/rei.eot?#iefix") format("embedded-opentype"), /* IE6-IE8 */
         url("https://i.test.alipay.net/common/fonts/rei.woff") format("woff"), /* chrome 6+、firefox 3.6+、Safari5.1+、Opera 11+ */
         url("https://i.test.alipay.net/common/fonts/rei.ttf") format("truetype"), /* chrome、firefox、opera、Safari, Android, iOS 4.2+*/
         url("https://i.test.alipay.net/common/fonts/rei.svg#rei") format("svg"); /* iOS 4.1- */
    font-weight: normal;
    font-style: normal;
}
.iconfont {
    font-family: "rei";
    font-size: 12px;
    font-style: normal;
    color: #4d4d4d;
    cursor: default;
    -webkit-font-smoothing: antialiased;
}
</style>

## ui-tiptext

````html
<p class="ui-tiptext ui-tiptext-error">
    <i class="ui-tiptext-icon iconfont" title="出错">&#x006B;</i>此服务支付宝不收取任何费用。
</p>
````

## ui-tip-container

````html
<div class="ui-tiptext-container ui-tiptext-container-error">
    <p class="ui-tiptext ui-tiptext-error">
        <i class="ui-tiptext-icon iconfont" title="出错">&#x006B;</i>此服务支付宝不收取任何费用。
    </p>
</div>
````
## ui-tip-container with arrow

````html
<div class="ui-tiptext-container ui-tiptext-container-error">
    <div class="ui-tiptext-arrow ui-tiptext-arrowup">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ui-tiptext ui-tiptext-error">
        <i class="ui-tiptext-icon iconfont" title="出错">&#x006B;</i>此服务支付宝不收取任何费用。
    </p>
</div>
````

````html
<div class="ui-tiptext-container ui-tiptext-container-error">
    <div class="ui-tiptext-arrow ui-tiptext-arrowdown">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ui-tiptext ui-tiptext-error">
        <i class="ui-tiptext-icon iconfont" title="出错">&#x006B;</i>此服务支付宝不收取任何费用。
    </p>
</div>
````

````html
<div class="ui-tiptext-container ui-tiptext-container-error">
    <div class="ui-tiptext-arrow ui-tiptext-arrowleft">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ui-tiptext ui-tiptext-error">
        <i class="ui-tiptext-icon iconfont" title="出错">&#x006B;</i>此服务支付宝不收取任何费用。
    </p>
</div>
````
