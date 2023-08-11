### 1. Git 初始化

```
git config --global user.name zengxin0213
git config --global user.email zengxin@email.cn
ssh-keygen -t rsa -C "zengxin@email.cn"
cat ~/.ssh/id_rsa.pub
```

### 2. 仓库初始化

```bash
git init
git add .
git commit -m "first book" 
git remote add origin https://github.com/zengxin0213/OCQDocument.git
git push -u origin master
```

### 3. 添加提交推送

```
git add .
git commit -m "zx" 
git push -u origin master
```

### 4. GitBook相关操作

> 教程：<https://www.bilibili.com/read/cv1991542/>

```bash
git add .
git commit -m “更新”
git push -u origin master 
git checkout gh-pages 
cp -r _book/* .
git add .
git commit -m “更新”
git push -u origin gh-pages
git checkout master

git init
echo "*~" > .gitignore
echo "_book" >> .gitignore 
git add .
git commit -m "first book" 
git remote add origin https://github.com/XXXXXXXXXXX
git push -u origin master
git checkout --orphan gh-pages 
git rm --cached -r .
git clean -df
rm -rf *~ 
echo "*~" > .gitignore
echo "_book" >> .gitignore 
cp -r _book/* . 
git add . 
git commit -m “更新”
git push -u origin gh-pages
git checkout master
```

