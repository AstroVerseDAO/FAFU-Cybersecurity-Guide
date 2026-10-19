# Web 安全

> 互联网世界最普遍的攻击面，也是 CTF 与就业市场需求最大的方向。校内相关课程为「Web 应用安全」（方向课，黄日茂老师曾开设）。

## 为什么学

- Web 应用无处不在，OWASP Top 10 长期是安全行业的核心清单；
- Web 安全入门门槛相对友好（不需要先啃汇编），适合作为攻防方向的起点；
- 渗透测试、安全研发、安全测试岗位的核心需求。

## 前置知识

- [程序设计基础](../专业基础/程序设计基础.md)（能读懂 HTTP 与前后端代码）
- [计算机网络](../专业基础/计算机网络.md)（HTTP 协议细节）
- [数据库](../专业基础/数据库.md)（SQL 注入的地基）
- [Burp Suite 与 Web 调试](../必学工具/BurpSuite与Web调试.md)

## 核心内容

- HTTP 协议：请求/响应、Cookie/Session、同源策略
- 注入类：SQL 注入、命令注入
- XSS（反射/存储/DOM）与 CSRF
- 文件上传与文件包含（LFI/RFI）
- SSRF、XXE、反序列化
- 越权（水平/垂直）、逻辑漏洞
- 防护视角：输入校验、输出编码、安全头、WAF 概念

## 推荐资源

| 资源 | 类型 | 说明 |
| ---- | ---- | ---- |
| 《白帽子讲 Web 安全》（吴翰清） | 书 | 中文 Web 安全圣经级入门 |
| 《Web 安全深度剖析》 | 书 | 漏洞原理与实践结合 |
| [PortSwigger Web Security Academy](https://portswigger.net/web-security) | 在线课程 | 官方免费，含实验环境，强烈推荐 |
| [OWASP Top 10](https://owasp.org/www-project-top-ten/) | 文档 | 权威漏洞清单 |

## 学习建议

- **原理 + 靶场**并行：每个漏洞先在 DVWA / pikachu / WebGoat 上复现，再看理论；
- 用好 Burp Suite（Repeater + Intruder），练到「闭眼改包」；
- CTF Web 题是很好的进阶练习（题目短、知识点集中）；
- 关注 OWASP Top 10 每年的更新，保持知识不落后。

## 校内对应

- Web 应用安全（方向课）
- 网络攻防技术（第 6 学期，核心课）中的 Web 攻击模块
