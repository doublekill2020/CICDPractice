# 使用docker搭建gerrit+jenkins流水线

## 安装所需docker镜像
> docker pull (openfrontier/gerrit and jenkins/jenkins and nginx)
## 利用脚本启动container
(脚本应按实际情况传参)

[run_gerrit](https://github.com/doubliekill/CICDPractice/blob/master/run_gerrit) 这里使用的是HTTP认证

[run_jenkins](https://github.com/doubliekill/CICDPractice/blob/master/run_jenkins)

[run_nginx](https://github.com/doubliekill/CICDPractice/blob/master/run_nginx) 用于反向代理gerrit

## 安装,配置gerrit
## 安装,配置jenkins
## 添加流水线任务
## TODO:jenkins+跑自动化测试+CD
