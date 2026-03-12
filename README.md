# qianshou.app 🌏 全平台统一客户端

qianshou.app (伸手.app) 是 local-agent-relay 的官方跨平台客户端 📱

## 简介 📖

支持 iOS 🍎 Android 🤖 Windows 🪟 Linux 🐧 macOS 🍎

双模设计 🧠 → 脑 (管理) + 手 (执行) 🦾

## 特性 ✨

### Controller 控制模块 🖥️
- 节点列表 📋
- 实时日志 📊
- 任务下发 📤

### Agent Core 执行模块 ⚙️
- WSS 连接 🔗
- Token 认证 🔐
- 工具调用 🛠️

### 配对 🤝
- 扫码 📱
- 手动 ⌨️

## 技术栈 🛠️

Flutter + web_socket_channel + Riverpod

## 快速开始 🚀

```bash
git clone https://github.com/cokeisnotbest/qianshou.app.git
cd qianshou.app
flutter pub get
flutter run
```

## 结构 📂

lib/
├── core/
├── features/
├── shared/
└── main.dart

## 移动端适配 📱

iOS → Shortcuts API 🍎
Android → Shell 执行 🤖

## 许可证 📄

MIT © 2024

## 联系 📧

Issues: https://github.com/cokeisnotbest/qianshou.app/issues
