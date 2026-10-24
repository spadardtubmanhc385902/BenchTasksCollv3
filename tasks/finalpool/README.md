# Final task pool

Snapshot of all 54 tasks marked `implemented` in [Task Tracker](https://app.notion.com/p/Task-Tracker-40353771ddd481ed9d17e8a63a6de445) on 2026-10-24.

## Scope and provenance

- Branch: `finalpool`, based on `main` commit `6ac0348555050a99bcf4f08ff8bf920616482289`.
- Layout: `tasks/finalpool/<task-name>/`; 54 task directories and 268 original task files, plus this README.
- Each task directory is copied from its developer branch snapshot below, preserving all tracked task files and their bytes. Main and developer branches are unchanged.
- Selection follows the existing Notion `implemented` status. Earlier classifications were preserved, not re-audited or promoted by this collection. No runtime tests or evaluator-logic review were performed.

## Latest task review

All 14 developer branches were checked against `tasks/examples/example-task`. The 29 named tasks in their latest batches and the unnamed second task at `tasks/yuxuan` were added to Task Tracker as `implementing`, with source links and blockers. No newly reviewed task qualified for this pool.

- Every newly reviewed task lacks `task_config.json`. It must contain a non-empty `needed_mcp_servers` and a non-empty `needed_local_tools` including `claim_done`.
- Additional English-only violations: `currency-converter/docs/task.md`; `insights-engine/docs/agent_system_prompt.md`; `audit-logger/docs/agent_system_prompt.md`; `resource-monitor/docs/agent_system_prompt.md`.
- The unnamed Yuxuan task has a blank task name and files directly in the developer directory. Its tracker title is a descriptive placeholder, not an inferred name.
- Optional user prompts, evaluation/preprocessing scripts and workspace folders were treated as optional exactly as documented. Apart from the example's explicit content requirements, only file existence was checked.

**Configuration caveat:** the source repository ignores `*.json` and has no tracked task configurations, including for the older tasks collected here. Their pre-existing Notion statuses were retained as requested; inclusion is not a new certification of runtime readiness. No missing configurations were fabricated.

## Source snapshots and included tasks

| Developer branch | Source commit and directory | Included task directories |
| --- | --- | --- |
| `fan-dev` | [`8b90f34` / `tasks/fan`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/8b90f34538e4e106eba103265efaa9a456be498c/tasks/fan) | [price-tracker](price-tracker/), [coupon-manager](coupon-manager/) |
| `gyy` | [`9612fff` / `tasks/gyy`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/9612ffff37072726292c77df0f4c6db2f8df1bbb/tasks/gyy) | [blog-engine](blog-engine/), [cms-builder](cms-builder/), [social-publisher](social-publisher/), [content-scheduler](content-scheduler/) |
| `haoze` | [`e0072cf` / `tasks/haoze`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/e0072cf979548c56984072cd76f529c7beea59b2/tasks/haoze) | [video-trimmer](video-trimmer/), [subtitle-generator](subtitle-generator/) |
| `jl_dev` | [`4e2b63f` / `tasks/jl`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/4e2b63f5dafce88b60886ed6e6af7bd9a8966296/tasks/jl) | [email-classification-system](email-classification-system/), [pdf-report-generator](pdf-report-generator/), [canvas-grade-automation](canvas-grade-automation/) |
| `junteng_dev` | [`4ab0c54` / `tasks/junteng`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/4ab0c5415824d799c3457a26482f9b794c7e9e93/tasks/junteng) | [calendar-sync](calendar-sync/), [contact-manager](contact-manager/), [reminder-service](reminder-service/), [booking-system](booking-system/), [order-processor](order-processor/), [shipment-tracker](shipment-tracker/), [product-catalog](product-catalog/) |
| `junxian_dev` | [`96bbc11` / `tasks/junxian`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/96bbc11b6fc701d07d961aaf070c434fccd1794f/tasks/junxian) | [qr-generator](qr-generator/), [translation-api](translation-api/) |
| `lueyang-dev` | [`bf8b9a1` / `tasks/lueyang`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/bf8b9a1d25edd81b158db0bb7f49d8624348e74d/tasks/lueyang) | [crm-system](crm-system/), [sales-pipeline](sales-pipeline/), [deal-manager](deal-manager/), [activity-logger](activity-logger/), [email-campaign](email-campaign/), [follow-up-reminder](follow-up-reminder/) |
| `lv` | [`0be3288` / `tasks/lv`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/0be3288e0fd4ae1f241d3ce9cc1c864ae2606d37/tasks/lv) | [chat-bot](chat-bot/), [voice-processor](voice-processor/), [sentiment-analyzer](sentiment-analyzer/), [personalization-service](personalization-service/), [feedback-collector](feedback-collector/) |
| `ruige` | [`a6f3fba` / `tasks/ruige`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/a6f3fba387f68acaf6517803e88b40a4a3c52658/tasks/ruige) | [expense-tracker](expense-tracker/), [data-analytics](data-analytics/), [canvas-automation](canvas-automation/), [file-manager](file-manager/) |
| `wenshuo-dev` | [`d11080e` / `tasks/wenshuo`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/d11080ed8d65fb72eb32d9353cb20844b593f9e8/tasks/wenshuo) | [image-processor](image-processor/), [search-engine](search-engine/) |
| `xiaochen_dev` | [`20bfc73` / `tasks/xiaochen`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/20bfc73490dcf4029b92123b6055e076b7eb5dfa/tasks/xiaochen) | [security-scanner](security-scanner/), [deployment-tool](deployment-tool/), [error-tracker](error-tracker/), [backup-utility](backup-utility/), [monitoring-agent](monitoring-agent/) |
| `yuxuan-dev` | [`e82c829` / `tasks/yuxuan`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/e82c8295f9506ced6862ab7f39048a731b48beb4/tasks/yuxuan) | [content-manager](content-manager/), [asset-optimizer](asset-optimizer/), [network-analyzer](network-analyzer/), [task-scheduler](task-scheduler/) |
| `yuzhen-dev` | [`c68265d` / `tasks/yuzhen`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/c68265dafe0a0eccc6e183ff96d1a3e5591a3d8b/tasks/yuzhen) | [data-validator](data-validator/), [form-builder](form-builder/), [permission-manager](permission-manager/), [invoice-generator](invoice-generator/), [payment-processor](payment-processor/), [alert-system](alert-system/) |
| `zhaochen` | [`b5f9cc4` / `tasks/zhaochen`](https://github.com/spadardtubmanhc385902/BenchTasksCollv3/tree/b5f9cc4f79bb9218e40c0293ab9ec4e90352a626/tasks/zhaochen) | [template-engine](template-engine/), [load-balancer](load-balancer/) |
