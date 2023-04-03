##### 命令                         作用
###### add .                 向暂存区提交所有文件
###### add filename          向暂存区提交指定的文件
###### commit -m "notes"     向本地仓库提交代码
###### commit -a -m "notes"  越过add直接提交代码
###### pull == fetch + merge
###### push    把本地的提交上传到远端仓库
###### push                  把本地的提交上传到远端仓库
###### checkout -b <分支名>  创建一个分支并转到该分支  没有-b则表示切换分支，同switch
###### switch <分支名>       转到该分支
###### log                   查看历史提交记录
###### status <-s/--short>   查看本地代码状态
###### pull                  把最新的代码拉下来，并合并到当前
###### fetch                 把最新的代码拉下来
###### push                  把本地的提交上传到远端仓库
###### branch                切分支
###### 注意                  不同分支的提交记录是并行的，不互通
###### merge                 合并后会增加一个合并节点
######                       merge合并之后会产生一个合并节点
######                       当两个分支同时修改相同文件的相同位置时，会发生冲突
###### rebase 
###### reset                 回退
######      mined            放入暂存区
######      soft             放到工作区
######      hard             清空多余的文件

