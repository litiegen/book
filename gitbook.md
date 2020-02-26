# Gitbook配置命令

```
npm i -g gitbook-cli 全局安装
gitbook --version 查看版本是否成功安装
gitbook build 打包成_book文件
git checkout -b gh-pages 创建gh-pages分支，将_book上传到gh—pages分支上
git branch -r 查看本地所有git分支
git branch -a 查看本地以及仓库的分支
git branch -D gh-pages 删除gh-pages分支
git push origin gh-pages 以gh-pages上传到仓库
git checkout master 切换目录
```
```jsx
配置package.json文件
"devDependencies": {
    "gitbook-cli": "^2.3.2"
  }
```
![Image text](img/pei.png)

```
travis-ci配置信息
USER_NAME litiegen
USER_EMAIL 517206296@qq.com
ACC_TOKEN github上查询
BRANCH gh-pages
GH_REF github.com/{用户名}/{仓库名}
```
```
git credential-manager remove | uninstall 本地git用户
git config --global credential.helper wincred 全部git用户删除
```