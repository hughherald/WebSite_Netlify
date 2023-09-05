---
title: PC初始化设置
date: "2022-05-24T00:00:00+01:00"
draft: false
share: false
commentable: false
editable: false

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---

## **window11 多窗口设置**
1. 下载[ViVeTool](https://github.com/thebookisclosed/ViVe/releases/)，并解压

2. 运行CMD，cd至解压路径，运行下列命令 

- vivetool /enable /id:37634385
- vivetool /enable /id:39145991

3. 重启电脑


## **window11 系统图标删除**
进入注册表
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

- 图片{24ad3ad4-a569-4530-98e1-ab02f9417aa8}
- 音乐{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}
- 视频{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}
- 桌面{B4BFCC3A-DB2C-424C-B029-7FE99A87C641}

## **Mircosoft 无法登陆**
出现错误：你无法登录
- Internet 选项 > 高级 
- 勾选TLS1.2 TLS1.3


## **window11 菜单定制**
下载[ViVeTool](https://github.com/BluePointLilac/ContextMenuManager/releases)