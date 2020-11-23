# 如何创建并push到远程仓库

```nginx
1. git config --global user.name "AerialDream"
2. git config --global user.email "1368844326@qq.com"
```

- 创建用户名和电子邮箱。

------

```nginx
git init # 初始化git
git status # 查看git本地仓库内容（文件未上传）
git add . # 将文件夹内所有内容移动到本地git仓库等待提交
git commit -m "first commit" # 提交的一种解释（提交完成，但并未到远程）
```

- 在对应的文件夹内初始化本地git仓库

------

```nginx
git remote add origin https://github.com/AerialDream/Sakura.git # 将文件传送到远程对应的仓库上 
```

