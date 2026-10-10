# floorplan-3d

户型装修设计工具（源自 [wy51ai/floorplan-3d](https://github.com/wy51ai/floorplan-3d)，MIT）：纯前端单文件，2D 平面布置 + Three.js 3D 漫游。

**在线使用**：https://floorplan-3d.hongyangchun.workers.dev

## 自动部署

push 到 `main` 即触发 GitHub Actions（cloudflare/wrangler-action@v3 + wrangler 4）部署到 Cloudflare Workers 静态资产。

所需 secrets：
- `CLOUDFLARE_API_TOKEN`（Workers Scripts Write 权限）
- `CLOUDFLARE_ACCOUNT_ID`
