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

Dielectric function and the random-phase approximation

$$\boxed{\epsilon (\omega,q) = 1 - \frac{e^2}{2\epsilon_0 q}\sum_{n,n',\vec{\mathrm{k}}}\frac{\left\vert\langle\vec{\mathrm{k}},n\vert e^{-i\vec{\mathrm{q}}\cdot\vec{\mathrm{r}}}\vert\vec{\mathrm{k}}+\vec{\mathrm{q}},n'\rangle\right\vert^2}{E_{\vec{\mathrm{k}}+\vec{\mathrm{q}},n'}-E_{\vec{\mathrm{k}},n}-\hbar\omega-i\hbar/\tau_{n,n'}}\times\left[f\left(E_{\vec{\mathrm{k}}+\vec{\mathrm{q}},n'}\right)-f\left(E_{\vec{\mathrm{k}},n}\right)\right]}$$

- (3D) $\frac{4\pi e^2}{q^2}$ - (2D) $\frac{2\pi e^2}{q}$
- (Hartree) $\frac{2\pi e^2}{q}$ - (SI) $\frac{e^2}{2\epsilon_0 q}$


### Yukawa screening

interaction with short range cut-off

$v(r,\kappa)=e^2 e^{-\kappa\cdot r}/r$

Fourier transform of interaction potential 

$$v_q(\kappa)\equiv\int v(r,\kappa) e^{-i\vec{q}\cdot\vec{r}} d\vec{r}$$

### easy exercise

- Coulomb potential (2D) $V_q = \lim_{\kappa\to 0}v_q(\kappa) = \lim_{\kappa\to 0} \frac{2\pi e^2}{\sqrt{q^2+\kappa^2}} = 2\pi e^2/q$
- Coulomb potential (3D) $V_q = \lim_{\kappa\to 0} \frac{4\pi e^2}{q^2+\kappa^2} = 4\pi e^2/q^2$

### ✦ 课本要点速记
- Single electron, decorated with Coulomb screening potential
- Plasma oscillations, excited by long wavelength part of Coulomb

### ✦ 理解 / 笔记
- Debye length as the exponential decay rate for screening  
- **RPA(随机相近似)** 推导等离子体色散：低 $q$ 区近似常数，随 $q$ 增大出现 Landau 阻尼。  
> TODO：整理 RPA 推导步骤、Landau 阻尼物理图像  


---

## 参考 / 扩展阅读
- Pines, Bohm. *A Collective Description of Electron Interactions* (Phys. Rev. 1952)  
- Maier. *Plasmonics: Fundamentals and Applications* (Springer 2007)

> Gray tin (1972) : 10.1103/PhysRevB.5.397

23. H. Ehrenreich and M. H. Cohen, Phys. Rev. 115, 786 (1959).
24. P. Nozieres and D. Pines, Nuovo Cimento 9, 470 (1958).
25. P. Nozieres and D. Pines, Phys. Rev. 109, 762 (1958).

> beyond (2012) : 10.1103/PhysRevE.85.036401

polarization, conductivity and structure factor

> several limiting cases (2024) : 10.1016/j.jpcs.2024.112470

optical, high momentum transfer, and static limits




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
