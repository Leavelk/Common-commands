# 利用Git来连接GitHub
## Git

>Git 是由 Linux 之父 Linus Tovalds 为了更好地管理linux内核开发而创立的分布式版本控制／软件配置管理软件。

粗略的理解就是git可以记录文件改变的过程，可以找到历史修改记录

- 使用git命令先进行初始化

    `git init`

- 然后去github上找到库的链接

    `git clone https://github.com/PengLongkun/Common-commands.git`

- 修改你需要修改的文件，然后保存

    <kbd>command</kbd> + <kbd>s</kbd>

- 添加文件到缓存区，可以指定文件

    `git add .`

- 将缓存区的文件添加到本地仓库

    `git commit -m '注释'`

- 上传到服务器

    `git push`

- 将服务器文件更新到本地

    `git pull` 和 `git fetch`(还不太理解)

---
