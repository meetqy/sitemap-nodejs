# sitemap-nodejs
Enter the site address, automatically crawl all the links in the site, and generate sitemap.

# Compared with other sitemap auto-generated modules
* When need to sitemap, you can immediately generate, no longer have to worry about the development process, did not take into account the sitemap problem.
* As long as there is a network can generate sitemap.

# installation
Use the npm install command:
```hash
npm install sitemap-nodejs
```
# Super simple use
```javascript 
var sitemap = require('sitemap-nodejs');
sitemap.init({
	href:'https://www.meetqy.com',
	save_path:'sitemap.txt'
});
```
href：Website address.

save_path：sitemap file save address.

Note: Currently only generate txt file, can not generate other format files!

save_path：sitemap文件保存地址

注意：目前只能生成txt文件，不能生成其他格式文件！
