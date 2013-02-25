# tiptext

---

带各类图标的提示文案，可带有提示箭头。

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/tiptext.css">

<style>
.ui-tiptext-container {
    margin-top: 8px;
}
</style>

## ui-tiptext 文本

````html
<p class="ui-tiptext ui-tiptext-message">
    <i class="ui-tiptext-icon iconfont" title="提示">&#x00ED;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-error">
    <i class="ui-tiptext-icon iconfont" title="出错">&#x006B;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-warning">
    <i class="ui-tiptext-icon iconfont" title="警告">&#x00EC;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-success">
    <i class="ui-tiptext-icon iconfont" title="成功">&#x00EF;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-question">
    <i class="ui-tiptext-icon iconfont" title="疑问">&#x00F1;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-stop">
    <i class="ui-tiptext-icon iconfont" title="阻止">&#x00EE;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-wait">
    <i class="ui-tiptext-icon iconfont" title="等待">&#x00F3;</i>
    此服务支付宝不收取任何费用。
</p>
````

## ui-tip-container 区块

````html
<div class="ui-tiptext-container ui-tiptext-container-message">
    <p class="ui-tiptext ui-tiptext-message">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x00ED;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>

<div class="ui-tiptext-container ui-tiptext-container-error">
    <p class="ui-tiptext ui-tiptext-error">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x006B;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>

<div class="ui-tiptext-container ui-tiptext-container-warning">
    <p class="ui-tiptext ui-tiptext-warning">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x00EC;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>

<div class="ui-tiptext-container ui-tiptext-container-success">
    <p class="ui-tiptext ui-tiptext-success">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x00EF;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>

<div class="ui-tiptext-container ui-tiptext-container-question">
    <p class="ui-tiptext ui-tiptext-question">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x00F1;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>

<div class="ui-tiptext-container ui-tiptext-container-stop">
    <p class="ui-tiptext ui-tiptext-stop">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x00EE;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>

<div class="ui-tiptext-container ui-tiptext-container-wait">
    <p class="ui-tiptext ui-tiptext-wait">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x00F3;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
````


## ui-tip-container 带箭头

````html
<div class="ui-tiptext-container ui-tiptext-container-message">
    <div class="ui-tiptext-arrow ui-tiptext-arrowup">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ui-tiptext ui-tiptext-message">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x00ED;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
````

````html
<div class="ui-tiptext-container ui-tiptext-container-message">
    <div class="ui-tiptext-arrow ui-tiptext-arrowdown">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ui-tiptext ui-tiptext-message">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x00ED;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
````

````html
<div class="ui-tiptext-container ui-tiptext-container-message">
    <div class="ui-tiptext-arrow ui-tiptext-arrowleft">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ui-tiptext ui-tiptext-message">
        <i class="ui-tiptext-icon iconfont" title="提示">&#x00ED;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
````

