### 1.该命令会将当前工作分支切换到branchName
```
git checkout branchName
```
### 2. 在新分支创建的同时切换分支
```
git checkout -b newBranch
该命令相当于下面这两条命令的执行结果：
1. git branch newBranch 
2. git checkout newBranch
该命令的完全体为：
git checkout -b|-B <new_branch> [<start point>]
```
https://www.jianshu.com/p/cad4d2ec4da5

