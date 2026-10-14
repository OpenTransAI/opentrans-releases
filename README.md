# OpenTrans releases

Download packages of the **OpenTrans** browser extension — AI translation and writing for Chrome and Microsoft Edge. Every version is listed on the [Releases](https://github.com/Jacleklm/opentrans-releases/releases) page with its changelog.

> This repository only hosts release packages. Source code is not published here.

## Install from a store (recommended)

Store installs update automatically.

- **Chrome**: [Chrome Web Store](https://chromewebstore.google.com/detail/opentrans-ai-writing-repl/ofdhabdokffjaklkckmkiiefnffehkgm)
- **Microsoft Edge**: [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/mlakkdajodfegnecmbgagfigiihmlapa)

## Install a package manually

Use this for a specific version or when the store is unavailable. Manually installed copies do **not** update automatically.

### Chrome

1. Download `opentrans-<version>-chrome.zip` from [Releases](https://github.com/Jacleklm/opentrans-releases/releases) and unzip it.
2. Open `chrome://extensions` and turn on **Developer mode** (top right).
3. Click **Load unpacked** and select the unzipped folder.

### Microsoft Edge

1. Download `opentrans-<version>-edge.zip` and unzip it.
2. Open `edge://extensions` and turn on **Developer mode** (left sidebar).
3. Click **Load unpacked** and select the unzipped folder.

Keep the folder in place after loading — the browser runs the extension from it. To upgrade, unzip the new version and click **Reload** on the extension card (or remove and load again).

### Verify the download

```bash
sha256sum -c SHA256SUMS.txt
```

## 中文说明

OpenTrans 浏览器扩展的安装包发布页。推荐从 [Chrome 网上应用店](https://chromewebstore.google.com/detail/opentrans-ai-writing-repl/ofdhabdokffjaklkckmkiiefnffehkgm) 或 [Edge 加载项](https://microsoftedge.microsoft.com/addons/detail/mlakkdajodfegnecmbgagfigiihmlapa) 安装，可自动更新。

手动安装：在 [Releases](https://github.com/Jacleklm/opentrans-releases/releases) 下载对应浏览器的 zip 并解压，打开 `chrome://extensions` 或 `edge://extensions`，开启「开发者模式」，点「加载已解压的扩展程序」选择解压后的文件夹。手动安装的版本不会自动更新。

## Links

- Website: https://getopentrans.com
- Docs & changelog: https://getopentrans.com/docs/changelog
- Support: support@getopentrans.com
