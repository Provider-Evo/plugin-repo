# 如何向 Provider-Evo 插件中心贡献

## 必需文件（插件仓库根目录）

| 文件 | 说明 |
|------|------|
| `_manifest.json` | manifest v2，`plugin_type` 为 platform/fncall/webui/coplan/general |
| `plugin.py` | `create_plugin()` 入口 |
| `LICENSE` | 与 manifest.license 一致 |
| `README.md` | 功能与配置说明 |

**注意**：`accounts.py` 不得提交到 GitHub。

## 提交方式

1. 在插件仓库完成 manifest 与测试
2. 向本仓提 Issue（Add Plugin 模板）或 PR 修改 `plugins.json`
3. CI 校验 `_manifest.json` 与 `host_application` 兼容范围

## 插件 ID

推荐：`<author>.provider-<name>` 或 `provider-evo.<name>`，与 `_manifest.json` 的 `id` 一致。
