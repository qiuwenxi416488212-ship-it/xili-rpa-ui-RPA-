# XiLi RPA
## 智能RPA自动化采集系统

<p align="center">
  <img src="https://img.shields.io/github/stars/XiLi/xili-rpa-ui" alt="Stars">
  <img src="https://img.shields.io/github/license/XiLi/xili-rpa-ui" alt="License">
  <img src="https://img.shields.io/badge/HTML5-CSS3-blue" alt="HTML">
  <img src="https://img.shields.io/badge/前端-RPA-orange" alt="RPA">
</p>

---

## 📦 项目简介

**XiLi RPA** (犀利RPA) 是一套专业的智能RPA自动化采集系统,提供可视化配置界面的网页数据采集工具,帮助用户快速构建自动化采集流程。

> **犀利**,让你的数据采集更简单!

## 🎯 核心功能

| 功能 | 说明 |
|------|------|
| 📊 **仪表盘** | 数据统计可视化,实时展示采集状态 |
| 🕷️ **任务管理** | 创建、编辑、启动、停止采集任务 |
| 📥 **数据采集** | 自动化网页数据抓取 |
| 🗄️ **数据源管理** | 管理采集数据源和目标 |
| 🎨 **可视化配置** | 可视化配置采集规则 |
| 📝 **模板管理** | 预置采集模板,快速上手 |
| 📤 **输出管理** | 数据导出格式配置 |
| ⚙️ **系统设置** | 系统参数配置 |
| 🛡️ **反爬策略** | 反爬虫策略配置 |

---

## 🏗️ 系统架构

```
┌─────────────────────────────────────────────────────────┐
│                    XiLi RPA 系统                         │
├─────────────────────────────────────────────────────────┤
│                                                          │
│  ┌──────────────────────────────────────────────────┐  │
│  │                   Web UI 层                       │  │
│  │  (HTML/CSS/JavaScript 可视化界面)                 │  │
│  ├──────────────────────────────────────────────────┤  │
│  │   index.html      - 首页/仪表盘                   │  │
│  │   tasks.html      - 任务管理                      │  │
│  │   collector.html  - 数据采集                      │  │
│  │   datasources.html - 数据源管理                   │  │
│  │   visual_config.html - 可视化配置                  │  │
│  │   templates.html  - 模板管理                      │  │
│  │   output.html     - 输出管理                      │  │
│  │   settings.html   - 系统设置                      │  │
│  │   anti_crawl.html - 反爬策略                      │  │
│  │   dashboard.html  - 统计仪表盘                    │  │
│  └──────────────────────────────────────────────────┘  │
│                                                          │
│  ┌──────────────────────────────────────────────────┐  │
│  │                   后端服务层                       │  │
│  │   (Python/Node.js RPA 引擎)                       │  │
│  └──────────────────────────────────────────────────┘  │
│                                                          │
└─────────────────────────────────────────────────────────┘
```

---

## 📂 项目文件

| 文件 | 功能 |
|------|------|
| index.html | 首页仪表盘,总览统计 |
| tasks.html | 任务管理,创建编辑任务 |
| collector.html | 数据采集核心页面 |
| datasources.html | 数据源配置管理 |
| visual_config.html | 可视化规则配置 |
| templates.html | 采集模板管理 |
| output.html | 数据输出格式配置 |
| settings.html | 系统设置 |
| anti_crawl.html | 反爬虫策略配置 |
| dashboard.html | 数据统计图表 |

---

## 🚀 快速开始

### 前置要求

- 现代浏览器 (Chrome/Edge/Firefox)
- 后端RPA服务 (可选,纯前端可预览)

### 使用方式

#### 方式1: 直接打开
```bash
# 在浏览器中打开
D:\aXi\xili_rpa\ui\index.html
```

#### 方式2: 本地服务器
```bash
# 使用Python启动简单服务器
cd D:\aXi\xili_rpa\ui
python -m http.server 8080
# 访问 http://localhost:8080
```

#### 方式3: 部署到Web服务器
将 ui 文件夹部署到 Nginx/Apache 后访问

---

## 📊 页面功能详解

### 1. 首页仪表盘 (index.html)
- 系统运行状态
- 任务统计概览
- 采集数据统计
- 最近活动记录

### 2. 任务管理 (tasks.html)
- 新建采集任务
- 编辑任务配置
- 启动/暂停任务
- 任务日志查看

### 3. 数据采集 (collector.html)
- 实时采集监控
- 采集进度展示
- 错误日志

### 4. 数据源管理 (datasources.html)
- 添加数据源
- 配置采集URL
- 设置采集规则
- 测试数据源

### 5. 可视化配置 (visual_config.html)
- 拖拽式配置
- 元素选择器
- 数据字段映射
- 规则预览

### 6. 模板管理 (templates.html)
- 预置采集模板
- 模板导入/导出
- 模板分类

### 7. 输出管理 (output.html)
- JSON输出
- CSV输出
- Excel输出
- 数据库导出

### 8. 系统设置 (settings.html)
- 采集并发数
- 请求间隔
- 超时设置
- 代理配置

### 9. 反爬策略 (anti_crawl.html)
- User-Agent轮换
- IP代理池
- 请求频率限制
- 验证码处理

---

## 🛠️ 技术特点

### 前端技术
- HTML5 + CSS3
- JavaScript (ES6+)
- 响应式设计
- 深色主题UI

### 功能特性
- 🎨 深色专业界面
- 📱 响应式布局
- ⚡ 高性能
- 🔒 安全可靠

---

## 📁 项目结构

```
xili_rpa_ui/
├── index.html           # 首页仪表盘
├── tasks.html           # 任务管理
├── collector.html       # 数据采集
├── datasources.html     # 数据源管理
├── visual_config.html   # 可视化配置
├── templates.html       # 模板管理
├── output.html          # 输出管理
├── settings.html        # 系统设置
├── anti_crawl.html      # 反爬策略
└── dashboard.html       # 统计仪表盘
```

---

## 🤝 使用场景

| 场景 | 说明 |
|------|------|
| 📰 **新闻采集** | 定时采集新闻资讯 |
| 🛒 **电商监控** | 商品价格监控 |
| 📊 **数据汇总** | 多源数据聚合 |
| 📋 **报表生成** | 自动化报表制作 |
| 🔍 **舆情监控** | 舆情数据采集 |

---

## 📄 许可证

MIT License - 免费商用

---

## 🙏 致谢

感谢使用 XiLi RPA!

---

<div align="center">

**犀利 - 让数据采集变得更简单**

Made with ❤️ by XiLi

</div>