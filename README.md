# 福建农林大学网络空间安全专业指南

> 在 GitHub 上读完一个网络空间安全专业的学士学位。
>
> 面向福建农林大学（FAFU）网络空间安全专业学子的开源学习指南：课程地图、四年规划、自学资源与竞赛成长路线，以网页文档形式呈现。

[![license](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## 这是什么

本仓库是一份**以网页形式呈现的开源网络安全学校指南**，参考了北大 [cs-self-learning](https://github.com/pkuflyingpig/cs-self-learning)（CS 自学指南）等优秀高校课程开源项目的组织方式：

- 基于 **MkDocs + Material 主题**构建，Markdown 即内容，自动生成可搜索的文档站点；
- 内容围绕 FAFU 网络空间安全专业真实培养方案组织（专业代码 080911TK，2020 年起招生）；
- 覆盖「必学工具 → 专业基础 → 安全方向 → 实验实践 → 竞赛成长」的完整学习路径。

## 在线阅读

站点部署于 GitHub Pages（启用后访问）：

- https://openfafu.github.io/FAFU-Cybersecurity-Guide/

本地预览：

```bash
pip install -r requirements.txt
mkdocs serve
```

## 目录结构

```
.
├── mkdocs.yml          # 站点配置（导航、主题、插件）
├── requirements.txt    # Python 依赖
├── template.md         # 新增课程页面的统一模板
└── docs/
    ├── index.md        # 前言
    ├── 使用指南.md     # 阅读路径与页面结构说明
    ├── 课程地图.md     # 专业信息与课程体系（源自官方资料）
    ├── 学习规划.md     # 四年学习路线建议
    ├── 必学工具/       # Linux、Git、Kali、Burp、逆向工具链、CTF 平台等
    ├── 专业基础/       # 数学、编程、数据结构、组成、OS、网络、数据库、汇编
    ├── 安全方向/       # 密码学、攻防、Web 安全、逆向、取证、云物联、AI 安全、合规
    ├── 实验与实践/     # 课程设计、实训、安全实验平台
    ├── 竞赛与成长/     # CTF 与竞赛、考研深造、就业认证
    ├── 好书推荐.md
    ├── 贡献指南.md
    └── 后记.md
```

## 参与贡献

任何补充、纠错与建议都欢迎：

- 提 **Issue**：报告链接失效、信息更新、资源推荐；
- 提 **Pull Request**：按 [贡献指南](docs/贡献指南.md) 与 `template.md` 模板新增/修改页面。

## 许可

[MIT](LICENSE) © OpenFAFU

## 免责声明

本指南中校内课程信息整理自学校公开资料，最终以学校教务最新安排为准；推荐资源均为公开知名课程与平台。所有安全技术内容默认仅在授权环境中实践，使用者须遵守相关法律法规（详见 [法律伦理与合规](docs/安全方向/法律伦理与合规.md)）。
