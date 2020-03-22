@[TOC] git常用指令

### 初始化本地仓库

```bash
mkdir learngit
cd learngit
git init
```

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
