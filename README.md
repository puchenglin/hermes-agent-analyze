<p align="center">
  <img src="assets/banner.png" alt="Hermes Agent" width="100%">
</p>

# Hermes Agent Analyze ☤

> [!IMPORTANT]
> **Fork 说明：源码分析仓库**
>
> 本仓库 fork 自 Hermes Agent 官方仓库 [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)，不是官方发布仓库。
>
> 本仓库主要用于深入分析学习 Hermes Agent 源码，分阶段分析文档放在 [`source_code_analyze/`](source_code_analyze/) 目录下。
>
> 对应源码版本：`hermes-agent 0.13.0`；源码分析基线提交为 `78b0008f4`（`2026-05-08`，`fix(gateway): also catch restart TimeoutExpired; friendly message`）。本 fork 在该源码基线之上增加源码分析文档和说明。

---

## 源码分析目录

本 fork 的源码分析文档位于 [`source_code_analyze/`](source_code_analyze/)：

| 阶段    | 主题                                                                                             |
| ------- | ------------------------------------------------------------------------------------------------ |
| Phase 0 | [Hermes Agent 源码结构分析](source_code_analyze/phase0_source_structure_analysis.md)             |
| Phase 2 | [AIAgent 主循环深入分析](source_code_analyze/phase2_main_loop_analysis.md)                       |
| Phase 3 | [工具执行子系统深入分析](source_code_analyze/phase3_tool_execution_subsystem.md)                 |
| Phase 4 | [工具注册与工具暴露链路深度分析](source_code_analyze/phase4_tool_registration_exposure_chain.md) |
| Phase 5 | [Memory 子系统深度分析](source_code_analyze/phase5_memory_deep_analysis.md)                      |
| Phase 6 | [自进化机制深度分析](source_code_analyze/phase6_self_evolution_mechanism_analysis.md)            |
| Phase 7 | [Context 管理深度分析](source_code_analyze/phase7_context_management_deep_analysis.md)           |

---
