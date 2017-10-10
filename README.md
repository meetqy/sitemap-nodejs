## sitemap-nodejs
Enter the site address, automatically crawl all the links in the site, and generate sitemap.

## Compared with other sitemap auto-generated modules
* When need to sitemap, you can immediately generate, no longer have to worry about the development process, did not take into account the sitemap problem.
* As long as there is a network can generate sitemap.

## installation
Use the npm install command:
```hash
npm install sitemap-nodejs
```
## Super simple use
```javascript 
var sitemap = require('sitemap-nodejs');
sitemap.init({
	href:'https://www.meetqy.com',
	save_path:'sitemap.txt'
});
```
href(Must): website address.

save_path(Can fill): sitemap file to save the address, the extension will determine the format to generate sitemap, the default format for the txt.

## Generate the sitemap in the corresponding format based on the extension
example:
* Generate xml format
```javascript
var sitemap = require('sitemap-nodejs');
sitemap.init({
    href:'https://www.meetqy.com',
    save_path:'sitemap.xml'
});
```
* Generate txt format
```javascript
var sitemap = require('sitemap-nodejs');
sitemap.init({
    href:'https://www.meetqy.com',
    save_path:'sitemap.txt'
});
```
