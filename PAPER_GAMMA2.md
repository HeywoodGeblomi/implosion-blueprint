# Compact support of an isentropic implosion ($\gamma\ge 2$)

Companion to `implosion_gamma2.tex` and `THEOREM_A_COND.md`. Not Clay. Not Navier--Stokes.

## Claim

**Theorem A_cond.** Radial isentropic Euler, $\gamma\ge 2$, $d\in\{2,3\}$. If Hypothesis C4.1 holds, a physical-vacuum collar can be glued to a $C^\infty$ self-similar implosion (MRRS 2022 / BCLGS 2025) so the solution is compactly supported, exact on $\mathcal{K}=\{r\le Z_s(-t)^\lambda\}$, and $R(t)>r_s(t)$.

## Hypothesis C4.1

On the vacuum sliver, with $\varphi=\partial_t^4 w$,
$$\Bigl|\int(\partial_t^3 p)\,v_y\,\varphi_y\Bigr|
\le C(M_0)\mathcal{E}+\tfrac1{32}\kappa\int\rho_0^2|\varphi_y|^2.$$
This pairing is not proved. It is the remaining obstruction.

## What is proved here

- Bridge: $Z_0$ then $L$, Hermite $C_*=35/16$, jet map $\det=c^6>0$.
- Lock $\sigma(t)=\bar J_+(t,\bar\eta(t,\bar a_*))$.
- Trial space $V_*=\{\varphi\in H^1:\varphi(a_*)=0\}$. Edge free.
- One-sided Hardy (L3) on this chart.
- Kato uniqueness on $\mathcal{K}$ because $\dot r_s=\bar u-\bar c$.
- C4.2--C4.4 on the model energy.

## What is not claimed

- Unconditional existence.
- Transfer of Coutand--Shkoller energy (1.13) to $V_*$.
- $\gamma\in(1,2)$.
- 3D incompressible Navier--Stokes or any Clay problem.
