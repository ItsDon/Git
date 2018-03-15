# 工作中常用git命令汇总


## git原理图
![avatar](https://cdn.liaoxuefeng.com/cdn/files/attachments/001384907702917346729e9afbf4127b6dfbae9207af016000/0)

## git clone
>> git clone https://github.com/ItsDon/Git.git （在当前目录下创建Git目录）    
>> git clone  https://github.com/ItsDon/Git.git . (在当前目录下不创建新的目录)    
>> git clone https://github.com/ItsDon/Git.git  MyGit (在当前目录下创建MyGit目录)   
                   
## git支持的数据传输协议  
> https://   https://github.com/ItsDon/Git.git

>git://   git@github.com:ItsDon/Git.git

>ssh   


## git status
> git status

> git status -s

> git status --short 

## .gitignore文件 
>   这是多种语言的.gitignore模板  https://github.com/github/gitignore  
                                                                
                                                                
## git diff   
> git diff  (比较的是工作目录中的文件和暂存区快照之间的差异)

> git diff --cached (查看的是已暂存的将要添加到下次提交里的内容)

> git diff --staged (同上)


## git add + git commit
>  git add     +     git commit -m "xx"     ==       git commit -a  -m "xxx"

## git rm --cached  删除对当前文件的跟踪

## git mv file_from file_to  将文件重命名
>  该命令相当于下面3条命令

> mv file_from file_to

> git rm file_from

> git add file_to
             
## git rm
> git rm xx (同时从暂存区和工作目录删除)

> git rm --cached xx (只是从暂存区删除，工作目录仍然存在，即相当于取消跟踪)   
