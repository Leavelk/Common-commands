# 常用命令：

- 创建conda环境：
 
  `conda create -n <name> python=x.x`

- 激活环境：

  `conda activate <name>`

- 查看或者创建文件：

  `cat <file_name>`

- 查看所有存在的环境：

  `conda evn list`

- scp命令：

```
  scp -r BERT_related xxxxx@172.27.xxx.xxx:~/code_file
  scp -r <source> <主机名@ip地址:target>
  两位置可以交换
```

- 查看当前所有的channel：

  `conda config --show channels`

- 添加镜像源：

```
  conda config --add channels http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
  conda config --add channels http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
  conda config --add channels http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge/
  conda config --add channels http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/bioconda/
  conda config --set show_channel_urls yes
```

- mac查看环境变量

  `cat ~/.bash_profile`
  
- 实时查看GPU使用情况
  
  `watch -n 5 nvidia-smi`
  
- 根据PID来查看运行的目录

  `ls -l /proc/<PID> | grep "cwd"`

- 查看当前的GPU编号

  `echo $CUDA_VISIBLE_DEVICES`
  
**************
**************
## 待补充...




  
