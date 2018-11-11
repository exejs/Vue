# Git操作

## (1)初始化Git仓库
`git init`
## (1)添加用户和邮箱
`git config user.name "baoname"`
`git config user.email "baoname@foxmail.com"`

## (2)将文件添加到Git的暂存区
`git add -A`
## (2)查看项目当前文件提交状态
`git status -s`
## (2)从Git的暂存区提交版本到仓库 -m 后为当次提交的备注信息
`git commit -m "备注信息"`

## (3)添加一个远程仓库
`git remote add gitee git@gitee.com:exejs/JavaScript.git`
## (3)查看当前仓库对应的远程仓库地址
`git remote -v`
## (3)推送到指定仓库
`git push -u gitee master`
## (3)查看git提交的日志
`git log`

## 修改远程仓库名
`git remote rename gitee` 将默认执行 clone 的仓库名 origin 改为 gitee
## 修改仓库对应的远程仓库地址
`git remote set-url gitee git@gitee.com:exejs/JavaScript.git`
## 生成ssh
`ssh-keygen -t rsa -C "baoname@foxmail.com"`