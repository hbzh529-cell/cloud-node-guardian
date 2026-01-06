# Cloud Node Guardian (CNG)

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Cloud Native](https://img.shields.io/badge/Cloud%20Native-Ready-orange)

**Cloud Node Guardian** 是一个轻量级的、基于异步 IO (`asyncio`) 的云服务器节点监控与自愈代理。专为高并发分布式环境设计。

## ✨ 主要特性 (Features)

- **非阻塞式 I/O**: 基于 Python 协程实现，极低的资源占用。
- **智能自愈**: 检测到 CPU/内存异常时自动触发 Webhook 进行弹性扩容。
- **多云支持**: 兼容 Huawei Cloud, AWS, AliCloud 实例元数据。

## 🚀 快速开始

```bash
# 启动守护进程
python main.py
