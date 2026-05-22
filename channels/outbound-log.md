# 公开反馈记录

更新时间：2026-05-22 23:08 CST

用途：记录主动发出的公开触点。只记录明确求反馈、相关 issue 或自己 PR 下的回复；不记录群发、私信或硬广。

## 已发出

| 时间 | 位置 | 动作 | 为什么发 | 链接 | 下一步 |
| --- | --- | --- | --- | --- | --- |
| 2026-05-21 22:18 CST | ProofPath #14 | 回复 README / philosophy / launch-post 反馈 | issue 明确征求外部反馈，评论内容能直接帮助作者调整 README 首屏 | https://github.com/safal207/ProofPath/issues/14#issuecomment-4509187006 | 监控作者回复；不追加催促 |
| 2026-05-21 22:24 CST | Elastic docs-content #6589 | 回复 integration-skills README 反馈 | issue 明确要求 review README，评论少，能指出文档结构问题 | https://github.com/elastic/docs-content/issues/6589#issuecomment-4509219974 | 监控 docs team 回复；如要求 PR 再补 |
| 2026-05-21 22:31 CST | agentic-swmm-workflow #2 | 回复 README 清晰度反馈 | issue 明确询问 README 是否讲清“不是 SWMM 替代品，而是工作流层” | https://github.com/Zhonghao1995/agentic-swmm-workflow/issues/2#issuecomment-4509275266 | 监控作者回复；如需要可给 README PR |
| 2026-05-21 22:47 CST | BasedHardware/Omi #3120 | 提交 Open-Meteo integration PR 后回链 | issue 明确讨论 $50 integration-app bounty，PR 已实现无 OAuth 天气/空气质量 app | https://github.com/BasedHardware/omi/issues/3120#issuecomment-4509417467 | 监控 PR #7442 review；不重复催促 |
| 2026-05-21 22:54 CST | BasedHardware/Omi PR #7442 | 回复自动 review 处理结果 | 自动评论指出验证约束和 HTTP client 复用问题，已用新 commit 修掉 | https://github.com/BasedHardware/omi/pull/7442#issuecomment-4509483730 | 等维护者 review |
| 2026-05-21 23:13 CST | BasedHardware/Omi #3120 | 提交 Frankfurter currency integration PR 后回链 | 同一 issue 明确讨论 $50 integration-app bounty，PR 已实现无 OAuth 汇率转换 app | https://github.com/BasedHardware/omi/issues/3120#issuecomment-4509647063 | 监控 PR #7443 review；不重复催促 |
| 2026-05-21 23:41 CST | BasedHardware/Omi PR #7443 | 回复自动 review 处理结果 | 自动评论指出 invalid input 返回 422 和 HTTP client 未复用，已用新 commit 修掉 | https://github.com/BasedHardware/omi/pull/7443#issuecomment-4509890809 | 等维护者 review |
| 2026-05-22 00:08 CST | BasedHardware/Omi #3120 | 提交 Public Holidays integration PR 后回链 | 同一 issue 明确讨论 $50 integration-app bounty，PR 已实现无 OAuth 公共节假日和长周末查询 app | https://github.com/BasedHardware/omi/issues/3120#issuecomment-4510250405 | 监控 PR #7445 review；不重复催促 |
| 2026-05-22 00:23 CST | BasedHardware/Omi PR #7445 | 回复自动 review 处理结果 | 自动评论指出 204 空响应会触发 JSONDecodeError、国家列表缺少返回结构保护，已用新 commit 修掉 | https://github.com/BasedHardware/omi/pull/7445#issuecomment-4510318779 | 等维护者 review |
| 2026-05-22 00:29 CST | BasedHardware/Omi PR #7445 | 回复第二条自动 review 处理结果 | 自动评论指出长周末 bridge day 文案和类型保护问题，已用新 commit 修掉 | https://github.com/BasedHardware/omi/pull/7445#issuecomment-4510363471 | 等维护者 review |
| 2026-05-22 01:14 CST | Scottcjn/Rustchain PR #6064 | 回复 PR bot label 提示 | bot 提示非 docs PR 需要 BCOS label；无权限加 label，已说明改动范围并建议 BCOS-L1 | https://github.com/Scottcjn/Rustchain/pull/6064#issuecomment-4510739592 | 等维护者 review |
| 2026-05-22 01:54 CST | BasedHardware/Omi #3120 | 提交 Open Food Facts integration PR 后回链 | 同一 issue 明确讨论 $50 integration-app bounty，PR 已实现无 OAuth 食品搜索、条码查询、产品对比和过敏原检查 app | https://github.com/BasedHardware/omi/issues/3120#issuecomment-4511039479 | 监控 PR #7448 review；不重复催促 |
| 2026-05-22 02:02 CST | BasedHardware/Omi PR #7448 | 回复自动 review 处理结果 | 自动评论指出 malformed JSON 会 500、过敏原文本匹配会误判；已用新 commit 修掉 | https://github.com/BasedHardware/omi/pull/7448#issuecomment-4511123218 | 等维护者 review |
| 2026-05-22 02:08 CST | BasedHardware/Omi PR #7448 | 回复 Codex review 处理结果 | 自动评论指出 async endpoint 里同步 requests 会阻塞 event loop；已改为 Starlette threadpool 包装 | https://github.com/BasedHardware/omi/pull/7448#issuecomment-4511164704 | 等维护者 review |
| 2026-05-22 10:26 CST | cargo-fresh #3 | 回复 1.0 前 CLI / JSON schema 反馈 | issue 明确收集反馈，0 评论；建议机器可读 skip reason、registry error、summary counts、prerelease policy | https://github.com/jenkinpan/cargo-fresh/issues/3#issuecomment-4514443100 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 10:47 CST | lean-ctx #249 | 回复 Context Manager dashboard UX 反馈 | issue 明确请求 dashboard 反馈，0 评论；建议 pressure table、eviction candidates、budget bands、compression-risk warning | https://github.com/yvgude/lean-ctx/issues/249#issuecomment-4514545793 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 11:17 CST | anchormap #5 | 回复 docs-to-code drift demo PR first reaction | issue 明确请求 5 分钟反馈，0 评论；基于 demo PR #3/#2/#4 给出 report clarity、reviewer action、rollout 建议 | https://github.com/fstepho/anchormap/issues/5#issuecomment-4514689721 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 11:47 CST | Alpha Insights #1 | 回复 V4.1 dual-platform release feedback | issue 明确请求 skill / README / demo report 反馈，0 评论；基于 README、安装契约、Codex installer 和 demo report 给出 harness proof、安装路径、source trace、failure-mode 建议 | https://github.com/Ericyoung-183/alpha-insights/issues/1#issuecomment-4514823523 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 12:26 CST | handsdiff/hub #11 | 提交 ghost counterparty deadline PR 后回链 | issue 明确有 100 HUB bounty；PR 实现 14 天默认 deadline、旧记录 backfill 和 48h claimant self-resolve | https://github.com/handsdiff/hub/issues/11#issuecomment-4514951145 | 监控 PR #22 review；不重复催促 |
| 2026-05-22 12:57 CST | fetchai/innovation-lab-examples #48 | 提交 first-run env examples PR | issue 明确列出缺 `.env.example` 的示例目录；PR 补模板、删除 tracked `.env`、移除硬编码 Serper key | https://github.com/fetchai/innovation-lab-examples/pull/122 | 监控 review / checks |
| 2026-05-22 13:22 CST | FhenixProtocol/cofhe-hardhat-starter #12 | 提交 missing `.env.example` PR | issue 0 评论且无同题 PR；README 已引用 `.env.example`，仓库缺模板且 `.gitignore` 未保留例外 | https://github.com/FhenixProtocol/cofhe-hardhat-starter/pull/13 | 监控 review；不重复催促 |
| 2026-05-22 13:29 CST | StoveCode/coraza-dashboard #35 | 回复 env template 核对结果 | issue 说缺 `CORAZA_METRICS_URL`，但当前 master 已有 `.env.example` 示例和 compose 传参；不做重复 PR | https://github.com/StoveCode/coraza-dashboard/issues/35#issuecomment-4515301093 | issue 已关闭，留档 |
| 2026-05-22 14:19 CST | Farukhsb/edu-intel-spark #104 | 回复 lecturer workflow realism 反馈 | issue 明确请求 lecturer workflow 真实感反馈；已读 README、governance note、pipeline 和 moderation demo | https://github.com/Farukhsb/edu-intel-spark/issues/104#issuecomment-4515711837 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 14:50 CST | BoolerLogic/marmota #3 | 回复 README / scope clarity 反馈 | issue 明确请求 README 和项目范围反馈；已读 README、build note、Wails 配置和项目结构 | https://github.com/BoolerLogic/marmota/issues/3#issuecomment-4515971903 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 15:26 CST | tobi-20/tweet-audit PR #1 | 回复 Go pipeline 架构 / 测试反馈 | PR 明确请求架构和红旗反馈；本地跑 `go test ./...` 复现 checkpoint、输入校验和 prompt 校验问题 | https://github.com/tobi-20/tweet-audit/pull/1#issuecomment-4516400385 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 15:45 CST | sddm/sddm #2175 | 回复插件登录系统安全边界反馈 | issue 明确说 looking for feedback 且 0 评论；反馈集中在插件路径、PAM/session 边界、challenge 语义、超时和日志 | https://github.com/sddm/sddm/issues/2175#issuecomment-4516556047 | 监控作者回复；如需要再补协议草案 |
| 2026-05-22 16:18 CST | SolvoFounder/termlog #3 | 回复 CLI 首次使用 / 记录语义反馈 | issue 明确请求 v0.1.0 honest feedback；本地安装、跑 help/list、跑测试，并读 capture / FTS 代码 | https://github.com/SolvoFounder/termlog/issues/3#issuecomment-4516877263 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 16:48 CST | QuantaVoxel/laravel-bootstrap-component #2 | 回复 Laravel 包架构 / DX 反馈 | issue 明确请求 code review；已读 README、composer、ServiceProvider、helper、docs 和代表性组件 | https://github.com/QuantaVoxel/laravel-bootstrap-component/issues/2#issuecomment-4517132127 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 17:19 CST | omry/agent-skill-installer #1 | 回复多技能包 API / manifest 设计反馈 | issue 明确询问一个 Python 包是否应支持多个 agent skill；已读 packaging docs、SkillProject 和 installer manifest 代码 | https://github.com/omry/agent-skill-installer/issues/1#issuecomment-4517355688 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 17:47 CST | p1910081/deadport #1 | 回复 beta CLI smoke test 反馈 | issue 明确请求 beta 测试；用 npx 验证空端口、占用端口和版本输出，发现 beta.2 包仍打印 beta.1 | https://github.com/p1910081/deadport/issues/1#issuecomment-4517595535 | 监控作者回复；如需要再补复现 |
| 2026-05-22 18:21 CST | Mumega-com/mcpwp #320 | 提交 Freemius release 包装 PR | issue 指出 paid single-plugin distribution 与旧 free/premium 包装不一致；PR 复用 Freemius build script 并验证 dry-run zip | https://github.com/Mumega-com/mcpwp/pull/326 | 监控 review / checks |
| 2026-05-22 18:46 CST | Bortlesboat/x402-insights #21 | 回复 agent evidence trail / Splunk 审计反馈 | issue 明确请求企业 agent 工具、审批、付款和生产数据证据链反馈；已读 architecture、SDK、Splunk searches 和 proof graph | https://github.com/Bortlesboat/x402-insights/issues/21#issuecomment-4517985535 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 19:53 CST | Ubuntu-123/changeloggenie-prototype #2 | 回复 v0.1.0 CLI / AI runner 测试反馈 | issue 明确请求本地测试反馈，0 评论；临时 venv 跑技术 changelog、version 参数、JSON 样例校验和无 key AI runner 边界 | https://github.com/Ubuntu-123/changeloggenie-prototype/issues/2#issuecomment-4518404210 | 监控作者回复；如要求 PR 再补 |
| 2026-05-22 20:20 CST | inxbit/prismtty #13 | 提交 Fortinet replay fixture PR | issue 明确请求合成 FortiGate CLI 样例；PR 补 policy、IPsec、diagnose、HA、traffic / UTM log 输出和 replay expectations | https://github.com/inxbit/prismtty/pull/24 | 监控 review / checks |
| 2026-05-22 20:51 CST | omry/agent-skill-installer #1 | 回复多技能安装实测反馈 | 作者点名邀请测试；用临时 repo 验证多 source skill 选择、安装、rename、manifest、uninstall，并指出 verbose 文档位置和空 hook/目录清理边界 | https://github.com/omry/agent-skill-installer/issues/1#issuecomment-4518787575 | 监控作者是否要求 PR |
| 2026-05-22 21:19 CST | omry/agent-skill-installer #1 | 回复交互式多技能安装实测反馈 | 作者要求继续测试 interactive install；用真实 TUI 跑 all / single select，发现空选择直接 Enter 会安装 all，空预览文案仍写 target | https://github.com/omry/agent-skill-installer/issues/1#issuecomment-4519027103 | 等作者判断是否要 PR |
| 2026-05-22 21:23 CST | agentic-swmm-workflow #2 | 回复 README 改版后 follow-up | 作者已按上次反馈前移项目边界；复读新版 README 后补两个小调整：自然语言表述位置和 five-minute 标题 | https://github.com/Zhonghao1995/agentic-swmm-workflow/issues/2#issuecomment-4519054026 | 不继续催促，等作者回复 |
| 2026-05-22 21:51 CST | omry/agent-skill-installer #1 | 回复交互修复验证结果 | 作者用 commit `6e788b6` 修掉交互空选择问题；已拉最新代码复测 TUI，并跑 `test_installer.py` 109 passed | https://github.com/omry/agent-skill-installer/issues/1#issuecomment-4519290366 | 该线索暂收口，等新请求 |
| 2026-05-22 22:24 CST | tomasz-tomczyk/crit #557 | 回复 live mode 实测反馈 | issue 明确请求 live mode feedback；读当前 main、README、live/preview 注入代码，并跑 Go / Node focused tests | https://github.com/tomasz-tomczyk/crit/issues/557#issuecomment-4519548086 | 监控作者回复；如要求可拆成专门 issue 或 PR |
| 2026-05-22 23:08 CST | MelorTang/scopeguard #1 | 回复 developer preview first-run 反馈 | issue 明确请求 ScopeGuard public preview 反馈；fresh clone 跑 install、build、typecheck、doctor/smoke 和外部 repo init/scan 流程 | https://github.com/MelorTang/scopeguard/issues/1#issuecomment-4519744209 | 监控作者回复；如要求可拆 docs PR |

## 发送规则

- 先读原文，再写具体卡点。
- 不贴服务链接，不催对方购买。
- 不复制同一段到多个 issue。
- 不在关闭、已解决、禁止推广或无关讨论下刷存在感。
- 对方回复后再继续；没有回复不连续顶帖。

## 下一轮候选

- `README feedback is:issue is:open comments:<3 updated:>=2026-05-01`
- `"looking for feedback" README is:issue is:open comments:<5`
- `"docs feedback" is:issue is:open comments:<5`
- `"launch post" feedback is:issue is:open comments:<5`
