# 如何使用git
## 服务端创建git 仓库

``` sh
git init --bare 
```
## 本地创建仓库
```sh
git clone 仓库地址
```
## 查看分支
``` git
git branch
```
## 将文件提交到本地仓库
```
git add .
```
## 将文件提交到指定远程仓库
```
git push remoteName branchName
```
## 比较两个仓库的差异
```
git diff a b
```
## 合并两个分支
```
git merge a b
```
## 远程合并到本地
```
git rebase a b
```

