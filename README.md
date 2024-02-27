# npm-boost

简体中文 / [English](./README.en.md)

> 一个NPM加速工具

## 节点位置
npm-boost 镜像可通过 Cloudflare 在北美、南美、欧洲、非洲、亚洲和澳大利亚的许多边缘节点获得。

## 使用方法
切换到 npm-boost 镜像很简单、快速和方便。
对单个命令,可以通过 --registry 参数传入镜像。

```bash
npm install --registry https://npm-registry.wnwd.eu.org/ express
```

要对所有 npm 命令使用镜像,可以设置 registry 配置变量。

```bash
npm config set registry https://npm-registry.wnwd.eu.org/
```
