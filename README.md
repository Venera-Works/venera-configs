# Venera 漫画源配置

本仓库维护适用于 Venera-Plus 的漫画源配置，版本信息以 `index.json` 中的元数据为准。

## 兼容性说明

**本仓库的漫画源只有配合 [Venera-Plus](https://github.com/Venera-Works/Venera-Plus) 项目使用时才能完全适配。使用其他分支项目可能出现功能不兼容，甚至无法使用。**

## 安装与使用

1. 安装并使用 [Venera-Plus](https://github.com/Venera-Works/Venera-Plus)。
2. 在客户端的“漫画源仓库”设置中添加以下索引地址：
   ```text
   https://cdn.jsdelivr.net/gh/Venera-Works/venera-configs@main/index.json
   ```
3. 从仓库列表中选择所需漫画源并安装，按对应源的要求完成设置或登录。

## 仓库迁移

- **订阅地址更新**：客户端“漫画源仓库”设置中需要填入 CDN 索引地址（`https://cdn.jsdelivr.net/gh/Venera-Works/venera-configs@main/index.json`），而非 GitHub 网页链接。请将旧仓库订阅地址替换为新地址。
- **覆盖更新漫画源**：因旧版已安装源内仍记录旧更新 URL，直接在旧源上“检查更新”可能仍请求旧地址。请在更新仓库索引后，从新仓库列表中重新获取并覆盖更新已安装源。
- **数据保留**：无需卸载已有漫画源或清除数据，历史记录、收藏与源设置均不受影响。

## 仓库文件

| 文件 | 说明 |
| --- | --- |
| `*.js` | 漫画源配置文件 |
| [`index.json`](./index.json) | Venera 漫画源索引元数据 |