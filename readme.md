@[TOC] git用法

### 初始化本地仓库

```bash
mkdir learngit
cd learngit
git init
```

### 工作区和暂存区(stage)

### [git远程仓库](https://www.liaoxuefeng.com/wiki/896043488029600/896954117292416)

### git常用指令用法

|指令|说明|
|---|---|
|git add file||
|git add .||
|git status||
|git diff file||
|git commit -m 'xx'||
|git log|查看提交详细日志|
|git reflog|记录每一次命令|
|git log --pretty=oneline|查看简化提交日志|
|git reset --hard HEAD^|返回上一次提交记录|
|git reset --hard commitid|返回指定提交记录|
|git checkout -- readme.txt|丢弃掉工作区的修改|
|git reset HEAD readme.txt|把暂存区的修改撤销掉|
|git log --graph|查看分支合并情况|
|git stash|暂存|
|git remote|远程分支|
|git push origin xx|推送远程分支|
|git fetch -p|同步远程分支信息|
|git rebase|变基|

### 项目管理规范

1.master、release、feature、hotfix、issue

```master稳定代码分支,每次发布后,代码合并到master,合并之前打好tag,tag命名规范和描述```

2.命名规范

```
release/v1.0.0_20200321
feature/v1.0.0_20200321
```