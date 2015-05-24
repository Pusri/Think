# 电信资源共享平台V1.0
## 环境部署
### Linux
Linux下使用一键PHP环境部署工具部署：
phpStudy for Linux 支持Apache/Nginx/Tengine/Lighttpd，
支持php5.2/5.3/5.4/5.5切换

下载版：http://lamp.phpstudy.net/phpstudy.bin    

完整版：http://lamp.phpstudy.net/phpstudy-all.bin

**安装：**    

`wget -c http://lamp.phpstudy.net/phpstudy.bin`   

`chmod +x phpstudy.bin`   权限设置    

`./phpstudy.bin `　　　　运行安装   

安装过程会进行版本选择：我们的环境选择PHP5.3+Apache+MySQL。

### Windows
Windows下使用phpStudy集成环境部署：
下载phpStudy并安装，环境选择PHP5.3+Apache+MySQL。


## 应用安装

### oneThink安装模式
1. 将think目录下的文件全部放到部署目录WWW或htdocs下（环境版本不同部署目录不同）；
2. 将install目录下的install.lock删除，即可使用安装模式；
3. 浏览器访问即可进入安装界面，通过安装界面配置数据库及后台信息。