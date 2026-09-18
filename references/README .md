# References

本目录用于维护 TEM 项目的核心参考文献索引。

这里主要记录**文献的基本信息、与本项目的关系及当前阅读状态**。详细的逐篇精读笔记后续统一放入 `docs/literature/`，不在本文件中重复展开。

---

## 1. 项目地质背景

### Liu et al. (2025)

**中文题目：** 新疆库拜盆地北缘古河湖相锆石砂矿的发现实现我国锆矿找矿突破

**英文题目：** *The Discovery of a Paleo-Fluvio-Lacustrine Facies Zircon Deposit on the Northern Margin of the Kubai Basin in Xinjiang Represents a Breakthrough in the Exploration of Zircon Deposits in China*

**期刊：** 地球科学（Earth Science）

**卷期：** 50(6), 2452–2456

**DOI：** 10.3799/dqkx.2025.092

**与本项目的关系：**

- 用于了解新疆库拜盆地北缘锆石砂矿的地质背景；
- 帮助理解矿体空间展布、找矿预测及三维地质建模的实际需求；
- 该文属于地质背景与找矿成果文献，不属于 TEM 数据处理或反演方法论文。

**当前阅读状态：** 已完成第一遍背景阅读。

---

## 2. TEM 研究进展

### Farquharson et al. (2023)

**题目：** *Advances in transient electromagnetic methods*

**中文暂译：** 瞬变电磁法研究进展

**作者：** Colin G. Farquharson, Xiangyun Hu, Qinghua Huang, Xiu Li, Jianhui Li, Guoqiang Xue, Changchun Yin

**期刊：** *Journal of Geophysics and Engineering*

**卷期页码：** 20(6), 1305–1307

**DOI：** 10.1093/jge/gxad089

**文献类型：** Editorial / 专题导读

**主要内容：**

该文概述了近年来 TEM 的主要研究方向，重点涉及：

- 仪器与数据采集；
- 数据去噪与处理；
- 成像、反演与解释；
- 工程和地质应用；
- 无人机等新型观测平台；
- 机器学习在噪声抑制和数据解释中的应用。

文章同时指出，三维 TEM 反演仍具有较高计算成本，因此实际解释中仍大量依赖一维方法；复杂环境中的噪声处理也是重要研究问题。

**与本项目的关系：**

用于建立 TEM 研究方向的整体认识，并帮助确定后续可能重点关注的方向：数据预处理、反演、多源融合及三维建模。

**当前阅读状态：** 已完成第一遍阅读；后续可结合专题中的具体研究论文继续扩展。

---

## 3. TEM 反演方法

### Xue et al. (2020)

**题目：** *Development of the Inversion Method for Transient Electromagnetic Data*

**中文暂译：** 瞬变电磁数据反演方法研究进展

**作者：** Guoqiang Xue, Hai Li, Yiming He, Junjie Xue, Xin Wu

**期刊：** *IEEE Access*

**卷页：** 8, 146172–146181

**DOI：** 10.1109/ACCESS.2020.3013626

**主要内容：**

该文系统总结了 TEM 数据反演方法的发展，涉及：

- 确定性反演；
- 约束反演；
- 联合反演；
- 随机/概率类反演；
- 粒子群等智能优化方法；
- Bayesian 反演；
- TEM 成像与反演的发展方向。

文章强调，TEM 反演的核心任务是由观测电磁响应恢复地下电阻率结构，而反演具有非唯一性，因此需要通过正则化、先验约束或多源数据联合等方式提高结果稳定性和可信度。

**与本项目的关系：**

与当前学习的一维层状模型、正演、数据失配、正则化和反演非唯一性直接对应，是后续学习传统 TEM 反演方法的重要入门文献。

**当前阅读状态：** 已完成第一遍概览；后续重点精读反演基本理论、确定性反演及约束/联合反演相关部分。

---

## 4. 后续文献整理规则

后续新增文献时建议统一记录以下信息：

```text
作者 + 年份
题目
期刊 / 会议
DOI / 官方链接
文献类型
主要解决的问题
使用的数据
核心方法
主要结论
与本项目的关系
当前阅读状态
```

阅读状态可统一标记为：

- `To Read`：待阅读
- `First Pass`：已完成第一遍浏览
- `Deep Read`：已精读
- `Reproduced`：已尝试复现相关方法

---

## 5. 当前重点阅读路线

```text
TEM 总体研究方向
        ↓
Farquharson et al. (2023)
        ↓
TEM 反演方法体系
        ↓
Xue et al. (2020)
        ↓
结合公开数据学习传统一维反演
        ↓
进一步阅读预处理 / 去噪 / 联合反演 / 三维反演文献
```

当前阶段优先把传统数据处理和一维反演流程跑通，再根据实际数据特点确定后续科研重点。
