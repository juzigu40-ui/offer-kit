# 渠道投放清单

更新时间：2026-05-21 22:24 CST

用途：把现有入口按平台拆开，避免“一个链接到处贴”。只做可复制清单，不自动发布、不自动登录账号。

## 优先投放顺序

| 优先级 | 渠道 | 发什么 | 用哪个入口 | 为什么 | 需要账号 / 权限 |
| --- | --- | --- | --- | --- | --- |
| P0 | GitHub Profile README | 公开交付 + 服务边界 | `https://github.com/juzigu40-ui` | 看 PR 的维护者可能会点 profile，不能只看到空主页 | 已用当前 GitHub 账号更新 |
| P0 | GitHub Pages 静态站 | 长期销售页 + 工具入口 | `https://juzigu40-ui.github.io/offer-kit/` | 临时隧道不稳定，公开链接要能长期打开 | 已发布；后续更新需 push |
| P0 | GitHub PR / issue 回复 | 只在相关 review 或问题下写事实回复 | `tools/pr-note-builder/` | 已有 4 个 PR，review 来了要快速回复 | 只能在自己的 PR 或相关 issue 下回复 |
| P0 | 公开求反馈 issue | 对 README、launch、docs 写具体反馈 | `channels/outbound-log.md` | 比陌生私信更自然，且能留下公开贡献痕迹 | 只回明确求反馈或高度相关的问题 |
| P0 | 即刻 / X / LinkedIn | 1 条“PR 文案怎么写”经验帖 | `channels/developer-short-posts.md` | 开发者更容易接受工具入口，不像硬广 | 需要账号本人发布 |
| P1 | GitHub Discussion / Indie Hackers | README 3 点诊断 | `tools/readme-audit-builder/` | 开发者公开求反馈时，README 诊断比服务广告更自然 | 只回复明确求反馈的帖子 |
| P1 | 小红书 / 朋友圈 | 小单服务菜单截图 + 具体边界 | `services/menu.html` | 面向 300 元中文轻服务，价格和交付清楚 | 需要账号本人发布 |
| P1 | 安全社区 / 开源安全群 | “漏洞报告别夸大影响”的回答 | `tools/vuln-report-builder/` | 和 Yuzu 安全修复、报告服务同向 | 只在允许分享工具的地方发 |
| P1 | Gumroad / Payhip / Ko-fi | 数字产品 + 轻服务上架 | `marketplaces/listing-pack.md` | 可收 $50，但需要账号和收款配置 | 需要平台账号、KYC、收款配置 |
| P2 | Reddit / Hacker News / Discord | 只回答问题，不贴服务链接 | `channels/helpful-replies.md` | 这些地方反感广告，先贡献内容 | 需要账号本人判断社区规则 |
| P2 | 微信群 / 私域 | 1 条短说明 + 菜单链接 | `services/menu.html` | 中文 300 元轻服务最直接 | 不群发陌生群，不刷屏 |
| P2 | 手动线索搜索 | 找正在问 PR、漏洞报告、商品页的人 | `channels/lead-finder.html` | 先找明确问题，再决定是否回复 | 只手动筛选，不自动抓取或私信 |

## 今天可发的 5 条

### 1. GitHub Profile README

用 `channels/public-profile-pack.md` 的 GitHub Profile README 段落。  
链接放 `link-in-bio/` 或 `proof/`。

当前已更新：`https://github.com/juzigu40-ui`。  
边界：后续再改前先读远端 README，避免覆盖手工内容。

### 2. 开发者平台短帖

```text
PR 描述不用写得很像广告。维护者一般只想看 4 件事：

1. 问题在哪个文件或路径。
2. 改了什么行为。
3. 跑了什么验证。
4. 还有什么边界。

我做了个本地小工具，把这 4 块整理成短文本：offer-kit/tools/pr-note-builder/
```

### 3. 安全报告短帖

```text
漏洞报告不要把“可能影响”写成“必然接管”。

我会按这几块写：Scope、Affected area、Low-risk reproduction、Impact、Evidence、Mitigation、Boundaries。

工具入口：offer-kit/tools/vuln-report-builder/
```

### 4. 中文朋友圈 / 即刻

```text
接一个很小的单：把 AI 味重的 PR、漏洞报告、商品页、私信改成人话。

你发初稿，我改一版，再写几条删改原因。¥300 / $50 起。

不编验证、不做未授权测试、不承诺成交或赏金。

菜单：offer-kit/services/menu.html
```

### 5. 小红书 / 图文标题

标题：

```text
PR 和漏洞报告怎么写得不像 AI
```

正文：

```text
不要先写“高质量、完整、企业级”。先写问题、改动、验证、边界。

如果是漏洞报告，还要补授权范围、未做事项、是否碰过生产系统。

我整理了两个本地小工具，一个写 PR 文案，一个写漏洞报告草稿。
```

配图可以用：`offer-kit/channels/social-card.html`  
可直接发图：`offer-kit/channels/social-card.png`

## 已主动发出的公开回复

- ProofPath #14：README / philosophy / launch-post 反馈，未贴服务链接。
  https://github.com/safal207/ProofPath/issues/14#issuecomment-4509187006
- Elastic docs-content #6589：integration-skills README 反馈，未贴服务链接。
  https://github.com/elastic/docs-content/issues/6589#issuecomment-4509219974

## 不发的地方

- 明确禁止自推广的社区。
- 需要绕过审核、刷赞、刷评论的平台。
- 要求提交私有系统提示词、token、运行时信息的平台。
- 需要未授权扫描或攻击真实生产系统的漏洞项目。

## 下一步

- GitHub Profile README 已完成；下一步优先从 `channels/developer-short-posts.md` 选 1 条开发者平台短帖。
- 外部链接优先使用 `https://juzigu40-ui.github.io/offer-kit/`，不再依赖临时隧道。
- 如果 24 小时内没有反馈，换安全报告短帖，不重复刷同一句。
- 继续找明确求反馈的开源 issue，每次只写真实读后的意见，不复制同一段。
- 所有外部回复都先回答问题，再放工具或菜单链接。
- 对方问价或准备付款时，先用 `services/scope-confirmation.html` 发范围确认，不直接催付款。
- 评论区临时写回复时，先用 `tools/quick-audit-builder/` 生成 3 行诊断。
- 遇到开源项目或工具页求反馈时，用 `tools/readme-audit-builder/` 生成 README 3 点诊断。
- 找新线索时，先用 `channels/lead-finder.html` 生成查询词和短回复，再人工判断平台规则。
