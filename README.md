# 四个人的西贡小假期

2026年9月24日至27日旅行攻略，独立静态页面，保留 TREK 分享页的地图、日期切换和预订信息。

运行 `npm ci && npm run build`，将 `docs/` 发布到 GitHub Pages。修改 `trip.json` 后重新构建即可更新攻略。

验证：`npx playwright install chromium && npm test`。已有 Chrome 时可运行 `CHROME_PATH="/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" npm test`。验证线上版本可另设 `GUIDE_URL`。

行程内容来自已授权的 TREK 公开分享数据；不包含登录凭据、数据库、后台或修改接口。网页和仓库公开可访问，任何拿到链接的人都能阅读。

基于 [TREK](https://github.com/liketrek/TREK/tree/b98787f83698f3beee1b9a8475121c52f0caf07c)，遵循 AGPL-3.0，许可证见 LICENSE。上游页面源代码在 vendor/，静态适配器及构建代码在仓库根目录。

地图底图由 OpenFreeMap 提供，需要联网。地图上的虚线表示景点游览顺序，不是实际步行或乘车导航路线。

攻略照片来自 Wikimedia Commons、酒店与餐厅等公开页面，各照片的作者、来源和已知许可保留在网页的「图片来源」中；照片版权归原权利人，代码许可证不适用于照片。
