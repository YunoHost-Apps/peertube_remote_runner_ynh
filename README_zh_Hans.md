<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 PeerTube Remote Runner

[![集成程度](https://dash.yunohost.org/integration/peertube_remote_runner.svg)](https://ci-apps.yunohost.org/ci/apps/peertube_remote_runner/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/peertube_remote_runner.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/peertube_remote_runner.maintain.svg)

[![使用 YunoHost 安装 PeerTube Remote Runner](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=peertube_remote_runner)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 PeerTube Remote Runner。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Remote runner to offload heavy workloads jobs (such as transcoding) from one or several (distant) Peertube server.


**分发版本：** 0.0.18~ynh1
## 文档与资源

- 官方应用网站： <https://docs.joinpeertube.org/admin/remote-runners>
- 官方管理文档： <https://docs.joinpeertube.org/maintain/tools#peertube-runner>
- 上游应用代码库： <https://github.com/Chocobozzz/PeerTube/tree/develop/packages/peertube-runner>
- YunoHost 商店： <https://apps.yunohost.org/app/peertube_remote_runner>
- 报告 bug： <https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/tree/testing --debug
或
sudo yunohost app upgrade peertube_remote_runner -u https://github.com/YunoHost-Apps/peertube_remote_runner_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
