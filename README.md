# SENSE 自动利润对比表 V4

粉色主题独立网页版，可直接部署至 Vercel。

## 功能

- SENSE 自营客源和 Partner/KOL 客源输入
- Surgery Gross Profit（手术毛利）
- Contribution Profit（贡献利润），In-house / Partner 佣金比例可调整及 Referral Fees
- Net Operating Profit（净营业利润）和共享成本分摊
- 总成交顾客、总手术收入 KPI 和 Commission Breakdown
- Download File (PDF)：使用浏览器的打印功能选择「另存为 PDF」

## Vercel 部署

1. 登录 https://vercel.com/new 。
2. Import Git Repository，选择 `jingniyip/sense-profit-calculator`。
3. Framework Preset 选择 **Other**（静态 HTML）。
4. 点击 **Deploy**。

网站首页使用 `index.html`，无需 npm、环境变量或构建命令。

## 隐私说明

此网页默认仅在浏览器内计算，不会主动把输入的数据发送到服务器；导出 PDF 为浏览器本地操作。GitHub 仓库如为 Public，网页源代码和公式将公开；Vercel 上线的网址通常也可公开访问。如果仅供内部使用，请在部署前设置合适的仓库和网站访问限制。

## 提醒

内容仅为 SENSE 内部利润测算工具，正式财务数字请另行核对。
