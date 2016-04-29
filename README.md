# http-server
http-server 是一个简单的零配置命令行HTTP服务器, 基于 nodeJs，这样就不要重复的写 nodeJs 的 web-server.js。


安装：

cmd进入指定目录文件夹，输入 npm install http-server 


使用：

cmd输入http-server文件地址即可启动服务访问页面：node node_modules/http-server/bin/http-server

注意：不要进入node_modules\http-server\bin文件夹下面去执行 node http-server 命令！

node node_modules/http-server/bin/http-server 向外可以访问到与node_modules同级目录的文件和文件夹；

node http-server只能访问到与http-server同级目录下的文件和文件夹。
