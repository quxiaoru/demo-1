# Github问题集（2）

### 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？


   New repository（创建新仓库）, Import repository（引入仓库）,New 

   gist（创建新代码片段）,New organization（新建组织）。

### 2.如何能将仓库中的html文件直接解析成页面？

  点击settings,找到Source，点击master branch.

### 3.如何删除仓库
  
   点击settings,，然后点击Delete this repository.

### 4.Bash是什么操作系统的命令

  Linux.

### 5.Pwd是什么命令

   print working directory(打印当前工作目录)。
  
### 6.Cd是什么命令，cp是什么命令

 change directory（改变目录）。 复制

### 7.Echo是什么命令

  在命令行打印信息。
 
### 8.配置git用户名的命令

  git config -- global user.name"xiaohanh"

### 9.配置邮箱的命令

 git config -- global user.email""

## 10.命令行换行方式
  
  /
 
### 11.命令行终结方式

 Ctrl+c强制退出


### 12.使用命令行比GUI方式有何优势
  
  
 更快捷。
   
### 13.提交到本地仓库时为什么有暂存区
         工作区workspace和仓库之间有一个暂存区。
暂存区：英文叫stage, 或index。在版本库.git）目录下，有一个index文件。
它实际上就是一个包含文件索引的目录树，像是一个虚拟的工作区。
在这个虚拟工作区的目录树中，记录了文件名、文件的状态信息（时间戳、文件长度等），文件的内容并不存储其中，而是保存在Git对象库（.git/objects）中.

文件索引建立了文件和对象库中对象实体之间的对应。如果当前仓库，有文件更新，
并且使用gitadd 命令，那么这些更新就会出现在暂存区中。

### 14.新建代码仓库的命令

  git init
   

### 15.git clone [url] 这个命令的作用是

    克隆仓库，下载一个目录和它的整个代码历史

### 16.添加指定文件到暂存区的命令
   
  git add[file1][file2]
 


### 17.删除工作区文件，并且将这次删除放入暂存区的命令

   git rm

### 18.改名文件，并且将这个改名文件放入暂存区的命令

   git mv

### 19.提交暂存区到仓库的命令

   git commit -m[message]


### 20.直接从工作区提交到仓库的命令

   git commit -a-m[message]

### 21. 显示变更信息的命令

 git status

### 22.查看历史信息的命令

  git log 



### 23.Commit的意义是
   
    将本地修改保存到本地仓库中。
   
### 24.Pull的意义是

  将远程仓库的提交拉下到本地。


25.Push的意义是

   将本地的提交推送到远程仓库。
