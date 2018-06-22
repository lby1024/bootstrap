## 头部导航

### 第一层(最外层)

```
<div class="navbar navbar-inverse navbar-static-top">

</div>
```
###### .navbar-inverse : 表示黑色
###### .navbar-default : 表示默认颜色, 灰白色
###### .navbar-static-top : 去掉圆角__border-radio=0

### 第二层(可有可无)
> 如果不设置 , 内容会充满整个屏幕

> 如果设置, 内容将会有一个最大宽度

```
<div class="container">
    非折叠区
    折叠区
</div>
```
### 第三层
##### @ 3.1 : 非折叠区
```
<div class="navbar-header">
    logo
    折叠按钮
</div>
```
##### @ 3.2 : 折叠区

```
<div class="collapse navbar-collapse" id="mymenu">
    nav>>> 首页 , 推荐 , 最新 , 热门
    搜索
    个人中心
</div>
```
### 第四层
##### @ 4.1 : 非折叠区域
###### logo

```
<a href="" class="navbar-brand"><img src="./img/logo.png" alt=""></a>
```
###### 折叠按钮

```
<i class="navbar-toggle" data-toggle="collapse" data-target="#mymenu"></i>
```
- data-target="#mymenu"---> 绑定折叠区的 @3.2 id="mymenu"

##### @ 4.2 : 折叠区

###### nav >>> 首页, 国内, 国外, 热门, 亚洲, 欧美

```
<ul class="nav navbar-nav">
   <li><a href="#">首页</a></li> 
   <li><a href="#">推荐商品</a></li> 
   <li><a href="#">手机生鲜</a></li> 
   <li><a href="#">抽奖</a></li> 
</ul>
```
###### 搜索

```
<form class="navbar-form navbar-right">
    <div class="form-group">
        <div class="input-group">
            <input type="text" name="" class="form-control">
            <span class="input-group-btn">
                <button class="btn btn-default"><span class="glyphicon glyphicon-search"></span></button>	
            </span>
        </div>
    </div>
</form>
```
- .navbar-right : 向右靠拢



