# Response in general
Given a linear operator for a field EoM, $Lf(x)=g(x)$, superposition allows me to define $LG(x,\xi)=\delta(x-\xi)$, such that field $f=G\ast g$ for any kind of source.

Examples are electric potential $-\nabla^2\phi=\rho/\epsilon_0$ and wavefunction $\hat{H}\psi=i\partial_t\psi$.

Spectral realization for $\delta(x-\xi)$ is $1/(x-\xi+i\eta)$.

# Another one
Given a set of lattice vectors for atomic coordinates in crystal, periodicity allows me to define $ab=I$, such that ... structure factor. (to be completed)

# Add-ons in response realization

- Brillouin zone sampling, efficiency for desired states
- Fermi function, thermal flunctuation in occupancy (sharp unity-zero variation around Fermi level)

## Fermi Surface
Metal are those Fermi-surfaced, while others not.

Convention breaks once the surface degenerates into line or point.

## sum over states
one is total quantities, the other is weighted sum.


> Ref. Electronic Structure. Martin (2020). KEY: spectral


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
