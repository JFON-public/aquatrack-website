# HydroTrack

HydroTrack 是一个全面的饮水追踪应用程序，旨在帮助用户维持适当的水分摄取量、追踪每日液体摄取量，并管理咖啡因摄取。

## 功能

### 核心功能

- **饮水追踪**：记录水和各种饮料，可自定义摄取量
- **个性化目标**：根据个人资料设定自定义目标或获取个性化建议
- **饮料模板**：追踪各种饮料类型，包括水、咖啡、茶、果汁和汽水
- **快速添加**：使用预设容量快速添加常用饮料
- **咖啡因监控**：追踪咖啡因摄取量并设定每日限制
- **长者模式**：为年长用户提供的简化界面选项

### 提醒功能

- **排程提醒**：在特定时间设定提醒（早上、中午、下午）
- **间隔提醒**：基于时间间隔的替代提醒系统
- **智能通知**：帮助用户保持水分摄取目标

### 统计与分析

- **每日/每周/每月统计**：查看水分摄取趋势
- **进度可视化**：每日目标进度的视觉呈现
- **饮料历史记录**：完整记录所有饮料记录，并提供筛选选项

### 个性化设置

- **单位偏好**：选择公制（毫升）或英制（盎司）单位
- **外观设置**：浅色模式、深色模式或系统默认
- **自定义饮料模板**：创建和管理自定义饮料类型
- **容量预设**：自定义常用容量以快速输入

### 入门指南

- **引导式设置**：逐步介绍应用程序功能
- **个性化建议**：根据用户资料提供初始饮水目标

## 数据模型

### 用户设置

- 每日饮水目标（毫升）
- 每日咖啡因限制（毫克）
- 提醒偏好设置
- 个人指标（性别、体重、活动水平）
- 显示偏好（单位、外观）
- 更多自定义选项

### 饮料模板

- 预设和自定义饮料类型
- 名称、图标和颜色自定义
- 每毫升咖啡因含量

### 饮料记录

- 记录的饮料摄取
- 摄取量
- 时间戳记
- 相关饮料模板

## 用户界面

### 主要标签

1. **首页**：显示每日进度的主仪表板
2. **统计**：详细统计资料和可视化
3. **添加饮料**：快速添加新饮料记录
4. **提醒**：设定和管理饮水提醒
5. **设置**：应用程序配置和偏好设置

### 特殊模式

- **长者模式**：为年长用户提供的简化界面，元素较大

## 技术实现

- 使用 SwiftUI 为 iOS 开发
- 使用 SwiftData 进行持久化存储
- 采用 MVVM 架构
- 支持本地化
- 整合天气信息以提供饮水建议

## 开始使用

1. 完成入门流程
2. 设定个人饮水目标
3. 配置提醒以保持进度
4. 开始记录您的饮料摄取！

## 隐私与数据

- 所有数据都存储在您的设备上
- 不会将个人信息传输到外部服务器
