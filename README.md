# Kubernetes资源管理GUI工具

一个用于快速调整Kubernetes Deployment和StatefulSet副本数的图形化工具。

## 功能特性
- 🖥️ 图形化界面操作
- 🔄 快速调整副本数
- 🛡️ 输入验证和异常处理
- 💻 跨平台支持

## 技术栈
- Python 3.12.5
- Tkinter (GUI)
- Kubernetes Python Client

## 快速开始
1. 安装依赖：`pip install -r requirements.txt`
2. 配置kubeconfig文件路径
3. 运行：`python k8s_gui_tool.py`

## 使用说明
选择命名空间 → 选择资源类型 → 选择资源名称 → 输入副本数 → 点击确认
