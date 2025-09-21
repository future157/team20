---
layout: home
title: Team20 毕业设计
---

<!-- Hero Section -->
<div style="position: relative; text-align: center; color: white;">
  <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1200&q=80" alt="Underwater background" style="width: 100%; height: auto; filter: brightness(0.6);" />
  <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);">
    <h1 style="font-size: 2.0rem;">基于偏好多目标优化的多无人水下航行器（UUV）协同反水雷任务规划研究</h1>
    <p style="font-size: 1.2rem;">融合T‑MOEA/D算法与YOLOv9目标检测的UUV路径规划及水雷处置方法</p>
  </div>
</div>

## 项目目标 (Project Objectives)

- 开发基于 T‑MOEA/D 的偏好多目标优化方法用于多UUV协同任务规划。
- 融合 YOLOv9 目标检测算法实现水雷快速识别与定位。
- 设计协同路径规划算法，使多UUV能在复杂海域中避障并完成反水雷巡检。
- 构建模拟平台，验证算法性能并优化任务流程。

## 项目背景 (Background)

在海洋水下环境中，单个无人水下航行器（UUV）的任务易受通信中断和未知障碍的影响。多UUV协同可以提高任务的鲁棒性和效率，国际项目如AOSN和WiMUST都利用多UUV协作完成反潜和水雷清扫任务【697428959012358†L91-L107】。然而，多UUV的路规划需要在线处理未知障碍和通信限制，同时要优化任务分配与航迹规划。项目通过融合偏好多目标优化算法T‑MOEA/D与YOLOv9目标检测，研究面向反水雷任务的协同路径规划及水雷处置技术。

## 项目成员 (Team Members)

- **Shengdan Zheng** — 邮箱：_待填_  
  个人介绍：_占位_
- **Bowen Liu** — 邮箱：_待填_  
  个人介绍：_占位_
- **Yichen Wang** — 邮箱：_待填_  
  个人介绍：_占位_
- **Peiyao Shi** — 邮箱：_待填_  
  个人介绍：_占位_

## 
### 团队任务分工 (Team Task Assignments)

<div style="text-align: center; margin-top: 1rem;">
  <svg width="120" height="120" viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg">
    <circle cx="60" cy="60" r="55" fill="#225D9B"/>
    <circle cx="60" cy="60" r="40" fill="#FFFFFF"/>
    <circle cx="85" cy="40" r="20" fill="#F5C542"/>
  </svg>
</div>

- **Bowen Liu** — 算法设计与优化  
  负责开发、改进和实现 T-MOEA/D；进行参数调优和对比实验；撰写可重复的实验代码和技术文档，为任务规划提供核心技术支持。
- **Yichen Wang** — 目标检测模块  
  基于 YOLOv9 开发水雷检测模型；负责数据收集、清洗与 StyleGAN 增强；完成模型训练和性能优化，输出稳定的检测接口。
- **Peiyao Shi** — 系统架构与仿真  
  构建 UUV 系统架构与硬件集成；搭建 Unity3D 仿真环境和行为脚本；完成任务流程的联合调试与仿真验证。
- **Shengdan Zheng** — 实验与结果分析  
  组织水雷检测/ 处罞与任务分配实验；收集整理实验数据；进行结果分析与报告撰写，总结问题与改进建议。

项目进度记录 (Progress Log)

- 查看全部进度：👉 [进度记录 / Progress](/progress/)

> 使用方式：每完成一个阶段/会议/里程碑，就在 `progress/` 文件夹里新增一条 Markdown 记录。

## 引用 (References)

[1]: 【697428959012358†L91-L107】
