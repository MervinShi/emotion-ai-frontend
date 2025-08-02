# 情感支持AI前端应用

这是一个基于React的情感支持AI前端应用，能够与情感大模型进行交互，并展示相关的心理干预策略。

## 功能特点

- 实时聊天功能，支持上下文对话
- 基于用户情绪的个性化干预策略推荐
- 响应式设计，适配各种设备
- 简单直观的用户界面

## 技术栈

- React.js - 前端框架
- Redux Toolkit - 状态管理
- Axios - API请求
- CSS - 样式设计

## 快速开始

### 前提条件

- Node.js (v14+) 和 npm 安装在您的计算机上

### 安装步骤

1. 克隆此仓库
git clone https://github.com/yourusername/emotion-ai-frontend.git
cd emotion-ai-frontend

2. 安装依赖
npm install

3. 启动开发服务器
npm start


4. 在浏览器中访问 `http://localhost:3000`

## 项目结构

- `src/components` - 包含所有React组件
- `Chat` - 聊天相关组件
- `InterventionCards` - 干预策略卡片组件
- `Layout` - 布局组件（头部、底部）
- `src/redux` - Redux状态管理相关文件
- `src/services` - API服务和请求封装
- `public` - 静态资源

## API集成

该应用假设后端API已经可用，主要调用以下接口：

- `/api/chat` - 发送聊天消息并获取回复
- `/api/interventions` - 获取推荐的干预策略
- `/api/feedback` - 提交干预策略的反馈

您可以在 `.env` 文件中配置API基础地址：
REACT_APP_API_URL=http://your-api-base-url



## 注意事项

- 本应用仅为前端实现，需要后端API支持才能完全运行
- 对于生产环境，建议进行进一步的优化和测试