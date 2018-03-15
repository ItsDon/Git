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



>  git add     +     git commit       ==       git commit -a 



                 