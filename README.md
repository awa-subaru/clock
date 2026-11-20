# Clock · 时间

一个简洁优雅的实时时钟页面：模拟表盘 + 数字时间，单文件、零依赖。

**在线预览：https://awa-subaru.github.io/clock/**

## 本地运行

直接用浏览器打开 `index.html` 即可。

## 特性

- 模拟表盘（时 / 分 / 秒三针，秒针平滑扫动）
- 大号等宽数字时间，带冒号呼吸动效
- 自动显示本地日期、星期与时区
- 深色渐变 + 星点背景，自适应手机与桌面
- 标签页标题实时显示当前时间
- 页面隐藏时自动暂停动画，节省电量
- 遵循 `prefers-reduced-motion` 设置

## 部署到 GitHub Pages

1. 在仓库 **Settings → Pages** 中，将 Source 设为 **Deploy from a branch**
2. 选择 `main` 分支、`/ (root)` 目录，保存
3. 稍等片刻，访问 `https://<用户名>.github.io/<仓库名>/`

## License

MIT
