### NPC FE

### 1. **前端静态资源合并**

#### Why

>通过前端资源打包合并，减少页面的http请求，提升页面的加载速度

####  How to do

>使用Gulp,Webpack等前端打包工具，对资源进行打包合并

####  Links

> 

### 2.**table组件，form表单页面样式交互统一**

#### Why

>后端在开发页面的时候，未能按照前端指定的规范编写页面

####  How to do

>前端以测试的身份，逐一检查页面的样式和交互，使其统一

####  Links

> 

### 3.**iframe性能优化**

#### Why

>在npc项目中，通过使用iframe来快速实现单页面应用的效果，但是随着iframe的大量使用，页面的性能越来越低，急需优化。

####  How to do

> 1. 调研iframe的渲染原理，更加明晰其如何影响性能  2. 查找目前已有的国内外关于iframe性能调优的解决方案

####  Links

1. **[Iframes, onload, and document.domain](https://www.nczonline.net/blog/2009/09/15/iframes-onload-and-documentdomain/)**

2. **[iframe异步加载技术及性能](http://www.cnblogs.com/beiyuu/archive/2011/07/18/iframe-tech-performance.html)**

3. **[Using Iframes Sparingly](https://www.stevesouders.com/blog/2009/06/03/using-iframes-sparingly/)**

4. **[Iframe loading techniques and performance](http://www.aaronpeters.nl/blog/iframe-loading-techniques-performance?%3E)**

5. **[Modern iframe programing](http://www.aaronpeters.nl/blog/iframe-loading-techniques-performance?%3E)**

6. **[Using Iframes to Address Third-Party Script Issues and Boost Performance](http://radar.oreilly.com/2013/06/using-iframes-to-address-third-party-script-issues-and-boost-performance.html)**

7. **[Non-onload-blocking async JS](http://www.phpied.com/non-onload-blocking-async-js/)**


### 4.**交互优化**

#### Why

>页面中有许多页面交互存在着不合理，使用不方便等问题

####  How to do

> 通过修改页面显示，交互逻辑修改等优化交互

####  Links

> 

### 5.**js代码逻辑调优**

#### Why

>后端在编写前端js代码时，会出现js代码编写不规范，代码逻辑不严谨等问题

####  How to do

> 类似于2中修改table和form，逐一检查，修改完善

####  Links

> 
