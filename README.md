# pc-slider
 
 - 使用`jquery`实现的瀑布流
```html
    <div class="list"></div>
```
```javascript
    //调用方法
    window.onload = function () {
        model.newClass({
            box: $(".list"),
            list: $(".list-c"),
            item: 13,
            length: 4,
            fn: function () {
                $(".list-c").fadeIn(800);
            }
        });
    }
```