# Git 学习

| 命令名称                                 | 作用                                     |
| ---------------------------------------- | ---------------------------------------- |
| git config --global user.name 用户名     | 设置用户签名                             |
| git config -- global user.email 用户邮箱 | 设置用户签名，这两步只需一次            |
| git init                                 | 初始化本地库                             |
| git status                               | 查看本地库状态                           |
| git add 文件名                           | 添加到暂存区                             |
| git commit -m "日志信息"文件名           | 提交到本地库，提交完成后不好删，只能版本 |
| git reflog                               | 查看精简历史记录 git log（详细） |
| git reset --hard 版本号                  | 版本穿梭                                 |
| git rm --cached <文件名>                 | 删除暂存区文件，工作区还在               |

可以在.git 文件夹下的 HEAD 查看当前在哪个分支

.git\refs\heads 文件夹下存放的是当前版本号

