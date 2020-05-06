### 版本：UYUN R13

### Q:[呼和浩特03]Windows手动安装Agent失败，报Error5，Error2

### A:
>问题原因
由于目标机器上有江民杀毒软件，将Ant Agent用来注册服务的nssm32.exe nssm64.exe，当做病毒给删除掉了
注：360杀毒软件，也有类似情况

>解决方案
安装Ant Agent前，先关闭杀毒软件，待安装完成后，在开启杀毒软件

# 参考链接
- [kb](http://kb.uyunsoft.cn/pages/viewpage.action?pageId=37197303)
- [jira](http://jira.uyunsoft.cn/browse/CPJF-3358?jql=text%20~%20%22error2%22)