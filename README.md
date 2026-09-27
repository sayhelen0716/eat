# 蘸酱饭桌

一人食菜谱工具：能不开火就不开火，1 正餐 + 0.5 加餐。

在线使用：https://sayhelen0716.github.io/eat/（iPhone Safari →「分享」→「添加到主屏幕」）

- **今天**：28 天轮换菜单的当天正餐、加餐、当天采购和前一晚解冻提醒
- **冰箱**：勾选现有食材，列出能做的菜、只差一样的菜，并按短保食材剩余份数排「吃完计划」
- **月菜单**：4 周菜单、每周采购清单、月初备货清单
- **图例**：食材图标与符号说明（冰箱页右上角进入）

网页在 `docs/` 目录：单文件 `docs/index.html`，无依赖，直接用浏览器打开即可。GitHub Pages、Cloudflare 都只发布 `docs/`。数据（菜品、食材、采购）都在文件内的 `ING` / `DISH` / `SNACK` / `BUY` / `STOCK` 常量里。
冰箱勾选和采购勾选保存在当前浏览器的 localStorage，不跨设备同步。

## 托管

- **GitHub Pages**：https://sayhelen0716.github.io/eat/
- **Cloudflare Pages**：已连接本仓库，推送 `main` 后自动部署；国内访问走自定义域名（`*.pages.dev` 在国内基本打不开）
- 构建：无构建命令，输出目录为 `docs/`

