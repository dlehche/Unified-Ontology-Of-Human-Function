# 人体功能统一本体（UOHF）

## 人体功能的受治理语义与计算本体

[English](README.md) · [UOHF Definition 2.1](https://doi.org/10.5281/zenodo.21630406) · **[18项核心 + 104项具体能力](papers/capacity-system/README.zh-CN.md)** · [形式化框架](papers/formal-framework/README.zh-CN.md) · [“统一”论文](papers/unification/README.md) · [论文总览](papers/README.md) · [版本档案](versions/README.md) · [出版映射](PUBLICATIONS.json) · [本体发布状态](ontology/README.md) · [权利与复用](RIGHTS_AND_REUSE.md) · **[下游 HFWM 仓库](https://github.com/dlehche/Human-Function-World-Model)**

**正式英文名称：** Unified Ontology of Human Function  
**正式简称：** UOHF  
**当前权威总体框架：** UOHF Definition 2.1  
**当前权威出版修订版本：** 2.1.1  
**作者：** 车雷（Lei Che）  
**机构：** 木梯科技（北京）有限公司  
**联系邮箱：** dlehche@gmail.com  
**权威总体框架 DOI：** [10.5281/zenodo.21630406](https://doi.org/10.5281/zenodo.21630406)  
**许可：** 各篇以对应出版记录为准；当前 UOHF 出版物采用 CC BY-NC 4.0

> **人体功能，就是身体被正常调用的能力。**

> **Human function is the body's capacity to be appropriately engaged to meet internal and external demands.**

---

## 本仓库负责什么

本仓库是**人体功能语义层与本体层**的权威公开 GitHub 入口。

UOHF 负责：

- 人体功能根定义与范围；
- Demand、能力、实际功能调用、证据等核心语义区分；
- 本体对象身份、类型边界与受治理关系；
- 公开人体功能能力坐标；
- 人体功能形式语义与计算约束；
- UOHF 版本历史、引用元数据和公开本体边界。

本仓库**不是 HFWM 本身的权威代码/论文仓库**。人体功能世界模型（HFWM）建立在 UOHF 语义基础之上，其世界模型架构、异构模型互操作、Functional Bridge 和 HFWM 专属治理，统一维护在独立的 [Human-Function-World-Model 仓库](https://github.com/dlehche/Human-Function-World-Model)。

---

## 当前权威总体框架

### UOHF Definition 2.1

UOHF Definition 2.1 是当前权威总体框架，恢复人体功能对内部需求与外部需求的完整覆盖，并明确区分人体功能能力、实际发生的调用过程、观察、推断、状态与行动。

- Zenodo：[10.5281/zenodo.21630406](https://doi.org/10.5281/zenodo.21630406)
- 出版修订：**2.1.1**
- 许可：**CC BY-NC 4.0**
- 中文框架正文：[UOHF_DEFINITION_ZH.md](UOHF_DEFINITION_ZH.md)

---

## 人体功能能力体系 Version 1.0

### 18项核心人体功能能力 + 104项具体人体功能能力

第一版能力体系论文把 UOHF 人体功能能力目录作为公开、可引用、可版本化的科学对象发布。

- [论文概览](papers/capacity-system/README.zh-CN.md)
- [中文完整论文](papers/capacity-system/source/zh/README.md)
- [English full paper](papers/capacity-system/source/en/README.md)
- Zenodo：[10.5281/zenodo.21975100](https://doi.org/10.5281/zenodo.21975100)
- 许可：**CC BY-NC 4.0**

18+104 是版本化语义坐标，不是104维可互换分数，也不是104个已经完成验证的量表。正式细粒度本体类型仍为对应 `CORE_CAPACITY` 下的 `SUBCAPACITY` 与 `CAPACITY_COMPONENT`。

---

## 当前 UOHF 专题论文

### 人体功能形式化与计算框架

- Zenodo：[10.5281/zenodo.21721599](https://doi.org/10.5281/zenodo.21721599)
- [中文完整论文](papers/formal-framework/UOHF_Formal_Framework_ZH_V1.0.md)
- [English full paper](papers/formal-framework/UOHF_Formal_Framework_EN_V1.0.md)

### 人体功能统一本体中的“统一”

- Zenodo：[10.5281/zenodo.21635694](https://doi.org/10.5281/zenodo.21635694)
- [论文入口](papers/unification/README.md)

---

## 下游 HFWM 研究体系

**Human Function World Model（HFWM）**是建立在 UOHF 之上的世界模型与模型协作研究体系。HFWM 的源文本、架构、异构模型互操作、Functional Bridge、纵向更新和 HFWM 专属治理，均以独立仓库为权威位置：

**HFWM 仓库：** https://github.com/dlehche/Human-Function-World-Model

当前 HFWM 相关公开论文包括：

- *The Human Function World Model: Modeling the Whole Person Through Human Function Across Tasks, States, Actions, and Longitudinal Change* — DOI：[10.5281/zenodo.22685308](https://doi.org/10.5281/zenodo.22685308)
- *Connecting Human Models Through Human Function: Toward a Common Computational Protocol for Whole-Person Modeling* — DOI：[10.5281/zenodo.23180973](https://doi.org/10.5281/zenodo.23180973)

它们是 UOHF 的下游相关出版物，**不属于 UOHF 自身的版本/出版序列**。

---

## UOHF 解决什么问题

UOHF 不替代医学、生理、康复、运动、心理或其他专业知识。它解决的是人体功能本身的共同语义问题：

- 当前是什么内部或外部 Demand？
- 哪些人体功能能力与之相关？
- 能力与实际功能调用有什么区别？
- 什么是观察、测量、报告，什么是推断？
- 什么证据能够支持某个判断，什么仍然未知？
- 哪些关系属于一般知识，哪些属于具体人的事实？
- 版本、来源、权限与语义变化怎样治理？

目标是让人体功能语义做到**可计算、受约束、可追溯、可审计、可修订**。

---

## 核心语义关系

```mermaid
flowchart LR
    D[内部 / 外部需求] --> RC[所需人体功能能力]
    RC --> C[能力]
    C --> FE[实际功能调用]
    FE --> R[反应 / 表现 / 测量]
    R --> E[证据 / 推断]
    E --> S[证据支持的人体功能状态]
```

这是一张语义组织图，不是通用生物学因果公式。

---

## 从这里开始

| 内容 | 用途 |
|---|---|
| [UOHF Definition 2.1](https://doi.org/10.5281/zenodo.21630406) | 当前权威总体框架 |
| [人体功能能力体系第一版](papers/capacity-system/README.zh-CN.md) | 18项核心 + 104项具体能力 |
| [人体功能形式化框架](papers/formal-framework/README.zh-CN.md) | 数学与计算形式化 |
| [“统一”论文](papers/unification/README.md) | 完整人层级的人体功能概念统一 |
| [论文总览](papers/README.md) | UOHF 专题出版物 |
| [版本档案](versions/README.md) | UOHF 公开框架与专题论文历史 |
| [出版映射](PUBLICATIONS.json) | 机器可读 UOHF 出版元数据 |
| [本体发布状态](ontology/README.md) | 当前公开机器可读本体边界 |
| [HFWM 仓库](https://github.com/dlehche/Human-Function-World-Model) | 下游完整人世界模型与模型互操作研究 |

---

## 当前边界

进入公开目录不表示全部对象已经完成生产生命周期激活、全部关系端点覆盖、评估/干预映射或 Runtime 发布。完整生产本体、关系拓扑、运行规则和真实业务数据不会因为学术论文公开而自动全部开放。

---

## 引用

> Che, Lei. *UOHF Definition 2.1: Unified Ontology of Human Function*. Version 2.1.1. MoveTips Technology (Beijing) Co., Ltd., 2026. DOI: [10.5281/zenodo.21630406](https://doi.org/10.5281/zenodo.21630406).

各篇专题论文的引用元数据维护在对应论文目录中。仓库总体引用信息见 [CITATION.cff](CITATION.cff)。

---

## 著作权与复用

**著作权 © 2026 车雷与木梯科技（北京）有限公司。**

当前 UOHF 出版物采用 **CC BY-NC 4.0**。允许按许可进行学术引用和非商业复用；需要著作权许可的商业使用须另行取得许可。详见 [RIGHTS_AND_REUSE.md](RIGHTS_AND_REUSE.md)。
