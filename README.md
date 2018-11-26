# GitLearn
Git的学习使用(精简版)   

1、准备工作：  
下载安装Git   
设置本机账号信息：   
git config --global user.name "your name"     
git config --global user.email "email@example.com"    

2、常用命令  
A、把项目添加到Git库管理：   
a、在dos命令下跳转到指定项目的目录下      
b、git init    
B、把修改后的文件提交到版本库当前分支    
a、git add file       
b、git commit -m message  
[file:提交的文件；message:本次提交的说明信息]    
过程：   
add命令是把修改的文件添加到了暂存区   
commit命令是把暂存区里的所有文件提交到当前分支    
C、查看当前状态   
git status    
D、查看文件修改的区别    
git diff file   
E、查看提交历史日志   
git log   
F、查看命令历史日志   
git reflog    
G、版本切换   
a、[回退]git reset --hard HEAD^    
[参数解释：HEAD，当前版本；HEAD^，上个版本；……；或HEAD~数字n]    
b、[切换]git reset --hard commit_id    
H、查看分支   
git branch    
