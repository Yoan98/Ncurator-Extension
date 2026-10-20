# NCurator Browser Extension

<p align="center">
  <img src="./store-assets/source/logo/ncurator-logo.svg" alt="NCurator Browser Extension" width="108" />
</p>

[简体中文](./README.md) · **English**

The browser extension is maintained independently in this repository. For the desktop AI assistant's source and downloads, see [Yoan98/Ncurator](https://github.com/Yoan98/Ncurator).

## Features

The browser extension is a lightweight bookmark utility for your information-organizing workflow:

- View bookmark titles, folder paths, and URLs, including nested folders.
- Copy every bookmarked URL in one click, one URL per line, while preserving browser order.
- Requests only the `bookmarks` permission and never creates, changes, or deletes bookmarks.
- Processes bookmark data locally in the browser. It does not upload, track, or exchange bookmark data with the desktop app.

<p>
  <a href="https://chromewebstore.google.com/detail/ncurator-knowledge-base-a/jdlfflbeekclkgcckcfombmfojmcdeio?hl=zh-CN">Install for Chrome</a> ·
  <a href="https://microsoftedge.microsoft.com/addons/detail/hkdfdbpkmkpooopbkdghecbaipeoijpj">Install for Microsoft Edge</a>
</p>

## Local development

```bash
git clone https://github.com/Yoan98/Ncurator-Extension.git
cd Ncurator-Extension
npm install
npm run dev
```

In Chrome, enable Developer mode on the extensions page and load `.output/chrome-mv3`. For Edge:

```bash
npm run dev:edge
```

Then load `.output/edge-mv3`.

## Verify and build

```bash
npm run check
npm run zip:stores
```

More development documentation:

- [Browser extension architecture](./docs/architecture.md)
- [Chrome and Edge store release](./docs/release.md)
