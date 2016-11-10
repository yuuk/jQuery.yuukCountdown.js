# jQuery.yuukCountdown.js

jQuery毫秒倒计时插件

预览地址：http://htmlpreview.github.io/?https://github.com/yuuk/jQuery.yuukCountdown.js/blob/master/index.html

# 使用方法
```javascript
$(function(){
    $('#js-countDown').yuukCountDown({
        starttime: '2016/11/10 00:00:00',
        endtime: '2016/12/31 10:59:59',
        notStartCallBack: function(time){
            console.log("未开始！");
        },
        startCallBack: function(time){
            console.log("开始中！");
        },
        endCallBack: function(time){
            console.log("已结束！");
        }
    });
});
```
