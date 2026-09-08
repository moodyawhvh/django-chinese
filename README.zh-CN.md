<div align="center">

# django 中文文档

[![原项目](https://img.shields.io/badge/原项目-django--django-blue?style=flat-square&logo=github)](https://github.com/django/django)
[![微信联系](https://img.shields.io/badge/微信-uaycar-brightgreen?style=flat-square&logo=wechat)](#)

**[中文版] django — 面向"赶工期完美主义者"的 Python Web 框架**

本仓库是 [django/django](https://github.com/django/django) 官方 README 的中文翻译版本,仅供学习交流。

**代部署 / 定制服务 / 技术咨询 请添加微信:uaycar**

</div>

---

## Django 是什么

Django 是一个高阶 Python Web 框架,倡导快速开发与干净、务实的设计。感谢你关注本项目。

## 📚 文档阅读指南(官方推荐顺序)

所有文档位于仓库的 "docs" 目录,同时提供在线版本:https://docs.djangoproject.com/en/stable/ 。如果你刚刚上手,官方建议按下面的顺序阅读:(译注:初学者直接读在线文档更方便,建议边读边动手练习。)

* 首先,阅读 ``docs/intro/install.txt``,了解 Django 的安装步骤。

* 接着,按顺序完成入门教程(``docs/intro/tutorial01.txt``、``docs/intro/tutorial02.txt`` 等)。

* 如果你要搭建真实的生产部署服务器,阅读 ``docs/howto/deployment/index.txt`` 获取部署指引。

* 之后建议通读主题指南(docs/topics 目录);遇到具体问题可跳转到 HOWTO 文档(docs/howto 目录),需要细节时查阅参考手册(docs/ref 目录)。

* 关于如何构建 HTML 版本文档,参见 ``docs/README`` 的说明。

文档会持续严格更新。如果你发现文档有问题,或认为某些地方需要进一步澄清,请花 30 秒填写一个工单:https://code.djangoproject.com/newticket 。你可以使用 GitHub 账号登录,如果已有 DjangoProject 账号也可以直接使用。登录后,在 View Tickets 旁边即可看到 New Ticket 按钮。

## 💬 获取更多帮助

* 加入 Django Discord 社区:https://chat.djangoproject.com

* 加入 Django 官方论坛社区:https://forum.djangoproject.com/

## 🤝 参与贡献 Django

* 访问 https://docs.djangoproject.com/en/dev/internals/contributing/ ,了解如何参与项目贡献。

## 🧪 运行 Django 测试套件

* 按照 ``docs/internals/contributing/writing-code/unit-tests.txt`` 中 "Unit tests" 一节的说明操作,在线版本见:https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/#running-the-unit-tests

## ❤️ 支持 Django 的发展

Django 的发展离不开社区的贡献。

如果你的项目依赖 Django,请记得支持 Django 软件基金会(Django Software Foundation):https://www.djangoproject.com/fundraising/

## ⚙️ 安装与快速上手(译注补充)

以下为方便中文读者补充的最小上手流程,完整说明以官方文档为准。建议先创建虚拟环境(``python -m venv venv``)并激活,避免污染系统 Python 环境:

```bash
python -m pip install Django
```

```bash
django-admin startproject mysite
cd mysite
python manage.py runserver
```

浏览器打开 http://127.0.0.1:8000/ ,看到欢迎页即安装成功。之后按上文"文档阅读指南"中官方推荐的顺序,从安装文档与入门教程读起即可。

## 🔗 相关资源

* 官方网站:https://www.djangoproject.com/

* 在线文档(稳定版):https://docs.djangoproject.com/en/stable/

* 源代码仓库:https://github.com/django/django

* 版本下载与发行说明:https://www.djangoproject.com/download/

---

## 📄 版权与声明

- 本文档是 [django/django](https://github.com/django/django) 官方 README 的中文翻译版本,仅供中文开发者学习交流使用。
- 所有代码与原始文档版权归 Django 软件基金会及原项目作者所有,遵循其原始许可证(BSD)。
- 完整源代码与最新版本请访问原项目:https://github.com/django/django
- **代部署 / 定制服务 / 技术咨询 请添加微信:uaycar**
- **如果觉得有用,请给原项目点个 Star!** ⭐
