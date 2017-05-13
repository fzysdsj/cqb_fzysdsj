# 春秋杯参赛作品
## 信1401-2 杜维杰
### 静态网页结构
## 1.项目结构
├── css	 样式有关文件目录     
├── font 字体图标文件目录
├──html  相关静态网页目录  
├──img   图片所在目录  	
├──js    js脚本所在目录  
├── lib  相关库所在目录
├──index.html  主页
└── readme.md  解释文档

## 2.编码约定 
- 在head中引入必要的CSS文件，优先引用第三方的CSS，方便我们自己的样式覆盖
- 在body末尾引入必要的JS文件，优先引用第三方的JS，注意JS文件之间的依赖关系，比如bootstrap.js依赖jQuery，那就应该先引用jquery.js 然后引用bootstrap.js

### 2.1 CSS约定
- 除了公共级别样式，其余样式全部由 模块前缀
- 尽量使用 直接子代选择器， 少用间接子代 避免错杀




## 3.项目名称 
>暂定
## 4.项目立意 
> 立意以假设春秋航空和石家庄铁道大学两者联手举办“春航-石铁大各种游”路线为起点

## 5.运用技术 
- 暂时没用任何模板，后期会将html加上jade模板，css换成less。
- 后台语言初步计划为node，数据库为mongodb或mysql。
- 前端包管理工具为bower。
- 后端包管理工具为npm。
- 前台框架用的bootstrap，后期会加angular
- 后台框架初步打算为express或koa。
- 版本管理工具为git。
- 自动化工具为gulp。
- 编辑器为sublime。

## 6.静态网页 
- 首页(index.html)
- 注册页(index.html)
- 航程预定页(hangchengyuding.html)
- 线路介绍页(xianlujieshao.html)
- 游客微博页(visiterSay.html)

## 7.项目优势
- 页面自适应，完美兼容各种PC端和移动端
- 运用字体图标，减少了请求响应
- 后台采用node，完全不会担心跨平台开发问题，大大提高开发效率。
