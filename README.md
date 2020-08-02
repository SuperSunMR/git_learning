# 目录

[toc]

# 1. 创建仓库（repository）

![](/Users/blackzero/Documents/Master/Study/others/git_learning/images/create_new_repository.png)

# 2. 本地文件（或代码）准备

## 2.1 文件已经准备好的情况

如果你已经创建好仓库而且本地文件已经编写好，可以通过下面的步骤操作：

```bash
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:SuperSunMR/git_learning.git
git push -u origin master
```

## 2.2 从现有的仓库上继续编辑或开发

```bash
git clone git@github.com:SuperSunMR/git_learning.git
```

# 3. Git 各个区域

- 工作区：就是本地你存放文件、编辑代码的位置
- 暂存区：git add会把文件从工作区提交到暂存区
- 版本库：git init之后会在本地生成一个.git文件，这个文件就是版本库

<img src="/Users/blackzero/Documents/Master/Study/others/git_learning/images/workspace_tmpspace_diff.jpeg" alt="workspace_tmpspace_diff" style="zoom:150%;" />

# 4. 命令详解

1. git init:

   将普通的工作区目录初始化为git目录

   ![WechatIMG459](/Users/blackzero/Documents/Master/Study/others/git_learning/images/WechatIMG459.png)

2. git status:

   比较工作区和暂存区之间的文件内容差异

   ![WechatIMG460](/Users/blackzero/Documents/Master/Study/others/git_learning/images/WechatIMG460.png)

3. git add

   将工作区的内容文件提交到暂存区

   