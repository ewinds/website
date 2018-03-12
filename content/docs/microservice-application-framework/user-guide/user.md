+++
title = "用户层"
weight = 4
+++

# IV 用户层

###1.用户信息维护

- 不可更改项：
    - 用户名：用户名可用于登陆，一旦创建，不可修改
    - 组织：用户所属组织用户本人不可变更

- 可更改项：
    - 昵称：用户的别称
    - 邮箱：填写真实正确的邮箱，可用于登陆、密码找回
    - 语言：系统界面显示的语言
    - 时区：系统所有与时间有关的操作根据选择的时区进行转换

### 2.密码更改

- 密码更改要符合系统密码策略
- LDAP用户不能在本系统更改密码，只能在LDAP访问的系统中实现密码的更改
- 更改密码需要输入原始密码
- 更改密码需要确定新密码 

### 3. 授权

- 用户可以通过调用接口创建自己的token
- 可创建、删除、详情查看、编辑、搜索授权

![授权管理](http://upload-images.jianshu.io/upload_images/7452984-2339b05d67c3c4e2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 3.1 创建授权

- 名称
    - 具有唯一性

- 过期时间
    - token的失效时间
    - 无法选择当前时间之前的

![创建授权](http://upload-images.jianshu.io/upload_images/7452984-39c3baeed9923834.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 3.2 其他操作

- **删除：**可删除token数据
- **编辑：**可修改token的过期时间，不可修改token名称