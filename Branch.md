# 如何创建分支

```nginx
git branch add_branch # 创建一个名为add_branch的分支
git branch # 查看分支目录
git checkout add_branch # 切换到add_branch分支目录下
```

------

```nginx
git status # 查看git本地仓库内容（文件未上传）
git add . # 将文件夹内所有内容移动到本地git仓库等待提交
git commit -m "branch_commit" # 对提交文件的一种描述（提交完成，但并未到远程）
```

------

```nginx
git regit push origin add_branch # 将文件传送到远程对应的分支上
```

