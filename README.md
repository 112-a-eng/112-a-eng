# Hi, I'm 112-a-eng 👋

自己写的小工具和小游戏都放在这里。风格基本一致：**从零手写、尽量零第三方依赖、带测试、带实测记录**。

---

## 🛠️ Windows 常用指令集 · [win-toolkit](https://github.com/112-a-eng/win-toolkit)

[![Release](https://img.shields.io/github/v/release/112-a-eng/win-toolkit?label=release)](https://github.com/112-a-eng/win-toolkit/releases/latest)
[![Build EXE](https://github.com/112-a-eng/win-toolkit/actions/workflows/build-exe.yml/badge.svg)](https://github.com/112-a-eng/win-toolkit/actions/workflows/build-exe.yml)
[![License](https://img.shields.io/github/license/112-a-eng/win-toolkit)](https://github.com/112-a-eng/win-toolkit/blob/main/LICENSE)

给 Windows 用户的一套「命令行 + 图形界面」工具包，纯 PowerShell + WinForms 实现，零第三方依赖。

| 组成 | 内容 |
| --- | --- |
| 📖 速查手册 | 19 章：文件目录 / 系统信息 / 进程服务 / 网络排查 / 磁盘修复 / 注册表组策略 / 计划任务 / winget / 电源 / 远程 / 文本处理 / 批处理语法 / 常见故障一条命令修 |
| 🧰 9 个脚本 | 系统信息、网络诊断、端口占用、临时清理、robocopy 备份、进程服务速查、大文件查找、批量重命名、控制台菜单 |
| 🖥️ 图形工具台 | WinForms 界面：任务在独立 Runspace 执行、输出实时彩色回显、危险操作二次确认 |
| 📦 单文件 EXE | 141 KB，内嵌全部脚本与图标，双击即用，不改执行策略 |

**下载**：[Releases](https://github.com/112-a-eng/win-toolkit/releases/latest) ｜ **安装**：`winget install 112-a-eng.WinToolkit`

---

## 🎮 小游戏合集 · [dsh-games](https://github.com/112-a-eng/dsh-games)

五个从零手写的完整游戏，技术栈各不相同 —— 都能直接玩（含手机 APK），也都有单元测试和打包脚本。

| 项目 | 技术栈 | 亮点 |
| --- | --- | --- |
| 💎 宝石三消（Android） | Java + 原生 Android SDK | 45 KB APK、零权限、21.9 万项断言 |
| 📱 2048（Android） | Java + 原生 Android SDK | 33 KB APK、零权限、手工 javac + aapt2 + d8 出包 |
| 🎮 扫雷 | C++20 + 原生 Win32/GDI | 零第三方依赖、零图片资源（图标/数码管/笑脸全是代码画的）、441 万项断言 |
| 📈 股票模拟交易 | Python + tkinter | 贴近 A 股实盘：涨跌停 / T+1 / 佣金印花税 / 滑点 / 限价挂单 / 部分成交 / 融资强平 |
| 🧱 俄罗斯方块 | Python + tkinter | 60FPS 增量渲染、幽灵落点、Hold、7-bag 随机、自绘 DAS/ARR 连发手感 |

---

📫 有问题直接开 Issue，我都会看。