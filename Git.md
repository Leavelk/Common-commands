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

# 在VS code中使用screen命令

## 需求：让程序在后台能够继续运行(以下前五个命令就够了)

- 创建session

    `screen -C <name>`

- 列出所有的session

    `screen -ls`

- 回到\<name\>的这个session

    `screen -r <name>`

- 远程detach\<name\>的这个session

    `screen -d <name>`

- 结束当前session并回到yourname这个session

    `screen -d -r <name>`

- 当进入了某个session后，可以采用以下命令，并且所有命令都以<kbd>ctrl</kbd>+<kbd>a</kbd>开头。

    - 重命名窗口

        <kbd>ctrl</kbd>+<kbd>a</kbd>，然后<kbd>shift</kbd>+<kbd>a</kbd>
    
    - 创建新的窗口

        <kbd>ctrl</kbd>+<kbd>a</kbd>，然后<kbd>c</kbd>

    - 查看所有的窗口

        <kbd>ctrl</kbd>+<kbd>a</kbd>，然后<kbd>w</kbd>

    - 创建新的窗口

        <kbd>ctrl</kbd>+<kbd>a</kbd>，然后<kbd>c</kbd>

    - 关闭窗口

        <kbd>ctrl</kbd>+<kbd>a</kbd>，然后<kbd>k</kbd>

    - detch窗口

        <kbd>ctrl</kbd>+<kbd>a</kbd>，然后<kbd>d</kbd>
    