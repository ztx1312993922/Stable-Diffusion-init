## 1.注册登录github  
![alt text](image.png)  

## 2.创建存储库  
![alt text](image-1.png)  

## 3.存储库创建成功以后就会看到一个git地址  

## 4.以上三步仓库就配置起来了。接下来配置你的mac吧。

## 5.安装Git（主要有两种方式这个你百度一下也好）首先查看电脑是否安装Git，终端输入：git

## 6.创建ssh key、配置git 设置username和email
```
git config --global user.name "github的名字"
git config --global user.email "github的邮箱"
```
## 7.创建ssh key
```
ssh-keygen -t rsa -C "githubm邮箱@qq.com"
```   
## 8.用 cat .ssh/id_rsa.pub 命令查看ssh key
```
cat .ssh/id_rsa.pub
```
## 9.将ssh key复制到github的ssh key里面

