# 夜幕 Nightfall · 更新仓库

夜幕是一个 Chromium Manifest V3 深色模式扩展。本仓库只发布可安装的 Release 包与校验文件，**不包含源码**。

## 最新版本

- [v1.17.1 · 第三方网页悬停态修复](https://github.com/xiao-danbao/nightfall-updates/releases/tag/v1.17.1)
- 直接下载：[nightfall-1.17.1.zip](https://github.com/xiao-danbao/nightfall-updates/releases/download/v1.17.1/nightfall-1.17.1.zip)
- 校验：[nightfall-1.17.1.zip.sha256](https://github.com/xiao-danbao/nightfall-updates/releases/download/v1.17.1/nightfall-1.17.1.zip.sha256)

## 扩展内更新

1. 打开夜幕设置弹窗，底部会显示当前版本与更新状态。
2. 点击「检查更新」。后台每 6 小时也会自动检查一次。
3. 发现新版本后，顶部会出现更新横幅，点击「下载 vX」下载 Release 包。
4. 解压并覆盖原扩展目录，打开 `edge://extensions` / `chrome://extensions` 点击「重新加载」。

> 浏览器不允许未上架扩展静默替换自身文件，因此这里提供「检测 + 下载」的一键入口，安装步骤仍需手动确认。

## 版本说明

- **1.17.1**：修复第三方网页深色模式下的浅色悬停态，包括白底、白边、白色外阴影和白色鼠标焦点环；移出后完整还原。
- **1.17.0**：深色首帧默认预涂，未知来源与新域名不再先闪白页；必应图片 / 视频悬浮白边改蓝色内描边。
- **1.16.0**：GitHub Releases 更新检查，工具栏角标与设置弹窗更新横幅。
