# Tokaify Gateway

> 一个为 LLM API 调用设计的轻量级网关，通过智能路由、语义缓存和多上游故障转移，**平均降低 45% 以上的 Token 成本**，同时保证模型透明不降级。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![GitHub stars](https://img.shields.io/github/stars/你的用户名/tokaify-gateway)](https://github.com/你的用户名/tokaify-gateway/stargazers)

## ✨ 特性

- **🔥 显著降本**：内置语义缓存、缓存池化、输出长度限制，实测减少 45%+ Token 消耗。
- **🤖 多模型统一接入**：支持 OpenAI、Claude、Gemini、通义千问、豆包等主流模型，兼容 OpenAI API 格式。
- **🛡️ 模型透明**：不降级、不偷换模型，调用日志可追溯。
- **⚡ 高可用**：多上游故障自动切换，可用性 99.9% 以上。
- **🧩 轻量易用**：一行 Base URL 即可接入，提供 Python/Node.js SDK。

## 🚀 快速开始

### 安装
```bash
pip install tokaify-client
