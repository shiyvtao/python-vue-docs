# flask——文档

###### 文档链接

* [官网](https://flask.palletsprojects.com/en/2.3.x/ "传送到官网")[https://flask.palletsprojects.com/en/2.3.x/]
* [GitHUb](https://github.com/pallets/flask "传送到GitHub首页")[https://github.com/pallets/flask]
* [Flask中文网](https://flask.net.cn/ "传送到Flask中文网")[https://flask.net.cn/]——更新不及时

---

##### 下载及其插件下载

flask下载

```
pip install flask
```

---

##### 方法

1. 添加路由
   ```python
   from flask import Flask

   app = Flask(__name__)

   @app.route("/index", methods=["GET", "POST"])
   def index():
    return "Hello"
   ```
2. class模式使用
   ```python
   from flask import views
   class BaseApiCls(views.MethodView):
       def __init__(self):
          # 在此配置服务
          # sele.db = 
       def get(self, *args, **kwargs):
          return "这是GET请求"
       def get(self, *args, **kwargs):
          return "这是POST请求"
   ```
##### 错误

1. xxxx

   关键字:[]

   链接: []

   错误解决
2. XXX
