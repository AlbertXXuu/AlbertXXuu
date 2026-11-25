<p align="center">
  <img src="assets/alvenx-wordmark.svg" width="320" alt="AlvenX">
</p>

# AlbertXXuu

I build reproducible AI tools for multimodal evaluation and browser-agent regression. My projects connect runnable code, independent outcome checks, and inspectable results.

[Projects and results](https://alvenx.com/#work) · [Engineering case studies](https://alvenx.com/notes#engineering-cases) · [About AlvenX](https://alvenx.com/about)

## Two projects to try

**BrowserAgentRegression — did the browser reach the intended state?** A browser agent once reported that checkout had failed, although every required page checkpoint had passed. BAR scores the page independently. In a separate controlled experiment, an overlay blocked a driver on nine attempts across three tasks. BAR identified the first missed checkpoint in all nine. [Source and local demo](https://github.com/AlbertXXuu/BrowserAgentRegression) · [Real-agent record](https://github.com/AlbertXXuu/BrowserAgentRegression/blob/v1.1.3/docs/evidence/phase0-deepseek-gate-c-02.md) · [Controlled results](https://github.com/AlbertXXuu/BrowserAgentRegression/blob/v1.1.3/docs/evidence/v1.0.0-report.md)

**OpenMultimodalLab — which model would you run on an 8 GB laptop GPU?** On 102 synthetic tasks, Qwen3-VL scored 0.784 on average and SmolVLM2 scored 0.690. On the four event-order tasks, their scores were 0.00 and 0.75 respectively. Each model completed three measured runs per task. The saved results let you check which categories drove the difference, alongside latency and peak memory. [Source and local benchmark](https://github.com/AlbertXXuu/OpenMultimodalLab) · [Results by task category](https://github.com/AlbertXXuu/OpenMultimodalLab/blob/v1.1.2/docs/reports/v1.0.0-candidate/report.md) · [Machine-readable run summary](https://github.com/AlbertXXuu/OpenMultimodalLab/blob/v1.1.2/docs/reports/v1.0.0-candidate/run-summary.csv)

I use AI tools in development. The project records show how candidate outputs were tested and which results another person can reproduce.

## More engineering and research

- **ReproLock** replays reviewed Playwright tests against exact before-and-after application revisions. The DrawDB case includes a plain Playwright control. [Source](https://github.com/AlbertXXuu/ReproLock) · [Test-repair experiment](https://github.com/AlbertXXuu/ReproLock/tree/main/spikes/test-healing-preservation)
- **PhysGauge** tests video metrics against known violations in simulated collisions. **GeometryAudit** provides recorded camera poses for independent recalculation and documents the prior-art review that closed its original research candidate. [PhysGauge](https://github.com/AlbertXXuu/PhysGauge) · [GeometryAudit](https://github.com/AlbertXXuu/GeometryAudit)
- **SpatialSceneLab** combines editable Blender scenes, GLB round-trip checks and camera diagnostics. An RGB cross-check found adequate coverage in only two of fifteen image pairs, leaving the proposed camera change unconfirmed. [Source](https://github.com/AlbertXXuu/SpatialSceneLab) · [RGB cross-check](https://github.com/AlbertXXuu/SpatialSceneLab/blob/main/reports/TABLE0-RGB-2026-10-25.md)

## 简体中文

我做多模态评测与浏览器 Agent 可靠性工具，关注两个问题：Agent 是否真的完成了用户的任务？同一批数据上，平均分领先的模型在哪些题型会落后？

- 看工程实现，可以从 BAR 的独立页面检查点读起，再看 ReproLock 怎样验证一条回归测试能区分修复前后的版本。[BAR 工程案例](https://alvenx.com/notes/engineering/browser-agent-independent-scoring-zh) · [ReproLock 工程案例](https://alvenx.com/notes/engineering/verified-browser-regression-zh)
- 看实验设计，可以从 OML 在 8 GB 笔记本显卡上的固定任务、重复测量与分项报告读起。[OML 中文工程案例](https://alvenx.com/notes/engineering/multimodal-measurement-zh)
