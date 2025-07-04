---
title: 等离子体与电子等离体  
description: 《凝聚态物理基础》§ 4.1.3 (5) & § 4.3.5 学习笔记  
date: 2025-07-04           # 可省；写了方便以后按日期排序  
---

# 电子与等离子体相关章节笔记

> **教材**：樊晓峰编，《凝聚态物理基础》，科学出版社 (2025.03)  
> **覆盖**：§ 4.1.3 金属电子量子论的应用（之五：电子等离体）  
> § 4.3 多体电子关联（之五：等离子体振荡）

---  

## Electron `gas` of comparable charge density

### ✦ 课本要点速记
1. Mobile charge, at least one type
2. Longitudinal and collective oscillations, excited due to heat or EM field
3. Plasmon, as plasma energy quantized
4. Modes, bulk one via high-energy electron beam, surface one as polariton or localized
5. EM wavelength (10 pm ~ 1 km, 500 nm), electron mean free path (1 nm ~ 10 um, 10 nm/impurity)
6. Dispersion  $\omega = \sqrt{\omega_p^2 + c^2 k^2}$

### ✦ 理解 / 疑问
- hybrid light-matter quasiparticles
    - lattice vibrations (transverse optical phonon) in polar dielectrics (like SiC, GaAs, hBN)
    - collective oscillations of free electrons (surface plasmon) on metal-dielectric interface
- Typical loss peaks in Electron Energy Loss Spectrum, $\omega_p$ ≈ 15 eV for aluminum
- TODO: Check electron number density and energy-wavelength correspondence

---

## Coulomb in action

### ✦ 课本要点速记
- Single electron, decorated with Coulomb screening potential
- Plasma oscillations, excited by long wavelength part of Coulomb

### ✦ 理解 / 笔记
- Debye length as the exponential decay rate for screening  
- **RPA(随机相近似)** 推导等离子体色散：低 $q$ 区近似常数，随 $q$ 增大出现 Landau 阻尼。  
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
