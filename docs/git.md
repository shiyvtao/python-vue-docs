# git——文档

###### 文档链接

* [官网](https://git-scm.com/ "传送到官网")[https://git-scm.com/]

---

##### 方法

1. 命令
   ```bash
    git clone xxx #下载git仓库
    git add . #保存修改git仓库
    git commit "" #将保存修改的代码提交到本地仓库
    git push #将本地仓库提交到远程仓库
    git pull #将远程仓库代码拉去到本地
    git status #查看项目文件状态
    git checkout -b <分支名> #创建分支，
    git merge #合并分支
    git branch #查看当前已有分支
   ```
2. 配置
   ```bash
    git config --list  #查看当前所有配置
    git config --global user.name "Your Name"  # 设置全局用户名
    git config --global user.email "you@example.com"  # 设置全局用户邮箱

    #公钥
    # 生成公钥
    ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

    # 将公钥进行应用 windows在C:\Users\用户\.ssh
    eval "$(ssh-agent -s)"
    ssh-add ~/.ssh/id_rsa
    # 将公钥复制到代码托管平台内

   ```

##### 错误

1. xxxx

   关键字:[]

   链接: []

   错误解决
2. XXX
