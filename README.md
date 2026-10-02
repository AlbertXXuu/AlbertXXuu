<p align="center">
  <img src="assets/alvenx-wordmark.svg" width="320" alt="AlvenX">
</p>

# AlbertXXuu

I build reproducible AI tools for multimodal evaluation and browser-agent regression. My projects connect runnable code, independent outcome checks, and inspectable results.

[Projects and results](https://alvenx.com/#work) · [Engineering case studies](https://alvenx.com/notes#engineering-cases) · [About AlvenX](https://alvenx.com/about)

## Start with these projects

| Project | What you can inspect | Read the engineering case |
| --- | --- | --- |
| [BrowserAgentRegression](https://github.com/AlbertXXuu/BrowserAgentRegression) | A local browser-agent lab with independent DOM checkpoints and controlled interface changes. Its frozen deterministic reference driver passed 36/36 task/variant attempts. | [Browser lifecycle and independent scoring](https://alvenx.com/notes/engineering/browser-agent-independent-scoring) |
| [OpenMultimodalLab](https://github.com/AlbertXXuu/OpenMultimodalLab) | Two pinned VLM backends evaluated on 102 synthetic tasks, with three measured repetitions per backend and task on a recorded RTX 4060 Laptop. | [Multimodal measurement on an 8GB GPU](https://alvenx.com/notes/engineering/multimodal-measurement) |
| [ReproLock](https://github.com/AlbertXXuu/ReproLock) | An experimental Playwright verifier binding reviewed tests, exact application revisions, build inventories, and cleanup. The DrawDB case includes an ordinary Playwright control. | [Verified before and after browser regressions](https://alvenx.com/notes/engineering/verified-browser-regression) |

The articles explain the problem, implementation choices, verification and measured limits. Source repositories retain the original evidence and reproduction instructions. Projects are developed with AI tooling; the published records distinguish generated candidates, controlled experiments and independently checked outcomes.

## Research and graphics experiments

- [PhysGauge](https://github.com/AlbertXXuu/PhysGauge): controlled collision worlds for checking how video metrics respond to known physical violations.
- [GeometryAudit](https://github.com/AlbertXXuu/GeometryAudit): recorded foundation-geometry runs and independent relative-pose calculations. The original reliability-adapter candidate was retired after a prior-art review; its evidence remains available.
- [SpatialSceneLab](https://github.com/AlbertXXuu/SpatialSceneLab): a first scene-package experiment with editable authored objects, explicit units and frames, GLB round-trip checks and a separate retained-reconstruction coordinate audit. [English and Chinese stage reports](https://github.com/AlbertXXuu/SpatialSceneLab/tree/main/reports) describe its measured limits.

ReproLock's [test repair experiment](https://github.com/AlbertXXuu/ReproLock/tree/main/spikes/test-healing-preservation) separates candidate test outcomes from independent business-state observations, with authored controls and one recorded model proposal replay.

Research status, input conditions and current limits are shown alongside each result on [alvenx.com](https://alvenx.com).

## 简体中文

我围绕多模态评测与浏览器 Agent 回归开发可复现的 AI 工具，将可运行代码、独立验收和结果记录连起来。

建议先读三个工程案例：

- [BAR 浏览器生命周期与独立评分](https://alvenx.com/notes/engineering/browser-agent-independent-scoring-zh)
- [OML 在 8GB 显存上的多模态测量](https://alvenx.com/notes/engineering/multimodal-measurement-zh)
- [ReproLock 浏览器回归的修复前后验证](https://alvenx.com/notes/engineering/verified-browser-regression-zh)

这些文章说明遇到的问题、实现选择、验证和测量范围；源码仓库保留原始证据与复现步骤。开发中使用 AI 工具，生成的候选、控制实验与独立核验结果分别记录。

[SpatialSceneLab 中文阶段报告](https://github.com/AlbertXXuu/SpatialSceneLab/blob/main/reports/STAGE-1.zh-CN.md)记录对象编辑、单位与坐标导出控制；[ReproLock 中文研究记录](https://github.com/AlbertXXuu/ReproLock/blob/main/docs/research/test-healing-preservation.zh-CN.md)说明测试修复后业务错误检测能力的实验口径。
