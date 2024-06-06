---
layout: page
title: Linearity of Earth's outgoing longwave radiation with global mean surface temperature
description: 
img: assets/img/project_prof_3.jpeg
importance: 5
category: work
related_publications: zhang2020linearity
---

In the study of Earth's climate sensitivity, the response of longwave radiation to temperature anomalies is conventionally modeled as a linear damping mechanism. This assumption of linearity is robust across a temperature range of about 50 K. Previous studies have largely relied on single-column models with fixed relative humidity (RH) to explain this linearity, despite the diversity of surface conditions within the climate system. However, globally, there is a remarkably linear relationship between outgoing longwave radiation (OLR) and surface temperature ($T_s$).

We have derived conditions under which this linearity holds for the averages across the entire globe. We show that the analog for fixed RH of a single column is that the global RH histogram is invariant under warming. 


We start with an expression of OLR as follows:
\begin{equation}
\mathrm{OLR}(T_s, \mathrm{RH}) = \alpha T_s +R(\mathrm{RH}),
\end{equation}
where $R$ represents a function of RH. This is equivalent to the expression:
\begin{equation}
\frac{\partial \mathrm{OLR}}{\partial T_s} = \alpha.
\end{equation}
Integrating local OLR values over the joint distribution of surface temperature ($T_s$) and RH yields the global average OLR:
\begin{equation}
\delta \overline{\mathrm{OLR}} = \alpha \delta \overline{T_s} + \int \mathrm{dRH}R(\mathrm{RH})\delta F(\mathrm{RH}),
\end{equation}
where $F$ denotes the global distribution of RH, particularly the column RH in the free troposphere. When the RH distribution remains invariant with warming, the relationship between the global average OLR and the global mean surface temperature reduces to
\begin{equation}
\frac{ \mathrm{d\overline{OLR}}}{\mathrm{d} \overline{T_s} }= \alpha.
\end{equation}
This reduction confirms the applicability of the single-column model to global averages.
The assumption of invariant RH is generally supported by simulations of global warming in global climate models. This implies that the single-column results are broadly applicable to global climate projections. However, significant changes in the RH distribution could potentially change this linearity.
