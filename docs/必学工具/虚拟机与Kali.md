# 虚拟机与 Kali

> 安全人的「移动实验室」。Kali Linux 是业内最知名的渗透测试发行版，内置数百款安全工具，配合虚拟机使用可以随时搭建 / 销毁实验环境。

## 为什么学

- 校内实训（网络攻防、操作系统安全）和校外 CTF、渗透练习都围绕 Linux 安全环境展开；
- 虚拟机（VirtualBox / VMware）提供**隔离 + 快照**能力：环境搞坏了随时回滚，做攻击实验不污染日常系统；
- Kali 预装 Nmap、Metasploit、Burp Suite、Wireshark 等主流工具，省去逐个安装。

## 入门路径

1. **安装虚拟机软件**：VirtualBox（免费开源）或 VMware Workstation Player（免费个人版）；
2. **安装 Kali**：从 [Kali 官网](https://www.kali.org/) 下载镜像安装，或直接使用官方提供的 VirtualBox 镜像；
3. **搭一套靶场**：在同一虚拟网络中架设 Metasploitable 2 / DVWA 等靶机（见 [安全实验平台](../实验与实践/安全实验平台.md)）；
4. 学会用**快照**：每次实验前打快照，翻车一键还原。

## 常用工具速览（Kali 内置）

| 类别 | 工具 |
| ---- | ---- |
| 信息收集 | Nmap、masscan、theHarvester |
| 漏洞利用 | Metasploit Framework、SearchSploit |
| Web 安全 | Burp Suite（社区版）、sqlmap、nikto、dirb |
| 密码攻击 | Hydra、John the Ripper、hashcat |
| 网络分析 | Wireshark、tcpdump、nmap 脚本 |
| 逆向 / 调试 | GDB、radare2 / Ghidra |

## 学习建议

- 先系统学 [Linux 与命令行](Linux.md)，再玩 Kali，事半功倍；
- **只在授权环境使用**这些工具——校内实训平台、自建靶场、CTF 平台都可以，未授权目标绝对不行；
- 不要只「装个 Kali 看看」，要带着任务用：完成一次「信息收集 → 漏洞发现 → 利用 → 报告」的全流程。

## 合规提醒

::: warning
  Kali 及其工具集是双刃剑。请严格遵守 [网络安全法律与伦理](../安全方向/法律伦理与合规.md) 的要求，任何未授权扫描与攻击行为都涉嫌违法。
:::
