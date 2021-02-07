
#git同步提交代码到github和码云上
修改.git/config文件：
[remote "origin"]
	url = git@github.com:lwrr/coding.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[remote "gitee"]
	url = https://gitee.com/lwr77/coding.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
