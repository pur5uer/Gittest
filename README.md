# gitbash:
  git config --global user.name "Your Name" # 设置名字<br/>
  git config --global user.email "email@example.com" # 设置邮箱<br/>
  git add xxx.xxx # 把文件xxx.xxx添加到仓库缓存区<br/>
  git commit -m "本次提交的说明" # 将缓存区的所有文件正式提交到仓库<br/>
  git log # 查看版本情况：过去所有修改时间、修改人、修改内容<br/>
  git reset --hard HEAD^ # 把当前版本回退到上一个版本，HEAD^^表示上上个版本，往上100个版本HEAD~100<br/>
  git reset --hard xxx # 回退到某个版本，xxx表示版本commit id<br/>
  git reflog # 显示过去的每一次命令<br/>
  git init # 把该文件夹变成Git可以管理的仓库<br/>
  git remote add 远程库的名字 远程库地址 # 将本地仓库与远程库联系起来<br/>
  git push -u 远程库的名字（默认为origin） master # 第一次推送master分支的命令<br/>
  git push origin master # 推送到远程库<br/>
  git clone 远程库地址   # 克隆远程仓库<br/>
  git fetch  --recurse-submodules 远程库地址 # 断点续传<br/>
  git add . # 将该目录下所有文件夹及文件提交到暂存区<br/>
  ls # 查看待上传文件夹的内容<br/>
  git pull --rebase origin master # 把最新版本的远程仓库源码更新到本地（往往是不可缺失的步骤）<br/>
  <br/>
  git add 的几种参数的区别：<br/>
  git add -A # 保存所有的修改<br/>
  git add . # 保存新的添加和修改，但是不包括删除<br/>
  git add -u # 保存修改和删除，但是不包括新建文件<br/>
  <br/>
  git status # 文件，文件夹在工作区，暂存区的状态 
  git remote -v # 查看关联远程库的本地库
