# Compact support of an isentropic implosion ($\gamma\ge 2$)

Companion to `implosion_gamma2.tex`. Not Clay. Not Navier--Stokes.

## Claim

Radial isentropic Euler, $\gamma\ge 2$. Take a $C^\infty$ self-similar implosion (MRSZ 2022 / BCLGS 2025) that blows up only at the origin. Glue a physical-vacuum collar so the solution is compactly supported, exact on the sonic cone $\mathcal{K}=\{r\le Z_s(-t)^\lambda\}$, and $R(t)>r_s(t)$.

## What is proved here

- Bridge: $Z_0$ then $L$, Hermite $C_*=35/16$, jet map $\det=c^6>0$.
- Lock $\sigma(t)=\bar J_+(t,\bar\eta(t,\bar a_*))$.
- Trial space $V_*=\{\varphi\in H^1:\varphi(a_*)=0\}$. Edge free.
- Kato uniqueness on $\mathcal{K}$ because $\dot r_s=\bar u-\bar c$.
- Cutoff viscosity: no layer at the lock; interface $O(\kappa)$.

## What is cited, not re-proved

Coutand--Shkoller, *Comm. Pure Appl. Math.* 64 (2011): Lemma 3.1 and the $\gamma=2$ model energy (1.13), transferred to a chart with one lock and one vacuum end. Theorem 8.1 is not used.

## What is not claimed

- Unconditional existence from first principles.
- $\gamma\in(1,2)$ (fractional vacuum weights; see `TRANSFER_81.md` in the working notes, not this letter).
- 3D incompressible Navier--Stokes or any Clay problem.
