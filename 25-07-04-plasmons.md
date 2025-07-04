---
title: 等离子体与电子等离体  
description: 《凝聚态物理基础》§ 4.1.3 & § 4.3 学习笔记  
date: 2025-07-04           # 可省；写了方便以后按日期排序  
---

# 4 电子与等离子体相关章节笔记

> **教材**：樊晓峰编，《凝聚态物理基础》，科学出版社 (2025.03)  
> **覆盖**：§ 4.1.3 金属电子量子论的应用（之五：电子等离体）  
> § 4.3 多体电子关联（之五：等离子体振荡）

---  

## 4.1.3 金属电子量子论的应用（五）——电子等离体

### ✦ 课本要点速记
1. **等离体(plasmon)的定义**：自由电子气在**集体振荡**模式下的激发；可视作带电流体中的纵向声子。  
2. **色散关系**  
   $$
     \omega_p = \sqrt{\frac{n e^2}{\varepsilon_0 m_\mathrm{e}}}
   $$  
   其中 $n$ 为电子密度。  
3. **屏蔽效应**：在金属内部，等离体振荡导致外加电场被指数衰减（德拜长度）。  
4. **实验观测**：EELS（电子能量损失谱）中出现典型 10–20 eV 损失峰。

### ✦ 我的理解 / 疑问
- **类比**：把电子气想成水面——局域扰动→涟漪；集体扰动→整体波动 ↔ plasmon。  
- 对比声子：声子在离子晶格；plasmon 在电子气。二者可耦合成 **极化子 (polaritons)**。  
- 计算题：若 $n = 8.5 \times 10^{28}\,\mathrm{m^{-3}}$（典型铝），$\omega_p$ ≈ 15 eV，对应波长约 80 nm，正好落在紫外区。

---

## 4.3 多体电子关联（五）——等离子体振荡

### ✦ 课本要点速记
- **RPA(随机相近似)** 推导等离子体色散：低 $q$ 区近似常数，随 $q$ 增大出现 Landau 阻尼。  
- **表面等离体(SPP)**：界面处的等离体‐光耦合模式；等离子体振荡可被光激发，用于超分辨显微。  

### ✦ 我的理解 / 笔记
> TODO：整理 RPA 推导步骤、Landau 阻尼物理图像  
> TODO：查 2024 Nature Photonics 关于 SPP 在钙钛矿中的新进展

---

## 参考 / 扩展阅读
- Pines, Bohm. *A Collective Description of Electron Interactions* (Phys. Rev. 1952)  
- Maier. *Plasmonics: Fundamentals and Applications* (Springer 2007)

<!-- 可选：告诉 MathJax 我们要用 $...$ 做行内定界符 -->
<script>
  window.MathJax = {
    tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}
  };
</script>

<!-- 真正加载 MathJax v3（官方 CDN） -->
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>
