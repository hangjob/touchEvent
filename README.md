# touchEvent
基于Jquery扩展在移动端产生的事件，包含，单次触摸事件，两次触摸事件，长按事件，滑屏事件，向上滑动事件，向下滑动事件，向左滑动事件，向右滑动事件

[![B4lry8.png](https://s1.ax1x.com/2020/11/07/B4lry8.png)](https://imgchr.com/i/B4lry8)

### 预览
地址预览
[https://hangjob.github.io/touchEvent/index.html](https://hangjob.github.io/touchEvent/index.html)

### 事件类型
#### 单次触摸事件
```js
$(el).tap
```

#### 两次触摸事件
```js
$(el).doubleTap
```


#### 长按事件
```js
$(el).longTap
```

#### 滑屏事件
```js
$(el).swipe
```

#### 向上滑动事件
```js
$(el).swipeUp
```

#### 向下滑动事件
```js
$(el).swipeDown
```

#### 向左滑动事件
```js
$(el).swipeLeft
```

#### 向右滑动事件
```js
$(el).swipeRight
```

### 如何使用
```js
$('.container').swipeRight((res) => {
   ulDom.append(createLi(`向右滑动了${res}px`));
})

$('.container').swipe((x, y) => {
   ulDom.append(createLi(`滑屏事件,X轴滑动了${x}px,Y轴滑动了${y}px`));
})
...
```

### 如有疑问
扫描公众号，回复：加群
[https://www.vipbic.com/weixin.html](扫描公众号，回复：加群)