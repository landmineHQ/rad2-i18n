# ftb_i18n

注意，此汉化为无授权汉化，不可用于商业用途。
这篇教程会教你如何向RAD2汉化进行贡献。

## 使用的IDE

首先，需要你下载[VSCode](https://code.visualstudio.com/)，你可以选择下载user版本与system版本，推荐下载user版本。


## 推荐的插件配置

在完成[使用的IDE](#使用的ide)后，你需要安装[i18n Ally](https://marketplace.visualstudio.com/items?itemName=Lokalise.i18n-ally)插件来方便进行对比。

## 启动项目的实时对比功能

首先，你的电脑需要具有node.js环境，你可以到[官网](https://nodejs.org/en)进行下载安装。
这边推荐使用第三方node管理工具来安装node.js，你可以在node.js官网找到推荐的[三方管理工具](https://nodejs.org/en/download/package-manager)，个人推荐使用[nvs](https://nodejs.org/en/download/package-manager#nvs)。
]

在你完成node环境安装后，你需要使用vscode创建并打开一个文件夹，然后输入
```sh
# 导入项目文件
git clone https://github.com/landminehq/rad2-i18n.git
```

```sh
# 安装软件包
npm install
```

```sh
# 编译并运行开发者模式
npm run dev
```

此时已经完成了项目的安装并进行语言对比，当然实际上你并不需要使用web页面来进行查看。
这里仅提供一种可行的方式，主要是借助vue的生态环境来快速进行本地化操作。