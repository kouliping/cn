# 创建库
 用户可以通过区块链数据服务管理控制台创建数据库，数据库名实例内唯一，不同实例不受此限制。  

## 操作步骤
1.  登录 [区块链数据服务控制台](https://bds-console.jdcloud.com/block/list)。  
2.  选择目标实例所在地域。 
3.  点击目标实例，进入实例详情页，切换至 **库管理** Tab 页，点击 **创建库** 按钮，创建库弹窗框参数说明如下。
    * 库名称：库名我们保留了一些关键字名称，请参考 [限制说明](待补充)，并且库名的长度和字符有一定限制，具体以控制台为准。
    * 字符集：默认是 Chinese_PRC_CI_AS，同时还提供了 Chinese_PRC_CS_AS，SQL_Latin1_General_CP1_CI_AS，SQL_Latin1_General_CP1_CS_AS，Chinese_PRC_BIN 几个选项，可以按需选择。
    * 授权账号：从可授权账号中选中需要授权库访问权限的账号，点击 > 按钮，账号会添加至已授权账号列表，默认账号对库的访问权限是 **只读**，支持修改为 **读写**。
![创建库](Pic/创建库.png)
