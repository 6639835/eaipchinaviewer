# EAIP中国航图查看器

*[English](README.md) | [中文](README.zh-CN.md)*

![应用图标](assets/icons/icon.png)

## 概述

EAIP中国航图查看器是一款专为航空专业人员和飞行员设计的综合移动应用，用于轻松访问、查看和管理中国空域的电子航空资料汇编(EAIP)数据。这款基于Flutter的应用程序为浏览机场图表、程序和航空相关信息以及实时机场天气数据提供了无缝体验。

## 功能特点

### 核心功能
- **EAIP文档查看**：浏览和查看官方航空图表和程序
- **版本控制**：访问当前和历史EAIP出版物
- **搜索功能**：快速查找特定图表或信息
- **PDF查看**：高质量集成PDF查看器，带有缩放和导航控制

### 天气信息
- **METAR/TAF数据**：机场实时天气报告和预报
- **天气报告翻译**：自动翻译天气报告
- **数据缓存**：智能缓存系统，支持离线访问和减少数据使用
- **最近搜索**：快速访问之前搜索过的机场

### 用户体验
- **响应式UI**：适应不同屏幕尺寸的直观界面
- **暗黑模式支持**：在所有光线条件下舒适查看
- **可折叠侧边栏**：带可调节侧边栏的高效导航
- **PDF管理**：保存、共享和组织PDF文档

### 技术特点
- **自动更新**：内置更新机制，用于应用版本管理
- **离线支持**：无需互联网连接即可访问之前加载的内容
- **文件管理**：高效缓存和存储EAIP文档
- **跨平台**：适用于iOS、Android、macOS和Windows

## 截图

*(这里将添加截图)*

## 安装

### 移动端(iOS和Android)
1. 从App Store(iOS)或Google Play商店(Android)下载应用
2. 或者，对于Android，可以从发布页面下载最新的APK

### 桌面端(Windows和macOS)
1. 从发布页面下载适当的安装程序
2. 运行安装程序并按照屏幕上的说明进行操作

### 开发者
```bash
# 克隆仓库
git clone https://github.com/KNA7022/eaipchinaviewer.git

# 导航到项目目录
cd eaipchinaviewer

# 安装依赖
flutter pub get

# 以调试模式运行应用
flutter run
```

## 使用方法

### 登录
应用需要有效的凭据才能访问EAIP数据库。请联系您的航空管理机构或组织获取访问权限。

### 浏览EAIP文档
1. 登录后，您将看到可用的EAIP版本
2. 选择一个版本浏览其内容
3. 通过层次结构导航查找特定文档
4. 点击文档在集成的PDF查看器中查看

### 天气信息
1. 导航至天气标签页
2. 输入机场的ICAO代码（例如，ZBAA代表北京首都国际机场）
3. 查看当前METAR和TAF数据及其翻译
4. 使用刷新按钮更新天气信息

### 设置
通过以下选项自定义您的体验：
- 主题偏好（亮色/暗色/系统）
- PDF查看选项
- 缓存管理
- 登录偏好

## 隐私与安全

EAIP中国航图查看器包含全面的隐私功能和用户凭据的安全处理。应用需要某些权限以实现最佳功能：

- **互联网访问**：用于下载EAIP数据和天气信息
- **存储访问**：用于保存和管理PDF文档
- **网络状态**：根据连接性调整功能

## 贡献

我们欢迎贡献以改进EAIP中国航图查看器。请随时提交问题或拉取请求。

## 许可证

本项目采用[MIT]许可 - 详情请参阅LICENSE文件。

## 致谢

- 特别感谢所有贡献者和测试人员
- Flutter和Dart团队提供的出色框架
- 所有使这个项目成为可能的第三方库 