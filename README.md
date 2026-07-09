# Provider-Evo Plugin Registry

Provider-Evo 官方插件索引仓库，对照 [Mai-with-u/plugin-repo](https://github.com/Mai-with-u/plugin-repo)。

## 工作方式

- `plugins.json`：轻量索引 `{ id, repositoryUrl }`
- `plugin_details.json`：CI 从各插件仓 `_manifest.json` 聚合（供 WebUI 市场）
- 插件源码在各自独立仓库，**本仓不含源码**

## WebUI 市场

provider-v2 默认从 `Provider-Evo/plugin-repo` 的 `main` 分支读取 `plugin_details.json`。

## 贡献插件

见 [CONTRIBUTING.md](./CONTRIBUTING.md)。
