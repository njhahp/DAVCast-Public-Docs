# DAVCast App Store Connect Metadata

Prepared on: 2026-08-05

## Public URLs

- Support URL: `https://njhahp.github.io/DAVCast-Public-Docs/support`
- Privacy Policy URL: `https://njhahp.github.io/DAVCast-Public-Docs/privacy-policy`
- Terms of Use URL: `https://njhahp.github.io/DAVCast-Public-Docs/terms`
- Marketing URL: `https://njhahp.github.io/DAVCast-Public-Docs/`

## English metadata

### App Name

DAVCast

### Subtitle

WebDAV media browser and cast

### Promotional Text

Browse WebDAV libraries, play media, preview documents, and cast supported content through AirPlay or DLNA.

### Description

DAVCast helps you connect to your WebDAV servers and access your media library from iPhone and iPad.

With DAVCast you can browse folders, search and sort files, play video and audio, preview images and documents, manage playlists and favorites, and cast supported content through AirPlay or DLNA.

Key features:

- Connect to one or more WebDAV servers
- Browse folders, search files, sort items, and select multiple files
- Play video and audio locally
- Preview PDF, text, Markdown, HTML, image, Word, Excel, and PowerPoint files
- Save favorites and manage playlists
- Cast supported content through AirPlay and DLNA
- Unlock DAVCast Pro through App Store subscriptions

### Keywords

webdav,media player,video player,audio player,file browser,airplay,dlna,playlist,document viewer

### Review Notes

DAVCast is a WebDAV client app for browsing personal or organizational media libraries.

Reviewer steps:

1. Open the app.
2. Go to Settings and add a WebDAV server.
3. Open the server in the Files tab.
4. Tap a media file to play it or tap a document to preview it.
5. If needed, test playlists, favorites, and AirPlay or DLNA casting.

Implementation notes:

- Server passwords are stored in Keychain.
- Playlist and favorite URLs are sanitized to avoid embedded credentials.
- The app uses local-network access only for AirPlay or DLNA discovery and casting.
- DAVCast Pro uses auto-renewable subscriptions with product IDs `davcast.pro.monthly` and `davcast.pro.yearly`.

## 简体中文元数据

### App 名称

DAVCast

### 副标题

WebDAV 媒体浏览与投放

### 推广文本

连接 WebDAV 媒体库，浏览文件、播放音视频、预览文档，并通过 AirPlay 或 DLNA 投放支持的内容。

### 描述

DAVCast 帮助你在 iPhone 和 iPad 上连接自己的 WebDAV 服务器并访问媒体内容。

你可以使用 DAVCast 浏览文件夹、搜索和排序文件、播放视频和音频、预览图片与文档、管理播放列表与收藏，并通过 AirPlay 或 DLNA 投放支持的内容。

核心功能：

- 连接和管理一个或多个 WebDAV 服务器
- 浏览文件夹、搜索文件、排序项目、批量选择
- 本地播放视频和音频
- 预览 PDF、文本、Markdown、HTML、图片以及 Word、Excel、PowerPoint 文件
- 管理播放列表与收藏
- 通过 AirPlay 和 DLNA 投放支持的内容
- 通过 App Store 订阅解锁 DAVCast Pro 功能

### 关键词

webdav,媒体播放器,视频播放器,音频播放器,文件浏览,airplay,dlna,播放列表,文档预览

### 审核备注

DAVCast 是一款 WebDAV 客户端应用，用于浏览个人或组织的媒体文件库。

审核步骤：

1. 打开应用。
2. 进入 Settings 添加一个 WebDAV 服务器。
3. 在 Files 页打开该服务器。
4. 点击媒体文件进行播放，或点击文档进行预览。
5. 如有需要，可测试播放列表、收藏以及 AirPlay / DLNA 投放。

实现说明：

- 服务器密码存储在 Keychain 中。
- 播放列表和收藏中的 URL 会清洗内嵌凭据。
- 本地网络权限仅用于 AirPlay / DLNA 设备发现与投放。
- DAVCast Pro 使用自动续订订阅，商品 ID 为 `davcast.pro.monthly` 和 `davcast.pro.yearly`。
