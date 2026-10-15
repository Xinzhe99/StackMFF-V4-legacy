> [!WARNING]
> **Deprecated / 已废弃 (2026-10).** This repository is no longer maintained. Its method has been merged with the previous StackMFF V3 and redesigned into a new, unified **StackMFF V3** (all-attention, pixel-wise layer classification). The new code, weights and benchmark results will be released in a new repository, which will be linked here. Please use the new release; this code is kept for reference only.
>
> 本仓库已停止维护。其方法已与 旧版 StackMFF V3 合并并重新设计为新的统一版 **StackMFF V3**，新代码、权重与评测结果将在新仓库发布（届时在此处给出链接），请以新版本为准。本仓库仅作存档参考。
>
> The old StackMFF V3 repository has been renamed to [StackMFF-V3-legacy](https://github.com/Xinzhe99/StackMFF-V3-legacy). The name **StackMFF-V3** now belongs to the new, unified release, which will become public together with the paper.
>
> 旧版 StackMFF V3 仓库已更名为 StackMFF-V3-legacy；StackMFF-V3 这一名称现由新的统一版使用，将随论文一同公开。

# StackMFF-V4
# <img src="stackmffv4_framework.jpg" alt="GMFF" height="800" style="vertical-align: middle;"/> 
StackMFF V4 is the deterministic fusion model used in the generative multi-focus image fusion framework [GMFF](https://github.com/Xinzhe99/GMFF). Its training framework is based on [StackMFF V3](https://github.com/Xinzhe99/StackMFF-V3-legacy), with improvements made only in the network architecture. The [StackMFF V3](https://github.com/Xinzhe99/StackMFF-V3-legacy) project provides detailed training instructions and usage guidelines. Therefore, you can train StackMFF V4 by using StackMFF V3 as the base and replacing the network model with the one provided in [GMFF](https://github.com/Xinzhe99/GMFF).
