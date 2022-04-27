[![](https://img.shields.io/badge/todayInHistory-@Vogadero-success.svg?style=plastic)](https://github.com/Vogadero/todayInHistory)
![](https://img.shields.io/badge/language-Jquery-yellow.svg?style=plastic)
![](https://img.shields.io/badge/language-JavaScript-orange.svg?style=plastic)
![](https://img.shields.io/badge/language-Html-9cf.svg?style=plastic)
![](https://img.shields.io/badge/language-Css-blueviolet.svg?style=plastic)
![](https://img.shields.io/npm/l/express?style=plastic)

# 项目简介🚩

- 历史上的今天
- 演示地址：https://vogadero.github.io/todayInHistory/

## 1. 功能模块🎨

#### 1.1 首页🛫

| 功能                   |
| ---------------------- |
| 展示历史上的今天大事件 |
| 查询当前事件的百度百科 |
| 显示当前设备的信息     |

## 2. 截图⭐

![](01.jpeg)

## 3. 项目架构🍽️

| 系统分层 | 使用技术                    |
| -------- | --------------------------- |
| 客户端   | Art-template、jQuery、layui |

## 4. 项目运行环境搭建🌈

- 克隆远端数据仓库到本地：`git clone 仓库地址`
- 拉取远程仓库中最新的版本：`git pull 远程仓库地址 分支名称`
- 双击index.html

# 功能介绍🦷

## 🕵️‍♀️历史上的今天

- 展示内容：历史上的今天大事件

- API

  - 地址：https://query.asilu.com/today/list

  - 方式：GET

  - 参数类型：jsonp

    


## :card_index:**查询**

- 展示内容：当前事件的百度百科

- API

  - 地址：https://query.asilu.com/today/list

  - 方式：GET

  - 参数类型：jsonp

    


## :woman_technologist:**设备信息**

- 展示内容：当前设备的基础信息

- API

  - 地址：https://api.asilu.com/user-agent/
  - 方式：GET
  - 参数类型：jsonp

  

# Tree🌵    

```
历史上的今天
├─ 01.jpeg
├─ index.html
├─ js
│  ├─ jquery-3.6.0.min.js
│  └─ template-web.js
├─ layui-v2.6.8
│  └─ layui
│     ├─ css
│     │  ├─ layui.css
│     │  └─ modules
│     │     ├─ code.css
│     │     ├─ laydate
│     │     │  └─ default
│     │     │     └─ laydate.css
│     │     └─ layer
│     │        └─ default
│     │           ├─ icon-ext.png
│     │           ├─ icon.png
│     │           ├─ layer.css
│     │           ├─ loading-0.gif
│     │           ├─ loading-1.gif
│     │           └─ loading-2.gif
│     ├─ font
│     │  ├─ iconfont.eot
│     │  ├─ iconfont.svg
│     │  ├─ iconfont.ttf
│     │  ├─ iconfont.woff
│     │  └─ iconfont.woff2
│     └─ layui.js
├─ README.md
└─ 时间.ico
```