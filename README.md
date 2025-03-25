[中文版](README.md)

# 点一下star✨，是对作者最大的支持

**如果成都有工作机会，请与我联系 codewithyou365@gmail.com**

# MQTT 客户端界面使用说明

## 项目简介

- 这是一个基于 Web 的 MQTT 客户端界面，允许用户连接到 MQTT 服务器，发布/订阅主题，并查看消息日志。
- 项目使用 Docker Compose 启动 EMQX MQTT 服务器。

## 快速开始

### 1. 启动 MQTT 服务器

使用以下命令启动 EMQX MQTT 服务器：

```bash
docker-compose up -d
```

### 2. 打开 MQTT 客户端界面

在浏览器中打开 `http://127.0.0.1:8080/index.html` ，开始使用 MQTT 客户端界面。

![演示](https://raw.githubusercontent.com/codewithyou365/emqx-client-html/refs/heads/main/demonstration.gif)

## 客户端操作

### 配置 MQTT 服务器

1. 在 "MQTT Server URL" 字段中输入服务器地址：`ws://localhost:8083/mqtt`
2. 点击 "Update Server" 按钮保存服务器地址。

### 注册客户端

1. 输入用户名（必填）
2. 输入密码（可选）
3. 点击 "Register" 按钮连接到服务器

### 订阅主题

1. 在 "Topic" 字段中输入要订阅的主题
2. 点击 "Subscribe" 按钮

### 发布消息

1. 在 "Topic" 字段中输入要发布到的主题
2. 在 "Message" 字段中输入要发送的消息
3. 点击 "Publish" 按钮

### 断开连接

1. 点击 "Close" 按钮断开选定客户端的连接