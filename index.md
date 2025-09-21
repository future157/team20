---
layout: home
title: Team20 毕业设计
---

<style>
body {
  background-image: url('{{ "/uuv_background.jpg" | relative_url }}');
  background-size: cover;
  background-attachment: fixed;
  background-repeat: no-repeat;
}
.main-content {
  background: rgba(255,255,255,0.90);
  padding: 2rem;
  border-radius: 12px;
  margin: 2rem auto;
  max-width: 900px;
}
.hero {
  text-align: center;
  margin-bottom: 1.5rem;
}
.hero-logo-title {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1rem;
}
.hero-logo-title h1 {
  font-size: 1.8rem;
  margin: 0;
  line-height: 1.3;
}
.hero-logo-title p {
  font-size: 1rem;
  margin-top: 0.3rem;
}
</style>

<div class="main-content">
  <div class="hero">
    <div class="hero-logo-title">
      <svg width="80" height="80" viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg">
  <circle cx="60" cy="60" r="55" fill="#2250D5" />
  <circle cx="60" cy="60" r="40" fill="#FFFFFF" />
  <circle cx="85" cy="40" r="20" fill="#FFC542" />
</svg>
      <div>
        <h1>基于偏好多目标优化的多无人水下航行器 (UUV) 协同反水雷任务规划研究</h1>
        <p>融合 T‑MOEA/D 算法与 YOLOv9 目标检测的 UUV 路径规划及水雷处置方法</p>
      </div>
    </div>
  </div>

## 项目目标 (Project Objectives)

- **开发基于 T‑MOEA/D 的偏好多目标优化算法** 用于多 UUV 协同任务规划，使得各项指标均衡而灵活。
- **融合 YOLOv9 的目标检测模块** 实现水雷目标的快速识别与定位，并通过 StyleGAN 增强训练数据。
- **设计高效路径规划策略**，使多 UUV 能在复杂海域中协同行动并完成水雷搜索与处置任务。
- **构建仿真平台**，强化算法在复杂条件下的任务验证。

## 项目背景 (Background)

在海洋水下环境中，单个无人水下航行器 (UUV) 的任务易受通信中断和障碍物的影响。多 UUV 协作可以显著提高任务的鲁棒性和效率，国际项目如 AOSN 和 WiMUST 都利用多 UUV 协作完成资源探测和反潜扫雷任务【697428959012358†L91-L107】。然而，多 UUV 的路径规划需要在实时处理大量环境数据的同时保证协同优化多目标指标，如航程、能耗和风险。为此，我们采用偏好多目标优化算法 T‑MOEA/D 与 YOLOv9 目标检测相结合，研究面向反水雷任务的协同路径规划及水雷处置方法。

## 项目成员 (Team Members)

- **Shengdan Zheng 郑盛丹** — 邮箱：<a href="mailto:1300520087@qq.com">1300520087@qq.com</a><br>
  来自大连海事大学机械设计制造及其自动化专业。负责实验与结果分析，组织实验设计，收集处理数据并撰写总结报告。
- **Bowen Liu 刘博文** — 邮箱：<a href="mailto:61633317@qq.com">61633317@qq.com</a><br>
  来自大连海事大学机械设计、制造与自动化专业。负责算法设计与优化，开发改进 T‑MOEA/D，进行参数调整和对比实验，为任务规划提供核心支撑。
- **Yichen Wang 王伊晨** — 邮箱：<a href="mailto:13330316606@163.com">13330316606@163.com</a><br>
  来自大连海事国际联合学院机械设计、制造与自动化专业 2 班。负责目标检测模块，基于 YOLOv9 开发水雷检测模型，并负责数据采集、清洗及 StyleGAN 增强等。
- **Peiyao Shi 史培垚** — 邮箱：<a href="mailto:1961312158@qq.com">1961312158@qq.com</a><br>
  来自大连海事国际联合学院机械设计、制造与自动化专业 1 班。负责系统架构与仿真，搭建 UUV 系统架构与硬件集成，构建 Unity3D 仿真环境并撰写行为脚本，完成任务流程仿真与验证。

## 团队任务分工 (Team Task Assignments)

- **Bowen Liu – 算法设计与优化**：负责算法开发、改进和实现 T‑MOEA/D；进行参数调优和对比实验；撰写可复现的实验代码和技术文档，为任务规划提供核心支持。
- **Yichen Wang – 目标检测模块**：负责目标检测模块的设计与算法改进；实现水雷 YOLOv9 检测并输出稳定检测接口；负责数据集构建、清洗及 StyleGAN 增强，并完成模型训练与性能优化。
- **Peiyao Shi – 系统架构与仿真**：负责 UUV 系统架构与硬件集成；搭建 Unity3D 仿真环境和行为脚本；完成任务流程的联合调试和验证，并提供仿真支持。
- **Shengdan Zheng – 实验与结果分析**：负责实验设计与数据收集；开展实验和结果分析；撰写报告总结并提出改进建议。

## 项目进度记录 (Progress Log)

- 查看全部进度：👉 <a href="{ '/progress/' | relative_url }">项目进度记录 / Progress</a>

> 使用方式：每完成一个阶段/会议/里程碑，就在 `progress/` 文件夹中新建一条 Markdown 记录。

## 引用 (References)

[1]: 【697428959012358†L91-L107】 多 UUV 协同任务与路径规划研究

</div>
