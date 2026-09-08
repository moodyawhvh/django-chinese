> 🌐 本文档由 [django/django](https://github.com/django/django) 翻译,英文原版见原项目。

运行测试套件:先创建并激活一个虚拟环境,然后安装若干依赖并运行测试::

    $ cd tests
    $ python -m pip install -e ..
    $ python -m pip install -r requirements/py3.txt
    $ ./runtests.py

关于测试套件的更多信息,请参见
https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/。
