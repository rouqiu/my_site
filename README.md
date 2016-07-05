# my_site
Django+Bootstrap搭建的简易个人博客
1.后台使用Bootstrap-admin
2.实现文章按月归档
5.实现文章分类,标签
3.采用第三方评论:多说
4.引入微博秀
5.采用JQcloud实现标签云功能
6.后台引入TinyMce富文本编辑器,前端使用SyntaxHighlighter进行代码高亮
7.引入站长统计以及访问统计

安装步骤
1、pip install -r requirements.txt
2、pip install django-tinymce

运行
python manage.py runserver 0.0.0.0:8000

创建超级用户（管理用户）
python manage.py createsuperuser
按提示输入信息，完成管理员用户创建

后台管理入口
.../admin
比如：http:127.0.0.1:8000/admin


