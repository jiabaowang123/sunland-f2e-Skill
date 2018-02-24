**f2e-rem布局**
--

**meta**

`<meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0,  user-scalable=0" name="viewport"/>`

**js**
```
<script>
    (function () {
        document.addEventListener('DOMContentLoaded', function () {
            var html = document.documentElement;
            var windowWidth = html.clientWidth;
            html.style.fontSize = windowWidth / 7.5 + 'px';
            // 等价于html.style.fontSize = windowWidth / 750 * 100 + 'px';  750为设计稿的宽度
        }, false);
    })();
</script>
```

**注意**

1. js代码最好放在head里面
2. 100px = 1rem 可以直接换算



