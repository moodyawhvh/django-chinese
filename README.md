<div align="center">

# django 中文翻译版

**[中文版] django — 面向"赶工期完美主义者"的 Python Web 框架**

[![原项目](https://img.shields.io/badge/原项目-django--django-blue?style=flat-square&logo=github)](https://github.com/django/django)
[![中文文档](https://img.shields.io/badge/中文文档-README.zh--CN.md-orange?style=flat-square)](README.zh-CN.md)
[![GitHub Stars](https://img.shields.io/github/stars/django/django?style=flat-square&label=原项目Stars)](https://github.com/django/django/stargazers)
[![微信联系](https://img.shields.io/badge/微信-uaycar-brightgreen?style=flat-square&logo=wechat)](#)

</div>

---

> 这是 [django/django](https://github.com/django/django) 的中文翻译版本。
> 完整源代码请访问原项目:https://github.com/django/django

**代部署 / 定制服务 / 技术咨询 请添加微信:uaycar**

---

## 📖 项目简介

Django 是一个高阶 Python Web 框架,倡导快速开发与干净、务实的设计理念,官方口号是"给带着截止日期的完美主义者的 Web 框架"。它内置 ORM、模板引擎、表单系统、认证授权与自动化管理后台,几乎覆盖 Web 开发全流程,让你把精力集中在业务本身。全球大量知名网站与 API 服务都构建在 Django 之上,社区成熟、文档严谨、生态极其丰富。它由经验丰富的开发者社区长期维护,版本迭代稳定、升级路径清晰,从个人小项目到大型平台都值得信赖。Django 遵循"约定优于配置"的思路,大量通用需求默认即可用,新手不必在繁杂配置上浪费时间,老手也能深度定制每个环节。本仓库是其官方 README 的中文翻译介绍版本,方便中文开发者快速了解与上手。

## ✨ 主要特性

- **极速开发**:组件开箱即用,几分钟就能搭起可运行的应用骨架,管理后台还能按数据模型自动生成。
- **干净务实的设计**:分层清晰、风格务实,项目从小做到大、长期维护都不失控。
- **强大 ORM**:用 Python 描述数据模型,自动完成建表、迁移与查询,配合迁移脚本让数据库演进全程可控。
- **模板引擎**:可继承、可复用的模板系统,与 ORM、表单无缝配合,页面开发省时省力。
- **认证与权限**:内置用户、分组、权限与会话体系,安全省心。
- **安全防护开箱即用**:默认防御 CSRF、XSS、SQL 注入、点击劫持等常见攻击。
- **国际化与本地化**:多语言、时区与本地格式支持完善,适合全球项目。
- **文档与社区**:官方文档严谨,Discord 社区与官方论坛活跃。
- **BSD 许可证**:免费开源,商用友好,可放心用于生产环境。

## 📁 文件说明

| 文件 | 说明 |
|:-----|:-----|
| README.md | 本文件(中文简介) |
| README.zh-CN.md | 详细中文文档(完整汉化) |

## 🚀 快速开始

**1. 确认环境:**

需要已安装 Python 3.10+(以官方文档要求为准),命令行执行 `python --version` 可验证。

**2. 安装 Django(推荐先创建虚拟环境):**

```bash
python -m pip install Django
```

**3. 创建项目:**

```bash
django-admin startproject mysite
```

**4. 启动开发服务器:**

```bash
cd mysite
python manage.py runserver
```

浏览器打开 http://127.0.0.1:8000/ 即可看到欢迎页。

**5. 按官方推荐顺序阅读文档:**

先读安装指南,再按顺序过一遍入门教程,然后通读主题指南(docs/topics),遇到具体问题查 HOWTO(docs/howto)与参考手册(docs/ref)。

**6. 部署到生产环境:**

参考官方部署指南 `docs/howto/deployment/`,涵盖 WSGI/ASGI、静态文件与安全加固等完整流程。初学者可先用 `runserver` 体验,生产环境建议搭配 Nginx/Gunicorn 或云平台容器方案。

**7. 运行测试套件:**

```bash
python runtests.py
```

**8. 获取更多帮助:**

加入 Django Discord 社区(https://chat.djangoproject.com)或官方论坛(https://forum.djangoproject.com/)。

完整源代码与最新版本请访问原项目:https://github.com/django/django

## 📞 联系方式

**代部署 / 定制服务 / 技术咨询 请添加微信:uaycar**

---

本项目为 [django/django](https://github.com/django/django) 的中文翻译版本,所有代码版权归原项目作者所有,遵循其原始许可证。

**如果觉得有用,请给原项目点个 Star!** ⭐
