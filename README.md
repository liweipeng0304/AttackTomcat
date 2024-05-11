# AttackTomcat

## 检测漏洞清单

CVE-2017-12615 PUT文件上传漏洞
tomcat-pass-getshell 弱认证部署war包
弱口令爆破
CVE-2020-1938 Tomcat 文件读取/包含

## 使用方式
  初次使用前请先在设置中重新设置配置文件，其他问题请仔细阅读！！！，java -jar \*.jar 启动可查看运行日志信息！！

​	下载源码maven编译，或者直接下载Releases。

​	双击jar包即可运行或执行`java -jar AttackTomcat`

![image-20221113190826427](https://github.com/tpt11fb/AttackTomcat/blob/main/images/image-20221113190826427.png)

![image-20221113190913584](https://raw.githubusercontent.com/tpt11fb/AttackTomcat/main/images/image-20221113190913584.png)

## 代理

​	使用http和socket代理。

![image-20221113191041737](https://raw.githubusercontent.com/tpt11fb/AttackTomcat/main/images/image-20221113191041737.png)

## 配置

​	启动jar包，生成配置文件config。

​	AJP漏洞使用python脚本验证，需要安装python3环境。命令格式：python -V。

​	注意：若出现如下提示，建议直接下载Release中的AttackTomcat.zip。

![image-20221113191218888](https://raw.githubusercontent.com/tpt11fb/AttackTomcat/main/images/image-20221113191218888.png)

## 说明

​	此工具只用来学习交流，自我检测，禁止非法扫描，
