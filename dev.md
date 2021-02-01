# 开发时如何使用git

## 分支

当我们开发一个新的功能/fix bug

则新建一个分支，分支名一般取功能名称

```
git brnach 分支名
git checkout 分支

todo ...
```

提交的时候

```
git push origin 分支名
```

提交pull requst pr(合并请求)

主开发人员(项目leader) 

代码code review

进行合并代码

每次开发的时候，需要进行到主分支

进行拉取远程最新的分支

`git pull --rebase`

本地合并，解决冲突

然后再进行开发