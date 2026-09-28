# Theorem A_cond

Conditional compact-support physical-vacuum realisation of a radial isentropic Euler implosion. Not an existence theorem. Not Navier--Stokes. Not a Clay problem.

## Statement

Let $d\in\{2,3\}$ and $\gamma\ge 2$. Let $(\bar\rho,\bar u)$ be a $C^\infty$ radial self-similar implosion of Merle--Rapha\"el--Rodnianski--Szeftel (2022) or Buckmaster--Cao-Labora--G\'omez-Serrano (2025), singular only at $(r,t)=(0,0)$. Let $\mathcal{K}=\{(t,r):r\le Z_s(-t)^\lambda\}$ be the sonic cone, with $\dot r_s=\bar u-\bar c$ on $\partial\mathcal{K}$.

**Hypothesis C4.1.** On the vacuum sliver $\{\omega=1\}$, with $\varphi=\partial_t^4 w$,
$$\Bigl|\int_{\mathrm{sliver}}(\partial_t^3 p)\,v_y\,\varphi_y\,dy\Bigr|
\le C(M_0)\mathcal{E}+\tfrac1{32}\kappa\int\rho_0^2|\varphi_y|^2.$$

**Conclusion, assuming C4.1.** There exists a compactly supported physical-vacuum solution $(\rho,u)$ of radial isentropic Euler on $[t_0,0)$ such that
- $(\rho,u)=(\bar\rho,\bar u)$ on $\mathcal{K}$,
- $\rho=0$ for $r\ge R(t)$,
- $R(t)>r_s(t)$ on $[t_0,0)$.

The solution is classical on $\{0<r<R(t)\}$ and of physical-vacuum regularity at $r=R(t)$.

## Proved in this archive (not conditional)

- L1: jet map $D_t J_+$, $\det=c^6>0$.
- L2: $Z_0$ first, then $L$; Hermite $C_*=35/16$.
- L3: one-sided Hardy on $d=1-y$ with vanishing trace at $y=1$.
- L4a: unweighted $H^2\hookrightarrow C^1$ on $\{\omega=0\}\cup I_\omega$.
- C4.2--C4.4: remaining acoustic commutator rows on the model energy.
- L8: Kato uniqueness on $\mathcal{K}$.
- Lagrangian momentum form; $V_*=\{\varphi\in H^1:\varphi(a_*)=0\}$; $V_{00}$ withdrawn.

## Open (the hypothesis)

C4.1 is the sliver pairing after IBP. Three $L^2$ factors do not H\"older-close. The missing factor is one $L^\infty$ of strain. Coutand--Shkoller (2011) energy (1.13) contains unweighted $H^{2-s/2}$ that would supply it on a two-vacuum-end interval. That estimate is not typed on $V_*$.

## Not claimed

- Unconditional Theorem A.
- $\gamma\in(1,2)$.
- 3D incompressible Navier--Stokes, Clay A/B/C/D, stability, $t>0$.
