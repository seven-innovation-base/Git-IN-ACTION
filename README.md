# Git-IN-ACTION

![Hexo Site CI](https://github.com/seven-innovation-base/Git-IN-ACTION/workflows/Hexo%20Site%20CI/badge.svg) ![issues](https://badgen.net/github/issues/seven-innovation-base/Git-IN-ACTION) ![last commit](https://badgen.net/github/last-commit/seven-innovation-base/Git-IN-ACTION) ![license](https://badgen.net/github/license/seven-innovation-base/Git-IN-ACTION)

Git-IN-ACTION 致力于分享 Git 在工程化和规范化方面的最佳实践

## 参与贡献

**可直接提 issue 分享文章，如果自己想动手的话，参考以下贡献方式**

```shell
# 1、fork 这个项目
# 2、clone 到本地
git clone https://github.com/your-username/Git-IN-ACTION
# 3、新建分支，在新建立的分支上进行改动
git branch new_branch_name
# 4、环境配置，需要安装 Node.js
cd content
npm install # 安装项目依赖
# 5、创建 & 撰写文章
npx hexo new post "文章标题" # 更多操作请查看 Hexo 文档，https://hexo.io/zh-cn/docs/writing
# 5、预览编写好的文章
npx hexo s
# 6、确认无误后提交改动到新建立的分支，然后发起 pull request
```

**如何同步（多次贡献），参考以下方式**：

```shell
# 1、添加本仓库为 fork 后 clone 到本地仓库的远程上游
git remote add upstream https://github.com/seven-innovation-base/Git-IN-ACTION
# 2、同步远程上游的变更
git fetch upstream
# 3、将远程上游的变更合并到你 fork 后的仓库的 master 分支中，保证你的 master 分支永远都是最新的
git merge upstream/master
# 4、基于最新的 master 分支新建个分支做改动，往后的操作与之前所述相同
```

## 许可证

BSD 2-Clause License. Copyright (c) 2020, Seven innovation base. All rights reserved.
See the license for more details.