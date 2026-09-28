# Jewelry-Competitor-Research

57 站珠宝竞品调研工作台的静态发布文件。页面入口为 `index.html`，商品与视觉分类数据位于 `data/`，以小文件拆分以便上传和更新。

启用 GitHub Pages：仓库 `Settings → Pages → Build and deployment → Source` 选择 `GitHub Actions`。部署成功后访问 <https://cathy856.github.io/Jewelry-Competitor-Research/>。

数据来自各品牌公开商品页面，图片仍使用来源站点的公开图片 URL；本站并非这些品牌的官方网站。该仓库不存放采集密钥、模型密钥或本地 `.env` 文件。后续更新应先完成增量采集、质量校验、离线预翻译和视觉分类，再重新生成静态发布文件并推送；不要在浏览器打开详情时调用付费模型。
