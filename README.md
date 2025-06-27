## 服务启动
`python manage.py runserver`启动服务

## 账号创建
`python manage.py createsuperuser`创建管理员账号


## 迁移命令
`python manage.py makemigrations polls`用于生成迁移文件`polls/migrations/0001_initial.py`

`python manage.py sqlmigrate polls 0001`用于显示迁移文件`polls/migrations/0001_initial.py`的SQL语句

`python manage.py check`用于检查项目

`python manage.py migrate`用于执行迁移文件`polls/migrations/0001_initial.py`