# 本轮接受 / 调整记录

## 接受的同事修改

### Deck
- 接受了 p4 / p8 / p12 / p16 方法页的“大图 + 右侧图注式 bullets”布局。
- 接受了 p17 的 OOD / E6 压缩写法与 `L19-22 onset` 放回橙色带内的处理方向。
- 接受了 p20 附录标题的单行化处理：`Pointwise vs. pairwise objective mismatch`。

### Papers
- **CodeGRIP**：接受了 §4.7 hierarchical LoRA 重复表述的去冗余改法，改成回指 Table 9。
- **MemStore**：接受了 +17.4pp 范围口径的澄清，把主结果和“pre-RL extractor 组合”区分开。
- **Pathway-Aligned**：接受了 §4.4 stop-gradient necessity 的数值一致性修复，去掉过时的 0.466 / 0.42 说法，改成“within seed variance / contamination control”。
- **Parametric Echo**：保留不改；现有口径已经足够克制且一致。

## 我这轮额外做的修改

- 把四篇 paper 的页脚年份统一修到 **NeurIPS 2026 / 40th Conference**，避免继续显示 2025。
- 更新了 deck 讲稿开头措辞，统一成“正文 19 页 + 附录 4 页”。
- 给 **Pathway-Aligned** 主文真正插入了方法图（paper 内可用的第二张图），并保留原有实证图。
- 重新把四篇 paper 编译了一遍；CodeGRIP 的外部图资源缺失问题通过补齐图文件处理掉了。
- 统一整理成一个新的最终交付包，便于你直接转发或继续 diff 合并。

## 我有意没有接受的点

- 没有把 deck 的讲稿完全保持原样不动；虽然主体说法没大改，但我把页数表述和附录定位补清楚了。
- 没有把 CodeGRIP 再往“benchmark 论文”方向写；继续保持为 **objective mismatch / evaluation framing**。
- 没有把 Parametric Echo 的 claim 再抬高；继续维持“among tested conditions, a key trigger”的边界。
