 **

###  **使用腾讯云函数进行安徽信息工程学院今日校园每日自动签到
** 
 
项目介绍
该项目基于大佬所作的今日校园签到脚本进行修改，将其表单填写精简化
 大佬项目地址https://gitee.com/Finch1/FuckDailyCP


#### 使用说明

 **

### 1. 打开腾讯云函数 https://console.cloud.tencent.com/scf/list  
** 
![新建云函数](https://images.gitee.com/uploads/images/2021/0206/125219_08bd74ac_1805470.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0206/125615_83fda65d_1805470.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0206/125929_9f62f97b_1805470.png "屏幕截图.png")
 **

### 2. 在代码中添加用户名密码，定位信息。 建议注册Qmsg酱用于接收打卡提醒以防万一 Qmsg酱网址https://qmsg.zendee.cn/ 也可以使用别的通知 主要qq常用
** 

![输入图片说明](https://images.gitee.com/uploads/images/2021/0206/130243_899bf79c_1805470.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0206/130358_06d106af_1805470.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0206/130503_e36a5c19_1805470.png "屏幕截图.png")
###  ** 3.填写完成后点击测试，成功时Qmsg会提示SUCCESS，在执行日志中也会显示 
** 
![输入图片说明](https://images.gitee.com/uploads/images/2021/0206/131431_e3ffd06f_1805470.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0206/130746_5f66a32d_1805470.png "屏幕截图.png")
若提示表单有更新或者表单信息未填写完整，就需要复制日志中数据到左边目录下dlcpdate.json 因为表单已经更改好无需更改
![输入图片说明](https://images.gitee.com/uploads/images/2021/0206/131118_cbca57cf_1805470.png "屏幕截图.png")
该文件内，isSelected中null为不选该选项，1为选择该选项 修改后再次点击部署或测试即可，也无需更改，这都是你前一天数据
###  **4. 每日定时签到 触发管理→创建触发器
** 
 
![输入图片说明](https://images.gitee.com/uploads/images/2021/0206/132924_24d52dc8_1805470.png "屏幕截图.png")
  

### **浪费他人时间是可耻的行为**
