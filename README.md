# 华润赢公开静态内容镜像

本仓库保存 [华润赢网站](https://huarun.win/) 成功部署后的公开 HTML 与静态资源，供 [华润赢客户端](https://github.com/huarunwin/huarunwin) 读取。

网站发布流程在 Cloudflare 上传及数据确认成功后，将同一次构建的公开文件同步至本仓库 main。内容未变时不新增提交；失败时保留上一份镜像，因此镜像仍可能暂时晚于网站。GitHub Pages 保持关闭。

根页面对应 index.html，其他页面按原路径追加 .html；图片与其他公开资源保持原路径。客户端使用 https://raw.githubusercontent.com/huarunwin/huarunwin-static/main/ 读取文件，仍按原网站 URL 解析链接。镜像不新增客户端数据接口，不包含后台页面、RSC、源码映射、Worker、构建报告或凭据。购买、下载、纠错及其他在线交互继续使用原网站或第三方入口。

公开内容与第三方图片、脚本仍遵循原站声明及各自许可，本镜像不授予额外权利。价格、版本与可用性请以原站为准；内容纠错使用 [原站纠错入口](https://huarun.win/corrections)。
