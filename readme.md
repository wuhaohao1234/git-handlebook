# git规范说明书

[基础文档](https://github.com/wuhaohao1234/git-handlebook/blob/main/docs.md)

[开发文档](https://github.com/wuhaohao1234/git-handlebook/blob/main/dev.md)

## 核心

1. `git rebase` & `git merge`

  git rebase 使得以前的提交commit 端开

  git merge 保留提交记录

  提倡使用git rebase

2. `git pull ` & `git pull --rebase`

  git pull 命令分解：

  `git fetch` + `git merge`

  git pull --rebase

  `git fetch` + `git rebase`

3. 查看提交日志与回滚

 `git log` 查看提交日志

 `git reflog` 查看被删除的提交日志

4. 回滚: 代码严重冲突

  `git reset --hard origin main` 与远程仓库保持一致 加commit-id

  `git cherry-pick commit-id` 切换到对应的提交