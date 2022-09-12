# lol-helper

- 英雄联盟助手,主要使用LCU API,**未修改**客户端内容,**不会封号!**
- 点击[Releases](https://github.com/4379711/lol-helper/releases)页面下载**.msi**安装包,安装后启动软件即可
- 功能失效可能是**未以管理员身份运行程序**
  - 方式一: 对着图标右键 -> 以管理员身份运行
  - 方式二: 对着图标右键 -> 属性 -> 以管理员身份运行此程序  -> 确定

## 项目说明

- 使用 [LCU API](https://riot-api-libraries.readthedocs.io/) 开发,另外附上 [拳头文档](https://developer.riotgames.com/docs/lol/)
- V2.0版本,只使用了API的功能,绝不封号
- V2.0+版本,添加了模拟行为,例如光速摸眼,挂机模式等
- V4.2版本,添加游戏内一键喊话,自动发送历史战绩
- V4.3版本,某些对喷内容被屏蔽,现在提供修改入口,在安装目录下的words.txt; 
- V4.3版本,使用大神和牛马称谓,不再显示战绩
- V4.3版本,添加彩虹屁功能,一键发送,让队友沉迷在你的彩虹屁中,从而赢得比赛!

## 功能说明

- 修改段位(此功能所有好友可见修改后的段位)
- 修改生涯背景图(更换后永久生效,提供了接口服务,但没提供操作界面)
- 修改游戏在线状态
- 自动接受对局
- 掉线自动重连
- 盲仔光速摸眼,即(眼闪W三键),默认设置D=闪现,4=眼,w=金钟罩;同理,可自定义其他英雄的连招等
- ~~挂机模式,控制英雄乱走,防止掉线~~(由于xxx原因,已下架这个功能)
- 选英雄界面,提示红蓝双方
- 查询对局双方的近期战绩,后续再实现可以发送到游戏内
- 游戏内一键喊话,对喷
- 游戏内一键鼓励队友,彩虹屁
- 计算得分,添加大神和牛马称谓
  - 最近三把(KDA+输赢)的平均值
  - KDA->(击杀*1.2+助攻*0.8)/(死亡*1.2)
  - 输赢->赢+1 输-1

## 软件截图
![安装后的图标](https://github.com/4379711/lol-helper/raw/master/src/main/resources/assets/logo.jpg)
![主界面](https://github.com/4379711/lol-helper/raw/master/src/main/resources/assets/main.jpg)
![段位和状态](https://github.com/4379711/lol-helper/raw/master/src/main/resources/assets/01.jpg)
![自动接受对局](https://github.com/4379711/lol-helper/raw/master/src/main/resources/assets/02.jpg)
![房间内发送文字](https://github.com/4379711/lol-helper/raw/master/src/main/resources/assets/03.jpg)
![游戏内发送文字](https://github.com/4379711/lol-helper/raw/master/src/main/resources/assets/04.jpg)


## 未来功能

- 暂无想法,欢迎提交建议


## 免责声明

本项目仅供学习,不得用作商业用途,不得用作违法行为

## 侵删联系

如有侵权行为,请联系我
