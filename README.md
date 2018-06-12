# NodeJSDemo
前端模板
https://nodejs.org/en/
https://jingyan.baidu.com/article/91f5db1b2bb6941c7f05e33c.html
安装一路下一步
node -v
npm -v
①、我们要先配置npm的全局模块的存放路径以及cache的路径，例如我希望将以上两个文件夹放在NodeJS的主目录下，便在NodeJs下建立"node_global"及"node_cache"两个文件夹
②、启动cmd，输入
npm config set prefix "C:\Program Files\nodejs\node_global"以及npm config set cache "C:\Program Files\nodejs\node_cache"
③、现在我们来装个模块试试，选择express这个比较常用的模块。同样在cmd命令行里面，输入“npm install express -g”（“-g”这个参数意思是装到global目录下，也就是上面说设置的“C:\Program Files\nodejs\node_global”里面。）。待cmd里面的安装过程滚动完成后，会提示“express”装在了哪、版本还有它的目录结构是怎样。
