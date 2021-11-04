# cobalt-strike4.0 for mac汉化版
#coblatstrike.icns为圆角方形图标
#直接打开.jar文件报错，因此选择命令启动
#命令启动
cd /xxx/xxx/xxx/xxx/cobaltstrike4.0-cracked && java -Xdock:icon=cobaltstrike.icns -Dfile.encoding=UTF-8 -javaagent:CobaltStrikeCN.jar -XX:ParallelGCThreads=4 -XX:+AggressiveHeap -XX:+UseParallelGC -jar cobaltstrike.jar
#制作app
使用mac自带软件automator.app，选择「新建文档」，选择文稿类型为「应用程序」，点击「选取」，将「运行Shell脚本」拖入右边，输入以上命令，点击右上角「运行」测试，成功后保存，选择文件格式为「应用程序」保存到应用程序栏。
#修改app图标
右键程序选择查看简介，将coblatstrike.icns拖到图标处。
#teamseerver
将整个文件拖入到服务器中，执行命令chmod 777 teamserver，给teamserver权限，执行./teamserver 「服务器IP」 「密码』
#客户端连接
运行客户端，输入服务器IP，用户名任意，密码填写上面设置的密码，点击连接

