# 华润赢公开静态内容镜像

这是 [华润赢网站](https://huarun.win/) 已公开页面与引用资源的一次性快照，供 [华润赢客户端](https://github.com/huarunwin/huarunwin) 读取 HTML 并原生展示。

- 抓取时间：2026-10-21 02:33:39 至 02:39:38 UTC（北京时间 10:33:39 至 10:39:38）。
- 本次收录：2,948 个 HTML 页面、1,345 个引用资源文件，合计 367,821,861 字节（约 351 MiB）。
- 来源：匿名请求网站的公开 HTTPS 页面，通过公开链接和候选路径发现内容；不执行页面 JavaScript。
- 范围：应用、设备、机场、VPS、动态、人物、纪事、文章及说明页面，以及页面引用的站内图片、样式、脚本和字体等公开资源。外部图片、下载文件与第三方页面仍由原服务提供。
- 28 个已返回 404 的候选路径未收录，所有已识别的站内引用资源均已成功获取。

**此镜像不会自动更新。** 本次未接入网站打包、部署或同步流程，内容可能晚于网站；价格、库存、版本和链接请以原站及对应服务方的当前信息为准。快照来自一个抓取时间窗口，不是网站数据库或某次构建的原子备份。

## 客户端读取

本仓库未启用 GitHub Pages，客户端直接通过 GitHub Raw 获取公开 HTML。Raw 地址用于读取文件，不作为网页浏览入口。

| 原网页 | 镜像文件 | Raw 地址 |
| --- | --- | --- |
| `/` | `index.html` | [首页 HTML](https://raw.githubusercontent.com/huarunwin/huarunwin-static/main/index.html) |
| `/apps/flclash` | `apps/flclash.html` | [FlClash HTML](https://raw.githubusercontent.com/huarunwin/huarunwin-static/main/apps/flclash.html) |
| `/vps` | `vps.html` | [VPS HTML](https://raw.githubusercontent.com/huarunwin/huarunwin-static/main/vps.html) |
| `/jichang` | `jichang.html` | [机场 HTML](https://raw.githubusercontent.com/huarunwin/huarunwin-static/main/jichang.html) |

根页面对应 `index.html`，其他页面路径追加 `.html`；图片等资源保留站内原路径，中文和空格按 URL 路径段编码。HTML 保留公开响应原文，包含浏览器使用的脚本，但客户端只解析 DOM，不执行脚本或读取其内部序列化状态。

客户端继续以原网页地址解析相对链接和标识内容，只切换 HTML 与站内图片的请求地址；购买、下载、纠错、分享和外部链接保留原有地址。镜像不承载账号、购买跳转、表单提交或其他在线交互，不包含网站源码、后台、私有构建产物或访问凭据，也不新增供客户端使用的数据 API。

## 权利与反馈

公开可读取不等同于全部内容采用开源许可证。原创内容、第三方图标、截图、引用及脚本依赖仍按原站声明和各自许可处理，本镜像不改变原有权利或授予额外授权。网站说明见原站的[使用条款](https://huarun.win/terms)与[编辑说明](https://huarun.win/editorial-policy)。

内容纠错请使用[原站纠错入口](https://huarun.win/corrections)；镜像缺失或读取问题可在本仓库提交 Issue。
