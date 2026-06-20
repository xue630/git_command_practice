# git_command_practice
这是练习git命令的仓库，会有清单指引需完成的任务
## 任务清单
### 标准任务
1. 通过git命令将本仓库拉到本地
2. 创建新文件输入任意内容推送到该仓库
3. 接着创建新分支且在新分支上修改文件
4. 合并分支

### 特殊情况1--不满意的提交回滚
1. 拉取仓库到本地
2. 随便修改一通推送到远程
3. 觉得自己的修改是一坨拉取上一个版本
4. 将上一版在推送到远程仓库

### 特殊情况2--冲突复现和解决
1. 拉取仓库到本地
2. 创建dev1和dev2两个分支
3. 分别在同一文件的相同位置修改
4. 后分别将两个分支推送到远程
5. 在远程完成对分支的合并
6. 清除本地分支

## 涉及命令手册
`git clone PATH # 克隆仓库`
`git pull # 从远程拉取最新代码 `
`git branch # 查看分支`
`git branch <name> # 创建分支name`
`git push -u origin <name> # 自动创建远程分支`
`git checkout <name> # 切换到分支name`
`git add . #添加到暂存区`
`git commit -m "" # 提交到本地仓库`
`git push origin <name> # 将代码提交到远程分支name`
`git log --online # 查看提交日志`
`git revert <hash> # 回滚到对应版本`
