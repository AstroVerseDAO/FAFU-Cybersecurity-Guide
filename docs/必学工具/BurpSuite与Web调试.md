# Burp Suite 与 Web 调试

> Web 安全测试的事实标准工具。抓包改包、扫描、重放，Web 攻防方向的一切实验都从 Burp Suite 开始。

## 为什么学

- 校内「Web 应用安全 / 网络攻防技术」与校外 CTF-Web 方向的核心工具；
- 理解 HTTP 请求/响应是 Web 安全的地基，Burp 是观察与修改它的最佳入口。

## 核心功能

- **Proxy（代理）**：浏览器流量经过 Burp，可拦截、查看、修改；
- **Repeater**：手动修改并重放请求（漏洞验证主力）；
- **Intruder**：自动化爆破 / 枚举；
- **Decoder / Comparer**：编码解码与报文比对；
- **Scanner（专业版）**：自动漏洞扫描（社区版功能受限）。

## 入门路径

1. 安装 Burp Suite Community（[PortSwigger 官网](https://portswigger.net/burp)），配置浏览器代理（或用 Burp 自带浏览器）；
2. 学会用 Proxy 拦截并修改一个请求（改参数、改 Cookie）；
3. 用 Repeater 重放，观察服务器响应变化；
4. 到 [PortSwigger Web Security Academy](https://portswigger.net/web-security) 练手——免费、系统、含实验环境的官方课程。

## 学习建议

- Web 安全方向的学习顺序：**HTTP 基础 → Burp 熟练 → OWASP Top 10 → 漏洞靶场 → 真实目标**；
- 靶场建议：DVWA、pikachu、[WebGoat](https://github.com/WebGoat/WebGoat)（见 [安全实验平台](../实验与实践/安全实验平台.md)）；
- Burp 的英文界面别怕，核心菜单就几个，用两天就熟了。

## 合规提醒

!!! warning
    Burp 的拦截与改包能力只可用于**授权目标**（课程实验、CTF 平台、自建靶场、签署了授权协议的测试）。
