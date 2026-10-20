# 馆长浏览器插件

<p align="center">
  <img src="./store-assets/source/logo/ncurator-logo.svg" alt="馆长浏览器插件" width="108" />
</p>

**简体中文** · [English](./README.en.md)

馆长浏览器插件独立维护于本仓库。桌面端 AI 助手的源码与下载见 [Yoan98/Ncurator](https://github.com/Yoan98/Ncurator)。

## 功能

浏览器插件是一个轻量收藏夹工具，用来配合你的资料整理流程：

- 查看收藏夹标题、目录和网址，支持多层文件夹。
- 一键复制全部收藏网址，每行一个，并保持浏览器原有顺序。
- 仅申请 `bookmarks` 权限；不会创建、修改或删除收藏夹。
- 收藏夹数据只在浏览器本地处理，不上传、不跟踪，也不与桌面端交换数据。

<p>
  <a href="https://chromewebstore.google.com/detail/ncurator-knowledge-base-a/jdlfflbeekclkgcckcfombmfojmcdeio?hl=zh-CN">安装到 Chrome</a> ·
  <a href="https://microsoftedge.microsoft.com/addons/detail/hkdfdbpkmkpooopbkdghecbaipeoijpj">安装到 Microsoft Edge</a>
</p>

## 本地开发

```bash
git clone https://github.com/Yoan98/Ncurator-Extension.git
cd Ncurator-Extension
npm install
npm run dev
```

在 Chrome 扩展程序页面启用开发者模式后，加载 `.output/chrome-mv3`。Edge 使用：

```bash
npm run dev:edge
```

然后加载 `.output/edge-mv3`。

## 验证与构建

```bash
npm run check
npm run zip:stores
```

更多开发资料：

- [浏览器插件架构](./docs/architecture.md)
- [Chrome 与 Edge 商店发布](./docs/release.md)

## 友链

- [LinuxDo 社区](https://linux.do/)
