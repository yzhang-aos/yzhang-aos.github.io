---
layout: page
title: Analytical radiative fluxes
img: assets/img/project_prof_6.jpg
importance: 1
category: work
topic: Radiative Transfer
year: 2026
description: >-
  Water vapor is both condensable and a greenhouse gas. This dual role collapses
  the Planck emission in optical depth into a power law.
equation: '\begin{array}{c}
    B_{\tilde\nu} \propto \tau^{\gamma} \\[4pt]
    \gamma = \dfrac{h\nu}{l_v}
    \end{array}'
related_publications: zhang2026analytical
---

Water vapor has two roles in Earth's atmosphere. It is **condensable** and is a **greenhouse gas**. The condensable nature implies that the optical depth of water vapor (roughly proportional to the vertically integrated path) is largely governed by temperature following the Clausius-Clapeyron scaling
\begin{equation}
\tau \sim \exp \left ({-\frac{L_v}{R_vT}}\right).
\end{equation}
As a greenhouse gas, water vapor absorbs and emits at infrared radiation wavenumbers ($\tilde\nu$) governed by the Planck function $B_{\tilde\nu}$, which, when the Wien approximation is taken, yields
\begin{equation}
B_{\tilde\nu}(T) \sim \exp\left(-\frac{h c\, \tilde\nu}{k_B T}\right)
\end{equation}
The two are isomorphic — the same Boltzmann factor $\exp(-E/k_B T)$, differing only in the energy $E$ — because photon occupation and the vapor-to-liquid molecule ratio obey the same statistics. Eliminating temperature between them leaves a power law,
\begin{equation}
B_{\tilde\nu}\big(T(\tau)\big) \approx B_{\tilde\nu}(T_s)\left(\frac{\tau}{\tau_s}\right)^{\gamma},
\qquad
\gamma = \frac{h\nu}{l_v} = \frac{\text{photon energy}}{\text{latent heat per H}_2\text{O molecule}},
\end{equation}
where $T_s$ and $\tau_s$ are the surface temperature and column optical depth. The exponent is small — below about 0.4 across the thermal infrared — because the latent heat of water vapor is larger than the energy an infrared photon carries.

What is this power law good for? Longwave transfer obeys Schwarzschild's equation,
\begin{equation}
\mathrm{d}I_{\tilde\nu} = \big(\pi B_{\tilde\nu}(T) - I_{\tilde\nu}\big)\,\mathrm{d}\tau,
\end{equation}
which becomes analytically solvable once $B_{\tilde\nu}$ is written as an explicit function of $\tau$. The power law does this, giving upward and downward fluxes, and from there, one can derive theories for atmospheric cooling, outgoing longwave radiation, downward longwave radiation, etc. 

For example the column-integrated radiative cooling at each wavenumber follows as
\begin{equation}
Q_{\tilde\nu} \approx \pi B_{\tilde\nu}(T_s)\, \Gamma(1+\gamma,\ \tau_s)\, \tau_s^{-\gamma},
\end{equation}
with $\Gamma$ the lower incomplete gamma function. In the optically thick limit ($\tau_s \gg 1$) this reduces to a pure power law, $Q_{\tilde\nu} \approx \pi B_{\tilde\nu}(T_s)\,\tau_s^{-\gamma}$, whose derivative with respect to $T_s$ vanishes identically, because $\gamma$ is precisely the ratio of the fractional temperature sensitivities of $B_{\tilde\nu}$ and $\tau_s$. This is an analytical statement of Simpson's law: at fixed relative humidity, the outgoing longwave radiation at water-vapor wavenumbers does not change as the surface warms.

Because $\gamma$ is built from the latent heat and radiative properties of the condensing gas, the same power law should carry over to other condensable greenhouse gases and other planetary atmospheres.

<!-- TODO: cover-image-source footer, matching projects 1–2, once a cover image is chosen. e.g.:
<span class="cover-image-source">Cover image source: <a href="...">...</a></span>
<style>
.cover-image-source { font-size: 0.8em; }
</style>
-->
