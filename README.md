# HORA
小美人资，基于OSGI模块化的SAAS专业人力资源系统，主要有人事档案、考勤管理、薪酬管理、绩效管理、招聘以及后勤管理几大模块，适用于中小型企业，</br>
本系统特点从代码级分模块开发与加载，从根本上解决系统复杂度问题，同时在人力资源领域能够提供深度服务功能。</br>
考勤机支持ZK指纹与人脸机，并对没有WEB模块的机型提供虚拟云服务功能。</br>
移动端目前在微信小程中提供便捷的功能，包括：移动打卡、请假、加班、工资条等。</br>


# 安装
1：安装JDK8.</br>
2: 安装REDIS(可选).</br>
3：下载所有的压缩包后合并解压.</br>

# 配置
1：修改默认数据库名称，主要用于默认的数据与全局数据保存。</br>
用压缩文件打开bin/chuniter-kernel_3.6.0.0.jar中的META-INF/MANIFEST.MF中的default-databaseName: 数据库名.</br>
2: 修改数据库连接池单元配置</br>
在unit/base/DBPool-1.1.0.jar,打开db.properties，以下是配置说明:</br>

user=数据库名</br>
password=加密后的密码</br>
driverClass=驱动类名</br>
url=jdbc url</br>
dbType=mssql(可选项：mysql、oracle、mssql)</br>
dbName=数据库名</br>
default=yes（是否是默认连接池，在多数据连接池中可用）</br>


# 运行

进入/bin/目录，widows执行startup.bat，linux执行startup.

# 以下为产品美图
![horaindex](https://hr.gddshl.com/images/horaindex.jpeg)
![hora1](https://hr.gddshl.com/images/hora1.jpeg)
![hora2](https://hr.gddshl.com/images/hora2.jpeg)
![hora3](https://hr.gddshl.com/images/hora3.jpeg)
![hora4](https://hr.gddshl.com/images/hora4.jpeg)
![hora5](https://hr.gddshl.com/images/hora5.jpeg)

# 技术支持
0769 333 555 23 李先生

# 在线体验
产品地址：https://hora.gddshl.com</br>
产品官网：http://hr.gddshl.com </br>
需要源码与技术支持的朋友请致电公司或发邮件到:<a href='mail:329900041@qq.com'>329900041@qq.com<a/> ，目前只提供人事档案、薪酬以及绩效的源码。


