# Event

## add/removeEventListener

<p data-height="300" data-theme-id="0" data-slug-hash="grZzbe" data-default-tab="js,result" data-user="luics" data-embed-version="2" class="codepen">See the Pen <a href="http://codepen.io/luics/pen/grZzbe/">event</a> by luics (<a href="http://codepen.io/luics">@luics</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>  

See [EventTarget](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget) for more details.

### 练习

<p data-height="265" data-theme-id="0" data-slug-hash="aGPEYq" data-default-tab="js,result" data-user="luics" data-embed-version="2" data-pen-title="event-exercise" class="codepen">See the Pen <a href="https://codepen.io/luics/pen/aGPEYq/">event-exercise</a> by luics (<a href="https://codepen.io/luics">@luics</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>


## Capturing vs Bubbling

先看一个简单的例子：

<p data-height="265" data-theme-id="0" data-slug-hash="NMeNgv" data-default-tab="js,result" data-user="luics" data-embed-version="2" data-pen-title="event-capture-bubble" class="codepen">See the Pen <a href="https://codepen.io/luics/pen/NMeNgv/">event-capture-bubble</a> by luics (<a href="https://codepen.io/luics">@luics</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

下面的例子是对前一个例子的扩展，以动画的形式展现`capture-bubble`过程

<p data-height="400" data-theme-id="0" data-slug-hash="ONrZoq" data-default-tab="js,result" data-user="luics" data-embed-version="2" class="codepen">See the Pen <a href="http://codepen.io/luics/pen/ONrZoq/">event-capture-bubble</a> by luics (<a href="http://codepen.io/luics">@luics</a>) on <a href="http://codepen.io">CodePen</a>.</p>  
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>  

See [Event Capturing and Bubbling in JavaScript](https://www.kirupa.com/html5/event_capturing_bubbling_javascript.htm) for more details.

### 练习

要求：

0. 页面元素：1 button，1 div
0. 给按钮绑定 bubble 事件和 capture 事件
0. 每次事件响应时在div中输出事件类型

## EventLoop

<p data-height="265" data-theme-id="0" data-slug-hash="oxVoqK" data-default-tab="js,result" data-user="luics" data-embed-version="2" class="codepen">See the Pen <a href="http://codepen.io/luics/pen/oxVoqK/">event-queue</a> by luics (<a href="http://codepen.io/luics">@luics</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>  

See [EventLoop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop) for deep sight.
