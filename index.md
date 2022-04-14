## 这是我第一次在GitHub上写前端 HELLO GITHUB!

趁热打铁！ 写一下如何把本地的代码部署到GitHub上！
1. 创建分支 git branch
2. 拉远程分支的master代码 git pull origin master 
3. 推master到远程分支 git push orgin master 
### git上的部署代码用的是SSH

```markdown


# 在git上使用 ssh-keygen 命令获取你的SSH密钥！放入GitHub中的SSH-KEY
## 把GitHub仓库上的SSH认证 放在git上 使用这段命令 git remote add origin 你的SSH认证 (注意在这之前要保存好你的分支到git上
### 最后使用 git push origin master 命令就可以部署到GitHub仓库啦！
