### git控制台命令

```java
// 将文件加入暂存区
git add .
// 将文件放入本地仓库
git commit -m '提交内容'
// 查看目录有哪些文件未提交
git status
// 本地仓库初始化
git init
// 将本地仓库提交到远程仓库
git remote add origin git@github.com:chaojiwudia/test.git
git branch -M main
git push -u origin main
// 配置秘钥，避免每次使用token进行验证。
ssh-keygen -t rsa -C "1481839150@qq.com"
ssh-add ~/.ssh/id_rsa
```