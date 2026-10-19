# Linux 与命令行

> 网络安全从业者的第一生产力。攻防两端的工作几乎都发生在 Linux 环境（服务器、靶场、Kali、云主机），不会命令行等于没有手。

## 为什么学

- 主流安全工具（Nmap、Metasploit、Burp、Wireshark、GDB 等）的原生环境都是 Linux；
- 渗透测试、运维排查、日志分析的核心场景全在终端；
- 学校课程（操作系统及安全、网络攻防技术）的实验环境大量使用 Linux。

## 入门路径

1. **装一个 Linux**：推荐先装虚拟机里的 Ubuntu Desktop（见 [虚拟机与 Kali](虚拟机与Kali.md)），别怕折腾；
2. **过一遍命令行基础**：文件系统、权限、进程、管道、重定向、常用命令（`ls` `cd` `grep` `find` `ps` `netstat` `ssh` `scp` 等）；
3. **会写 Shell 脚本**：把重复操作脚本化。

## 推荐资源

| 资源 | 类型 | 说明 |
| ---- | ---- | ---- |
| 《鸟哥的 Linux 私房菜》 | 书 | 中文 Linux 经典入门，基础篇足够 |
| [Linux Journey](https://linuxjourney.com/) | 网站 | 交互式入门教程，节奏友好 |
| [missing-semester（MIT）](https://missing.csail.mit.edu/) | 公开课 | 「命令行 + 编辑器 + 版本控制」一网打尽，中文翻译在 [missing-semester-cn](https://missing-semester-cn.github.io/) |
| [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) | 闯关 | 用游戏方式练 SSH 与命令行 |

## 核心技能清单

- 文件与权限：`chmod` / `chown` / 软硬链接
- 文本处理：`grep` / `awk` / `sed` / `cut` / `sort` / `uniq`
- 进程与端口：`ps` / `top` / `netstat` / `ss` / `lsof`
- 网络：`ssh` / `scp` / `curl` / `wget` / `nc`（netcat）
- 日志：`/var/log` 常见日志、`tail -f`、`journalctl`

## 学习建议

- **别背命令**，遇到就查 `man` / `--help` / `tldr`；
- 把「折腾环境」当学习本身：装坏一次系统，就多会一点；
- 大二前把基础过完，大三学攻防时直接进入战斗状态。
