# NR TBS 计算工具

基于 3GPP **TS 38.214 §5.1.3.2** 的 NR（New Radio）传输块大小（TBS）计算工具。

## 使用

🔗 **在线使用：** [https://hanfy-cscn.github.io/TBS-calc/tbs_calc.html](https://hanfy-cscn.github.io/TBS-calc/tbs_calc.html)

## 功能

- 支持 PRB 范围选择（1~275）
- 支持 3 种 MCS 表（64QAM / 256QAM / 64QAM Low SE）
- 可配置 DMRS、高层开销、缩放因子、层数
- 自动计算每个 MCS × PRB 组合的 N<sub>info</sub> 和 TBS
- 结果可一键复制 CSV
- 内置公式参考区（可折叠）

## 参考

- 3GPP TS 38.214 — NR Physical layer procedures for data
