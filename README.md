# GKD 自建订阅

基于 [甘霖的GKD订阅](https://github.com/ganlinte/GKD-subscription) 的本地托管版本。

## 订阅标识
- id: 2331（与原订阅 233 区分，可共存）
- 版本: 71
- 覆盖: 744 个应用 / 1453 个规则组

## 与上游的差异
1. `id` 由 233 改为 2331，避免与远程订阅冲突
2. 移除 `checkUpdateUrl` 的远程指向，改用仓库内版本文件
3. 可按需追加自定义规则（如微信小程序 AppBrandUI00）

## 导入链接（三选一）

jsDelivr 加速（国内推荐）:
```
https://cdn.jsdelivr.net/gh/你的用户名/gkd-subscription@main/ganlin.json5
```

GitHub Raw（需科学上网）:
```
https://raw.githubusercontent.com/你的用户名/gkd-subscription/main/ganlin.json5
```

## 使用说明
GKD → 订阅 → 右上角 ⋮ → 添加订阅 → 粘贴上面的链接

## 更新方式
编辑 `ganlin.json5` 后推送到仓库，GKD 端会自动拉取新版本。