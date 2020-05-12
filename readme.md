

1, 安装 git
请从官方网站下载
https://github-production-release-asset-2e65be.s3.amazonaws.com/23216272/f97c3080-8341-11ea-992e-0fe5b47e5d09?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20200511%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200511T093538Z&X-Amz-Expires=300&X-Amz-Signature=bff4992f54e3b4983b8587748de31865572acd0048577a589255e65163189033&X-Amz-SignedHeaders=host&actor_id=11409816&repo_id=23216272&response-content-disposition=attachment%3B%20filename%3DGit-2.26.2-64-bit.exe&response-content-type=application%2Foctet-stream

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
