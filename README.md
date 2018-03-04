# MyDuerOS-PythonDcsSdk-RaspberryClient
### 本项目代码来源链接：https://github.com/MyDuerOS/DuerOS-Python-Client
### 作者是百度大神刘才权，其简书主页：https://www.jianshu.com/u/bf03aa158e75 博客主页 https://caiquanliu.github.io/
### 本人详细教程链接： https://developer.dueros.baidu.com/didp/forum/topic/show?topicId=245089
### 本项目为修改自定义唤醒词版本，喊“小白”可以唤醒。
### 请修改为自己的DuerOS设备开放平台上创建的音箱产品的ID，需要百度开发者账号授权。
#### vim /home/pi/MyDuerOS-PythonDcsSdk-RaspberryClient/app/auth.py
#### CLIENT_ID = '你的CLIENT_ID'
#### CLIENT_SECRET = '你的CLIENT_SECRET'
### 需要赋予最高权限才可执行 chmod 777 wakeup_trigger_start.sh auth.sh enter_trigger_start.sh 
### 或者在Shell脚本前添加sh
### sh auth.sh
### sh wakeup_trigger_start.sh
### sh enter_trigger_start.sh
