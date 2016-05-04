使用方式：
```
    <link rel="stylesheet" href="star-rate.css">
    <script src="jquery.js"></script>
    <script src="star-rate.js"></script>

    $('#div').startRate({
          size: 5,//总星数
          onEvent: true,//是否可点击
          activeSize: 5,//激活的星星数目
          starSize: 16,//设置星星的大小，单位px，和字体单位一样
          activeColor: '#F8B551',//激活的颜色
          normalColor: '#ccc'//正常态颜色
    });
```

参数可省略，最好一次只选中一个元素。
