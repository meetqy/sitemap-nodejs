# sitemap-nodejs
输入网站地址，自动爬取网站当中所有的链接，并生成sitemap。
[1]:https://www.meetqy.com "meetqy"

# 与其他sitemap自动生成模块相比
* 什么时候需要sitemap，就可以马上生成，不用担心在开发过程中，没有考虑到sitemap的问题。
* 只要有网络便可以生成sitemap。

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
href：网站地址

save_path：sitemap文件保存地址

注意：目前只能生成txt文件，不能生成其他格式文件！
