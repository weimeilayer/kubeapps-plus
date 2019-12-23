# <img src="./docs/img/logo.png" width="40" align="left"> KubeApps Plus

![License](https://img.shields.io/badge/License-Apache%202.0-red)
![HitCount](http://hits.dwyl.io/kubeoperator/kubeapps-plus.svg)
      
>KubeApps Plus 是基于 [KubeApps](https://github.com/kubeapps/kubeapps) 的扩展, [KubeApps](https://github.com/kubeapps/kubeapps) 是由 [Bitnami](https://bitnami.com/) 发布的 Kubernetes 应用商店。KubeApps Plus 的主要扩展是中文本地化、离线应用包支持。KubeApps Plus 使用 Apache License 2.0 许可, 与 [KubeApps](https://github.com/kubeapps/kubeapps/blob/master/LICENSE) 相同.

>KubeApps Plus is an extension for [KubeApps](https://github.com/kubeapps/kubeapps) which is a popular application dashboard on Kubernetes powered by [Bitnami](https://bitnami.com/). The main extensions are localization for chinese and supporting offline application package management.KubeApps Plus is licensed under the Apache License 2.0, same as [KubeApps](https://github.com/kubeapps/kubeapps/blob/master/LICENSE).

## 概要

KubeApps Plus 是 KubeApps 的扩展项目，基于 Web UI 界面在 Kubernetes 集群中部署和管理 Helm-based 的应用程序。

## 功能列表

- 从 Helm Chart Repo 中浏览并部署 Helm Chart 应用；
- 集群中已有 Helm-based 应用的查看、升级和卸载；
- 支持自定义 Helm Chart Repo（比如 ChartMuseum 和 JFrog Artifactory 等）；
- 基于 Kubernetes RBAC 的身份验证和授权；

## 安装和使用

```bash
git clone https://github.com/KubeOperator/kubeapps-plus.git
cd kubeapps_plus
helm install --name kubeapps-plus --namespace kubeapps-plus ./chart
```

- 详细安装文档请参考：[安装指南](chart+/README.md)
- 详细使用文档请参考：[使用指南](docs/user/getting-started.md)

## 开发人员指南

- [Kubeapps Plus 架构说明](docs/architecture/overview.md)
- [KubeApps Plus 构建指南](docs/developer/build.md) 有关从源代码设置构建环境和构建 Kubeapps Plus 的说明。
- [KubeApps Plus 开发文档](docs/developer/README.md) 有关设置开发人员环境以在 Kubeapps Plus 及其组件上进行开发的说明。

## 沟通交流
 
- 技术交流 QQ 群：825046920；
- 技术支持邮箱：support@fit2cloud.com；
- 微信群： 搜索微信号 wh_it0224，添加好友，备注（城市-github用户名）, 验证通过会加入群聊；
