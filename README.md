# neupy
NEU-Python 东北大学校园工具箱

### 用接口掌控你的校园生活！

## ❤一 导入方式
&nbsp;将neu.py放入Linux(Shell) or Windows(cmd)下的同级目录，该目录下启动Python3 idle，敲入：
from NEU import neu

## ❤二 功能概述
&nbsp;本模块由一个neu类构成。完全采用http requests response session实现，适合各类能跑Python环境的设备！！（悄悄的说一句，Android手机也可以噢！）。

&nbsp;首先，你需要声明一个对象，举个栗子~
person = neu(学号,密码)  #声明person对象
&nbsp;接下来，就可以愉快的玩耍了~ 
以下是对象功能表：
1. 对象名.ipgw.connect()  #连接校园网
2. 对象名.ipgw.info()  #校园网余额查询
3. 对象名.work.gpa()  #查询gpa
4. 对象名.work.exam()  #查询近期考试
5. 对象名.ecard.money()  #查询一卡通余额

### 更多功能敬请期待！
### 欢迎提出建议与一起fork neupy库！一起愉快的玩耍Python吧！
### 来自一只在东北体验生活的程序猿的留言~
