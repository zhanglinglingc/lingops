# LingOps（灵控）- AWD/AWDP 竞赛自动化平台

<p align="center">
  <img src="https://img.shields.io/badge/Go-1.21+-00ADD8?style=flat-square&logo=go" alt="Go version">
  <img src="https://img.shields.io/badge/React-18+-61DAFB?style=flat-square&logo=react" alt="React version">
  <img src="https://img.shields.io/badge/TypeScript-5+-3178C6?style=flat-square&logo=typescript" alt="TypeScript version">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">
</p>

## 📖 简介

LingOps（灵控） 是一个专为 AWD/AWDP 攻防竞赛设计的竞赛自动化平台，提供 IP探测、WebShell 管理、SSH 终端、基线加固、Flag 读取等核心功能，帮助参赛选手在比赛中高效管理多个目标。



## ✨ 核心功能

### 🔍 目标探测
- **网络扫描** - 快速检测目标主机存活性，支持批量 IP 和 IP 范围探测

### ⚡ 攻击模块
- **Shell 管理** - WebShell/SSH 连接管理，支持虚拟终端、文件管理
- **木马生成** - 生成各种类型的 WebShell 木马
- **权限维持** - 通过不死马、内存马维持已获取的权限

### 🛡️ 防御模块
- **WebShell 扫描** - 基于规则引擎的 WebShell 检测，支持 ZIP 上传和远程扫描
- **WAF 管理** - WAF 规则配置与部署

### 🛠️ 运维模块
- **基线管理** - 网站备份、安全巡检、权限标准化、PHP 安全配置、后门清理、文件差异监控、反弹 Shell 终止、端口封禁、SSH密码修改、Mysql密码修改
- **数据库管理** - MySQL 连接管理、SQL 执行、数据库备份恢复

### 🚩 Flag 读取
- **后台任务模式** - 切换页面不中断

- **定时读取** - 设置间隔自动循环读取

- **历史记录** - 查看所有读取记录和时间

  

## 🚀 快速开始

### 环境要求
- Windows10 64位或更高

### 1. 下载发行版本
### 2. 启动可执行文件

### 3. 访问
打开浏览器访问 `http://127.0.0.1:8080`

**默认账号密码：**
- 用户名：`admin`

- 密码：`admin123`

  

## 🔒 部分功能预览

### ✨ 首页

![image-20260123162004132](C:\Users\ling\Downloads\lingops\imgs\总览.png)

### 🔍 目标探测

![image-20260123162157429](C:\Users\ling\Downloads\lingops\imgs\探测.png)

### ⚡ shell管理

![image-20260123163002939](C:\Users\ling\Downloads\lingops\imgs\shell管理.png)

### 🛡️ WAF管理

![image-20260123162420936](C:\Users\ling\Downloads\lingops\imgs\防御.png)

### 🛠️ 基线管理

![image-20260123163158401](C:\Users\ling\Downloads\lingops\imgs\基线管理.png)

### 🚩 Flag 读取

![image-20260123163524805](C:\Users\ling\Downloads\lingops\imgs\flag读取.png)

## 🔒 安全说明

⚠️ **本工具仅供授权的安全测试和 CTF 比赛使用！**

- 请勿用于未授权的系统
- 请勿用于非法活动
- 使用者需自行承担法律责任

