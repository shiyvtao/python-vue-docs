# FastApi——文档

###### 文档链接

* [官网（中文）](https://fastapi.tiangolo.com/zh/ "传送到官网（中文）")[https://fastapi.tiangolo.com/zh/]
* [GitHUb](https://github.com/tiangolo/fastapi "传送到GitHub首页")[https://github.com/tiangolo/fastapi]

---

##### 下载及其插件下载

FastApi下载

```
pip install fastapi
```

FastApi 服务器 uvicorn下载

```
pip install "uvicorn[standard]"
```

---

##### 方法

1. 添加路由

   ```python
   from fastapi import FastAPI

   app = FastAPI()


   @app.get("/")
   async def root():
       return {"message": "Hello World"}
   ```
2. 服务启动方式
   命令行启动

   ```
    uvicorn main:app --reload
   ```

   .py文件启动

   ```python
   import uvicorn

   if __name__ == "__main__":
       uvicorn.run("main:app", reload=True, port=5000)
   ```
   > uvicorn main:app 命令含义如下:
   > main：main.py 文件（一个 Python「模块」）。
   > app：在 main.py 文件中通过 app = FastAPI() 创建的对象。
   > --reload：让服务器在更新代码后重新启动。仅在开发时使用该选项。
   > --port：服务器运行端口

##### 错误

1. xxxx

   关键字:[]

   链接: []

   错误解决
2. XXX
