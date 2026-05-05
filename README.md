---
# 🐱 Momocat 莫猫官网

Momocat 是专注原创文学与创意项目的会员制社区。本仓库为其官网前端，包含中文主站与莫语页面，通过 GitHub Pages 静态托管。

## 🌐 在线访问

- 主站：`https://momocat.online/`
- 商店：`https://momocat.online/store`
- 莫语页面：`https://momocat.online/mo/`

## 📁 仓库结构

```
.
├── index.html                      # 中文首页
├── store.html                      # 商店页面
├── logo.jpg                        # 站点图标
├── mo/                             # 莫语页面目录
│   └── index.html                  # 莫语首页
├── README.md                       # 本文件
└── ...                             # 其他资源文件
```

> **语言切换**：页面底部提供 `中文（中国大陆）` 与 `Moumauakattiesrt（莫语）` 的切换，跳转至 `/mo/` 目录。

## 🚀 部署方法

### 使用 GitHub Pages
1. 将本仓库推送到 GitHub。
2. 在仓库 `Settings` → `Pages` 中，选择部署分支（如 `main`），根目录为 `/ (root)`。
3. 保存后等待构建完成，即可通过 `https://<用户名>.github.io/<仓库名>` 访问。
4. （可选）在自定义域名设置中填入 `momocat.online`，并配置 DNS 解析。

### 本地运行
直接用浏览器打开 `index.html` 即可预览。

## 🎨 技术栈

- 纯 HTML5 / CSS3 / 原生 JavaScript
- 毛玻璃毛效果 (`backdrop-filter`) 与交互动画
- 响应式布局（手机、平板、桌面端自适应）
- 语言切换与页面间路由（无构建工具依赖）

## 📄 许可

本项目内容归 Momocat 团队所有，未经允许不得转载。
