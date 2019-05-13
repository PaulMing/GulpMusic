

技术栈：Gulp、Zepto库、Less、Autoprefixer、requestAnimationFrame();  


基础配置：  
1.初始化项目；  
2.配置gulpfile.js: html/css/js/监听/本地服务器(自动刷新页面)/插件；  


开发：  
1.结构：合理划分开发模块；  
2.样式：  
(1).适配移动端 -> meta标签、相对单位vw/vh/%/px的使用、Flex布局、三栏布局、音乐转盘自适应正方形等；   
(2).预处理语言less，后处理器postcss、autoprefiexer;  
3.行为：页面动态渲染、音乐播放暂停切换/音乐转盘、进度条部分(渲染时间，进度条动态加载，进度条拖拽); 

项目小结：  
开发过程中划分模块，根据功能封装单独JS文件，文件暴露接口的方式不同(函数/对象/构造函数) -> 每个js文件中使用立即执行函数，模式增强，接口挂载都window -> 参考jQuery源码；  


推荐项目[star]：  
简书笔记codeing、LevelOne阶段demo汇总[ES3/5/6/DOM/BOM/JQuery/网络/H5/CSS3/模块化(CommonJS/AMD/CMD/ES6Mod)/构建工具(Webpack/Gulp)/你不知道的JS(原理篇/函数式编程篇/数学计算篇)/Git/GitHub]  
URL:https://github.com/PaulMing/LevelOnecodeing

