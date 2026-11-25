<div align="center">

# 明鉴 AOS · Mingjian AOS

**Agent OS for code intelligence.** Tool bus · permissions · tasks · long-term memory · personal gateway.

</div>

---

### What we are building

**ACD** — a multi-source, function-level call graph fusing static parsing (with macro expansion), runtime instrumentation, disassembly and function-pointer registry analysis.

Validated end to end on **FFmpeg 9.1-dev**:

`114,175 edges` · `38,697 callers` · `30,259 edges confirmed by ≥2 independent sources`

The methods, graph, viewer, verification scripts and caliber documents ship together in `acd-callgraph` v4.0. Edge / node / source counts are recomputable from the shipped graph; reach and anchor rates state exactly which extra artifacts they require.

**Research preview.** Edge-level precision / recall is not measured; known gaps and failed checks are published with the graph.

### Rules we keep

- **A number without its denominator is not a result.**
- **Known limits are listed before strengths.**
- **False-positive filters and unresolved edges are published too.**
- **Corrections are versioned**, never silently overwritten.

### 中文

**明鉴 AOS** 是面向代码智能的 Agent 操作系统：工具总线、权限、任务、长期记忆与个人网关；不做模型，也不做 IDE。

首个对外交付是 **ACD 引擎**：多源合流的函数级调用图，在 FFmpeg 9.1-dev 上完成端到端实证。**11.4 万条边，每条边带出处；边 / 节点 / 来源计数可当场复算，触达率与行号一致率明确标注所需的外部产物。** 已知边界、失败判据与修正记录一并公开。

这是研究预览：边级 precision / recall 未测，缺口和失败判据随图一并公开。

### Contact

`mingjian_aos@163.com`

---

<sub>Next public release: <code>acd-callgraph</code> v4.0 · CC BY 4.0 (data &amp; docs) / MIT (scripts)</sub>
