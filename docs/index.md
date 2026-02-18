# OpenViking 项目解析系列

![OpenViking](https://raw.githubusercontent.com/volcengine/OpenViking/main/docs/images/banner.jpg)

## 系列简介

本系列旨在帮助你从零开始，逐步理解 OpenViking 这一为 AI Agent 设计的上下文数据库项目。

> **OpenViking** 是字节跳动火山引擎 Viking 团队开源的上下文数据库，专门为 AI Agent 设计，用于统一管理记忆、知识资源和技能。

## 为什么学习 OpenViking？

| 痛点 | OpenViking 解决方案 |
|------|---------------------|
| 碎片化存储 | 虚拟文件系统统一管理 |
| 检索不精准 | 目录递归检索 + Rerank |
| Token 浪费 | L0/L1/L2 三层按需加载 |
| 记忆难迭代 | 自动提取，长期记忆 |
| 检索黑盒 | 可视化检索轨迹 |

## 文档结构

### 📚 入门认知

建立整体认知，了解 OpenViking 是什么、能做什么。

- [01-项目是什么](01-项目是什么.md) - 定位、核心理念
- [02-快速体验](02-快速体验.md) - 5 分钟上手示例

### 🧠 核心概念

理解 OpenViking 的三大核心抽象和信息模型。

- [03-三大核心抽象](03-三大核心抽象.md) - Resource/Memory/Skill
- [04-三层信息模型](04-三层信息模型.md) - L0/L1/L2
- [05-虚拟文件系统](05-虚拟文件系统.md) - Viking URI

### 🏗️ 架构设计

深入系统内部，理解各模块如何协同工作。

- [06-系统架构总览](06-系统架构总览.md) - 模块划分
- [07-双层存储架构](07-双层存储架构.md) - AGFS + 向量库
- [08-检索机制详解](08-检索机制详解.md) - 意图分析、递归检索、Rerank
- [09-会话与记忆管理](09-会话与记忆管理.md) - 会话生命周期

### 🚀 高级特性

了解部署方式和扩展能力。

- [10-自动记忆迭代](10-自动记忆迭代.md) - 记忆自进化
- [11-部署模式与扩展](11-部署模式与扩展.md) - 嵌入式/HTTP 模式

## 快速开始

```bash
# 1. 克隆文档仓库
git clone https://github.com/hilaily/openviking.git
cd openviking

# 2. 安装 MkDocs
pip install mkdocs mkdocs-material

# 3. 本地预览
mkdocs serve
# 访问 http://localhost:8000
```

## 参考资源

- [官方文档](https://www.openviking.ai/docs)
- [GitHub 仓库](https://github.com/volcengine/OpenViking)
- [官网](https://www.openviking.ai)

---

*本系列文档由 OpenClaw 生成*
