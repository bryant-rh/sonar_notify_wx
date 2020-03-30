- usage: sonar_notify_wx.py [-h] [-c CORPID] [-s SECRET] [-a AGENTID] [-u USER]
[-r REPONAME] [-b BRANCH] [-v VERSION] [-i SONARURL]

- optional arguments:
- -h, —help show this help message and exit
- -c CORPID, —corpid CORPID
- 指定企业微信corpid
- -s SECRET, —secret SECRET
- 指定企业微信应用secret
- -a AGENTID, —agentid AGENTID
- 指定企业微信应用agentid
- -u USER, —user USER 成员ID列表（消息接收者，多个接收者用’
- |’分隔，最多支持1000个）。默认指定为@al
- l，则向关注该企业应用的全部成员发送
- -r REPONAME, —reponame REPONAME
- 指定仓库名称
- -b BRANCH, —branch BRANCH
- 指定代码分支
- -v VERSION, —version VERSION
- 指定编译版本
- -i SONARURL, —sonarurl SONARURL
- 指定sonarqube系统url地址

