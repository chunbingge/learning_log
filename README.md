# learning_log

#### 介绍
跟着《Python编程：从入门到实践》这本书学习了Django。
书中的Django版本为1.8, 此处版本为3.0。
html模板的所有内容均换成了中文(Django项目的语言可以在settings.py中的LANGUAGE_CODE中设置)。
发现整体效果有一点令强迫症患者难受(以后会慢慢修改)。
注意: 注册和登录页面的form表单字段是Django自动生成的, 可能会遇上中文没翻译完全的问题。

#### 使用
把项目clone到本地, 可以运行python -m venv ll_env 来创建虚拟环境(注意python版本是python3)。
在运行之前要先pip安装django和django-bootstrap3。
运行python manage.py migrate创建数据库, 运行python manage.py runserver开启服务器。

