# 原生js滚动条移动Scrollbarmovement

效果如下：

![](images/img.gif)

demo code:
```
<!DOCTYPE html>
<head>
    <meta charset="utf-8" />
    <title></title>
    <style>
        .input1{position: absolute;
            top: 100px;
        width:200px;
        height:100px;}
    </style>
</head>
<body>
    <input id="input1" class="input1" type="button" value="按钮" onclick="asd()"/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
    <br/>aaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa <br/>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>
    <h1>aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</h1>
    <p>111111111111111111111111111111111111</p>

</body>
</html>
<script>
    var oldTOP ;
    window.onload = function(){
        if(document.defaultView){
            oldTOP = document.defaultView.getComputedStyle(input1,null).top;
        }
        if(input1.currentStyle){
            oldTOP = input1.currentStyle.top;
        }
    };
    window.onscroll = function (){
        input1.value = document.documentElement.scrollTop+document.body.scrollTop+parseInt(oldTOP);
        var inputTOP = document.documentElement.scrollTop+document.body.scrollTop+parseInt(oldTOP);
        input1.style.top = inputTOP+"px";
    }
</script>
```

