# AutoSignMachine

> Due to a third-party risk dispute, this script stopped sharing
### 使用插件 Pull App 同步
需要安装 [![](https://prod.download/pull-18h-svg) Pull app](https://github.com/apps/pull) 插件。

安装过程中会让你选择要选择那一种方式;

`All repositories`表示同步已经 frok 的仓库以及未来 fork 的仓库；

`Only select repositories`表示仅选择要自己需要同步的仓库，其他 fork 的仓库不会被同步。

根据自己需求选择，实在不知道怎么选择，就选 `All repositories`。

点击 `install`，完成安装。

![Install Pull App](https://cdn.jsdelivr.net/gh/Ryanjiena/BiliBiliTool.Docs@main/imgs/install_pull_app.png)

Pull App 可以指定是否保留自己已经修改的内容，分为下面两种方式，如果你不知道他们的区别，就请选择方式一；如果你知道他们的区别，并且懂得如何解决 git 冲突，可根据需求自由选择任一方式：

手动触发同步：`https://pull.git.ci/process/${owner}/${repo}`
