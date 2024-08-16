**扫码 >> 源码商城 获取** ![qrcode_for_gh_1266b4b5294a_258 (2)](https://github.com/user-attachments/assets/45838afd-19a8-4cdc-bdd5-74b9c76fb241)

**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务。项目仅供学习和毕业设计参考~**

#### 1.项目介绍

技术栈+工具：SpringBoot + MyBatis + shiro +Jsp +IDEA2022 + 微信开发工具

系统角色：管理员、出售用户、回收用户

系统功能：管理员（用户管理、公告管理、回收分类管理、品牌管理、设备管理、订单管理、评价管理等）、出售用户（微信授权登录、通知公告、查看收购信息、出售、个人中心等）、回收用户（微信授权登录、发布设备、管理设备、订单信息、评价信息等）

#### 2.项目部署

##### 2.1 后端部署

- 创建数据库，导入sql文件

- 打开idea，导入项目recycle-admin

- 根据本地数据库环境，修改数据库连接 src/main/resources/application.yml  6-9行

- 启动后端服务 http://localhost:8080/DigitalProductRecycling/ 

- 管理员账号/密码： admin/123456

##### 2.2 小程序端部署

- 打开微信开发工具，扫码登录

- 导入项目recycle-miniapp,选择测试号即可

- 微信授权登录即可，然后完善个人信息。 

- 测试的时候可以设置为回收用户，发布设备，然后再修改个人信息为出售用户去创建订单，然后再切为回收用户查看相关订单信息
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/1.png)
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/2.png)
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/3.png)
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/4.png)
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/5.png)
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/6.png)
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/7.png)
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/8.png)
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/9.png)
![0](https://github.com/Learning-Journey-Treasures/bysj-024/blob/master/91.png)
