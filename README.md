<h2>一个前端开发者的简历</h2>
<b>技能树</b>
<ul>
  <li>javaScript库：jQuery / zepto</li>
  <li>css相关：sass / css3动画、过渡 / 响应式布局 / flex布局</li>
  <li>数据处理M：ajax / json</li>
  <li>模板渲染V：handlebars</li>
  <li>路由管理C：hashchange / pushState</li>
  <li>模块化及构建工具：require / gulp / fis</li>
  <li>图片处理：ps</li>
  <li>mvvm框架vueJs(熟悉) / nodeJs(熟悉) / mongodb(熟悉)</li>
</ul>
<b>项目经验</b>
<dl>
  <dt><a href="http://m.easeeyes.com/active160214.html">情人节随心配</a></dt>
  <dd>
    当时做这个的时候比较赶，甚至设计图都没有给到==！项目要求每人只能选择两件，可以重复，需要有添加商品、删除商品功能，有单独的层可以查看已经选择的商品。最主要的是添加和删除提醒，用的是弹层的方式，没有抽象成库，难点在于度数选择判断和数据同步，主要通过数据主导渲染dom，这样不会导致数据和dom不一
  </dd>
  <dt><a href="https://github.com/aduck/YJS/blob/master/Y.js">网站通用功能库Y.js</a></dt>
  <dd>
    包含选择器、ajax模块、cookie模块、localstorage本地数据管理、loadScript脚本加载、random随机性相关模块等，兼容IE6+
  </dd>
  <dt><a href="https://github.com/aduck/datePick/blob/master/ani.css">css3动画库</a></dt>
  <dd>
    主要用来处理高版本浏览器和移动端动画，具体效果有fade渐隐渐现、zoom放大缩小、shake抖动、2d旋转、3d旋转、从各方向滑入滑出
  </dd>
  <dt><a href="https://github.com/aduck/datePick/blob/master/js/tmAble.js">移动端触屏滑动插件</a></dt>
  <dd>
    小型触屏事件库，控制元素可移动的方向，通常作为底层，日期选择插件和地址选择插件就是在这个基础上编写的
  </dd>
  <dt><a href="https://github.com/aduck/datePick/blob/master/js/datePick.js">日期选择组件</a></dt>
  <dd>
    在做新版移动端改版时要求模拟安卓和ios原生选择器组件编写出来的，定义起始年份和终止年份就可以使用了，具体demo效果图<a href="https://github.com/aduck/datePick/blob/master/demo.png">参见</a>
  </dd>
  <dt><a href="https://github.com/aduck/wap_bf160323/blob/master/areaSelect.js">三级联动地址选择器</a></dt>
  <dd>
    和日期选择器功能基本类似，区别在于数据处理部分，难点在于数据和dom表现统一上
  </dd>
  <dt><a href="https://github.com/aduck/wap_bf160323/blob/master/pics.js">基于zepto/jQuery图片轮播组件</a></dt>
  <dd>
    上一版移动端轮播图插件用的是swipe.js，但是体积有点庞大，这一版加上了左右剪头切换，干脆就写了一个，选项有是否可循环、是否自动播放、播放完成后回调函数等，可以结合触屏插件使用
  </dd>
  <dt><a href="https://github.com/aduck/wap_bf160323/blob/master/pop.js">移动端弹层插件</a></dt>
  <dd>预留动画接口，可结合css3动画库实现相关动态效果</dd>
  
  
  
  
  
  
</dl>
