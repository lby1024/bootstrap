## 栅格系统

##### html

```
<body>
    <div class="container">
        <div class="row"></div>
    </div>
</body>
```
##### css

```
.box{
    max-width: 160px;
    max-height: 100px;
    min-width: 100px;
    min-height: 100px;
    background-color: skyblue;
    margin-bottom: 12px;
    margin-right: auto;
    margin-left: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 36px;
}
```

##### JS
```
<script>
    
    for (let i=0; i<33; i++) {
        let box = 
        `<div class="col-lg-2 col-md-3 col-sm-4 col-xs-6">
                <div class="box">${i+1}</div>
        </div>`

        $('.row').append(box)
    }
</script>
```
###### 大屏 : 一行6个 (col-lg-2)
###### 中屏 : 一行4个 (col-md-3)
###### 小屏 : 一行3个 (col-sm-4)
###### 超小屏 : 一行2个 (col-xs-6)
