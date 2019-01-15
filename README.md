# DuerOS

Baidu DuerOS DCS Python SDK For RespberryPi Client

# 项目源码
[DuerOS-Python-Client](https://github.com/MyDuerOS/DuerOS-Python-Client)  

# 项目作者
百度刘才权  
[GitHub主页](https://github.com/caiquanliu)   
[简书主页](https://www.jianshu.com/u/bf03aa158e75)  
[博客主页](https://caiquanliu.github.io/)  

# 项目教程
[本人详细的DuerOS教程](https://developer.dueros.baidu.com/didp/forum/topic/show?topicId=245089)  

# 唤醒词
默认是**小白**   
[唤醒词训练地址](https://snowboy.kitt.ai/hotword/351)  

# 修改步骤
- 请修改为自己的DuerOS设备开放平台上创建的音箱产品的ID，需要百度开发者账号授权。
- 修改配置文件  
```shell
vim /home/pi/MyDuerOS-PythonDcsSdk-RaspberryClient/app/auth.py
```
- CLIENT_ID = '你的CLIENT_ID'
- CLIENT_SECRET = '你的CLIENT_SECRET'
- 需要赋予最高权限才可执行 
```shell
chmod 777 wakeup_trigger_start.sh auth.sh enter_trigger_start.sh 
```
- ./auth.sh
- ./wakeup_trigger_start.sh
- ./enter_trigger_start.sh
- 或者在Shell脚本前添加sh
- sh auth.sh
- sh wakeup_trigger_start.sh
- sh enter_trigger_start.sh

# 推荐
本人修改版本，添加多项配置项，更加自定义。  
[DuerOS-Modularization](https://github.com/HuangDayu/DuerOS-Modularization)  
