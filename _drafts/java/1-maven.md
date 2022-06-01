---
layout: single
title: maven
---
## 下载并解压
```
[maven](https://maven.apache.org/download.cgi)
tar -xvf apache-maven-3.8.5-bin.tar.gz
sudo mv -f apache-maven-3.8.5 /usr/local/
```
## 在 `/etc/profile` 文件追加以下内容
```
export MAVEN_HOME=/usr/local/apache-maven-3.8.5
export PATH=${PATH}:${MAVEN_HOME}/bin
```
## 使环境变量生效
```
source /etc/profile
```
## 查看是否安装成功
```
mvn -v
```

