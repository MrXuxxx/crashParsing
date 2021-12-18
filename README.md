# crashParsing
对ips进行dSYM化的解析小脚本，十分轻量。
将.ips崩溃报告文件导入文件目录
在文件夹中的这个.xcarchive文件右键，显示包内容，就可以看到一个名为dSYMs的文件夹，把里面的.dSYM文件拷出来，同样放到文件目录下
接下来，只需要run CrashTool，就会自动建立一个crash文件
