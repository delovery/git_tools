

1, 安装 git  
请从官方网站下载  
https://git-for-windows.github.io/

2, 安装 TortoiseGit  
请从官方网站下载  
https://download.tortoisegit.org/tgit/2.10.0.0/TortoiseGit-2.10.0.2-64bit.msi

3, 下载 commit-msg  
http://192.9.230.37:9080/tools/hooks/commit-msg

4, 安装 commit-msg  
git config --global init.templatedir D:/BananaPI/git_tools/templatedir

5, 生成公钥和秘钥  
PuTTYgen

6, 克隆一个 repo  
git clone "ssh://liu@192.9.230.37:29418/am_sdk"

7, 修改添加  
git add *

8, 修改提交  
git commit -m "you commit msg"

9, push 文件  
git push origin refs/for/master

10, 验证提交  
verified

11, 评审提交  
review

12, 合入提交  
submit

13, 远程查看提交  
http://192.9.230.37:9080/gitweb?p=am_sdk.git;a=summary

14, 本地更新  
git pull
