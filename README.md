## sitemap-nodejs
输入网站地址，自动爬取网站当中所有的链接，并生成sitemap。

## 与其他sitemap自动生成模块相比
* 什么时候需要sitemap，就可以马上生成，再也不必担心在开发过程中，没有考虑到sitemap的问题。
* 只要有网络便可以生成sitemap。

## 安装
使用npm install命令：
```hash
npm install sitemap-nodejs
```
## 超级简单的使用
```javascript 
var sitemap = require('sitemap-nodejs');
sitemap.init({
    href:'https://www.meetqy.com',
    save_path:'sitemap.xml'
});
```

## 根据扩展名生成对应格式的sitemap
例：
* 生成xml格式
```javascript
var sitemap = require('sitemap-nodejs');
sitemap.init({
    href:'https://www.meetqy.com',
    save_path:'sitemap.xml'
});
```
* 生成txt格式
```javascript
var sitemap = require('sitemap-nodejs');
sitemap.init({
    href:'https://www.meetqy.com',
    save_path:'sitemap.txt'
});
```

## 参数

href（必须）：网站地址

save_path（可选）：sitemap文件保存地址，扩展名会决定生成sitemap的格式，默认为txt格式。

show_url（可选）：是否在控制台打印当前爬取的url地址，默认不开启。


