# 一个基本功能稳定的主分支 
<b>注意：目前还存在一些bug，部署到公司内部后，已经修复，但是在github上面的项目没有提交<b><br>
## 设备管理系统安装配置方法：

1. 配置好了apache + mysql + php的环境
2. 下载devMan-branch-noip-install或者devMan-branch-noip-QRcode-install 分支代码
3. 解压，并将其解压后的目录改为ci
4. 访问 host + install 目录
5. 填写数据库地址、要创建的数据库，用户名、密码，更具步骤安装即可  <br>

默认用户名：admin <br>
密码：admin <br>
安装后需要修改一些配置文件，如:<br>
/application/config/database.php 文件，需要修改安装时填写的数据库地址，用户名和密码，来替换点默认的<br>
/application/config/config.php 最后一行修改对应的域名 <br>
安装遇到问题，请邮件联系：908963295@qq.com <br>
## 一、设备管理系统简单介绍
<b>设备管理系统的原理，以及要解决的问题:</b><br>

1. 解决公司内部测试手机的签借和签还的便捷性。代替手工记录在excel中或在签借的本子上
2. 如果记录在本子上，会由于签借的次数过多，会导致记录增多，很难维护并且很难查找，还繁琐。
3. 如果记录在excel上，每次记录都会打开excel，并且需要自己更新多条信息，最主要的是无法多人编辑，无法让要借设备的人员查看测试手机。
4. 设备管理系统主要解决一个让公司内部员工可以实时查看公司测试机的情况，被谁在什么时候借走了，应该找谁去调配测试机。让管理测试手机的人远可以更加方便的管理测试机，添加测试手机，签借、签还测试手机；以及对手机进行盘点，查看测试机的实时状态，方便手机的调配。

<b>设备管理系统简单介绍</b><br>
管理员拥有登录账号，登录后即可管理设备（添加，删除，修改，签借，签还，查看日志，盘点设备等功能）；普通人只能查询设备，申请查看手机，查看系统的管理员

1. 设备管理系统设备查询界面，普工用户可以申请设备，并查询哪些设备被借出去了：
![图片加载失败](/temp/设备查询.png)

2. 设备详情界面，查看设备的详细信息：
![图片加载失败](/temp/设备详情.png)

3. 管理设备界面（设备的签借，修改签借人，删除等功能）：
![图片加载失败](/temp/管理设备.png)

4. 设备盘点界面（用于帮助盘点设备，以及查看那些设备已经损坏不能用了）
![图片加载失败](/temp/设备盘点.png)

5. 添加设备:
![图片加载失败](/temp/添加设备.png)

6. 用户管理：
![图片加载失败](/temp/用户管理.png)

7. 用户详情：
![图片加载失败](/temp/用户详情.png)

8. 日志管理：
![图片加载失败](/temp/日志管理.png)
