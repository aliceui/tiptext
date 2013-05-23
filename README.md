# tiptext

---

带各类图标的提示文案，可带有提示箭头。

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/tiptext.css">

<style>
.ui-tiptext-container,
.ui-tiptext {
    margin-top: 5px;
}
.ui-tiptext-container .ui-tiptext {
    margin-top: 0;
}
</style>

### ui-tiptext 文本

````html
<p class="ui-tiptext ui-tiptext-message">
    <i class="ui-tiptext-icon iconfont" title="提示">&#xF046;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-error">
    <i class="ui-tiptext-icon iconfont" title="出错">&#xF045;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-warning">
    <i class="ui-tiptext-icon iconfont" title="警告">&#xF047;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-success">
    <i class="ui-tiptext-icon iconfont" title="成功">&#xF049;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-question">
    <i class="ui-tiptext-icon iconfont" title="疑问">&#xF04A;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-stop">
    <i class="ui-tiptext-icon iconfont" title="阻止">&#xF048;</i>
    此服务支付宝不收取任何费用。
</p>

<p class="ui-tiptext ui-tiptext-wait">
    <i class="ui-tiptext-icon iconfont" title="等待">&#xF04B;</i>
    此服务支付宝不收取任何费用。
</p>
````

### ui-tip-container 区块

````html
<div class="ui-tiptext-container ui-tiptext-container-message">
    <p class="ui-tiptext ui-tiptext-message">
        <i class="ui-tiptext-icon iconfont" title="提示">&#xF046;</i>
        此服务支付宝不收取任何费用。
    </p>
    <p class="ui-tiptext ui-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <p class="ui-tiptext ui-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <div class="ui-tiptext-close iconfont">&#xF028;</div>    
</div>
<br>
<div class="ui-tiptext-container ui-tiptext-container-error">
    <p class="ui-tiptext ui-tiptext-error">
        <i class="ui-tiptext-icon iconfont" title="出错">&#xF045;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
<br>
<div class="ui-tiptext-container ui-tiptext-container-warning">
    <p class="ui-tiptext ui-tiptext-warning">
        <i class="ui-tiptext-icon iconfont" title="警告">&#xF047;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
<br>
<div class="ui-tiptext-container ui-tiptext-container-success">
    <p class="ui-tiptext ui-tiptext-success">
        <i class="ui-tiptext-icon iconfont" title="成功">&#xF049;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
<br>
<div class="ui-tiptext-container ui-tiptext-container-question">
    <p class="ui-tiptext ui-tiptext-question">
        <i class="ui-tiptext-icon iconfont" title="疑问">&#xF04A;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
<br>
<div class="ui-tiptext-container ui-tiptext-container-stop">
    <p class="ui-tiptext ui-tiptext-stop">
        <i class="ui-tiptext-icon iconfont" title="阻止">&#xF048;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
<br>
<div class="ui-tiptext-container ui-tiptext-container-wait">
    <p class="ui-tiptext ui-tiptext-wait">
        <i class="ui-tiptext-icon iconfont" title="等待">&#xF04B;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
````


### 带上箭头

````html
<div class="ui-tiptext-container ui-tiptext-container-message">
    <div class="ui-tiptext-arrow ui-tiptext-arrowup">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ui-tiptext ui-tiptext-message">
        <i class="ui-tiptext-icon iconfont" title="提示">&#xF046;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
````

### 带下箭头

````html
<div class="ui-tiptext-container ui-tiptext-container-message">
    <div class="ui-tiptext-arrow ui-tiptext-arrowdown">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ui-tiptext ui-tiptext-message">
        <i class="ui-tiptext-icon iconfont" title="提示">&#xF046;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
````

### 带左箭头

````html
<div class="ui-tiptext-container ui-tiptext-container-message">
    <div class="ui-tiptext-arrow ui-tiptext-arrowleft">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ui-tiptext ui-tiptext-message">
        <i class="ui-tiptext-icon iconfont" title="提示">&#xF046;</i>
        此服务支付宝不收取任何费用。
    </p>
</div>
````

