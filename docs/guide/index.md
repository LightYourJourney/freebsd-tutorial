# FreeBSD 不完全指南

::: warning

🚧 文档施工中

:::

## 在线阅读

本项目托管在 GitHub Pages 上，可以通过 [https://freebsd.yanjinli.fun/](https://freebsd.yanjinli.fun/) 在线阅读。

## 本地部署

首先确保你的电脑上已经安装了 [`Node.js`](https://nodejs.org/zh-cn) 和 [`yarn`](https://yarnpkg.com/)。

在终端中依次执行以下命令，若输出版本号，则说明你已成功安装：

```shell
node -v
yarn -v # npm -v / pnpm -v
```

> 本项目使用 `yarn` 作为包管理器，你也可以使用 [`npm`](https://www.npmjs.com/) 或 [`pnpm`](https://pnpm.io/)。

```shell
git clone https://github.com/LightYourJourney/freebsd-tutorial.git
cd ./freebsd-tutorial
yarn install
yarn docs:dev
```

## 文档动态

![Repo Status](https://repobeats.axiom.co/api/embed/5d822c5a43dacbd3ee8b4a20750785eebbc831f0.svg)

## 参与贡献

欢迎对指南内容以及网站源码做出贡献，也欢迎对本指南的上游文档做出贡献。

## 版权说明

文档以 [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 协议发布。详情请见 [LICENSE](https://github.com/LightYourJourney/freebsd-tutorial/blob/main/LICENSE)。

## 贡献者

<a href="https://github.com/LightYourJourney/freebsd-tutorial/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LightYourJourney/freebsd-tutorial" alt="contributors"/>
</a>

## Star 历史

[![Stargazers over time](https://starchart.cc/LightYourJourney/freebsd-tutorial.svg?variant=adaptive)](https://starchart.cc/LightYourJourney/freebsd-tutorial)
