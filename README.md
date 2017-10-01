# sitemap-nodejs
输入网站地址，自动爬取网站当中所有的链接，并生成sitemap。

# 安装
使用npm install命令：
```hash
npm install sitemap-nodejs
```
# 超级简单的使用
```javascript 
var sitemap = require('sitemap-nodejs');
sitemap.init({
	href:'https://www.meetqy.com',
	save_path:'sitemap.txt'
});
```
href:网站地址

save_path:sitemap文件保存地址
