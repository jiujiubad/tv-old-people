# 影视仓多仓指南

### 1. v.json 格式

{
  "urls": [
    {"name": "饭太硬 (首选)", "url": "http://www.饭太硬.com/tv"},
    {"name": "肥猫 (资源多)", "url": "http://肥猫.com"}
  ]
}

### 2. jsDelivr 加速

https://fastly.jsdelivr.net/gh/你的github用户名/仓库名@main/v.json

### 3. 常见问题
- **解析失败**：检查 `v.json` 格式是否有多余逗号，或外层大括号是否缺失。
- **直播加载慢**：优先使用 IPv6 源，并确保路由器已开启 IPv6 功能。
- **源失效**：只需更新 v.json 里的 url，再重启电视 app。
