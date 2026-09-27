# Compact support of an isentropic implosion
Conditional on the Theorem 8.1 pairings in §4.

## §1 Setting

Radial isentropic Euler, d in {2,3}, gamma > 1.
Profile: Merle-Raphael-Rodnianski-Szeftel, Ann. of Math. 196 (2022),
or Buckmaster-Cao-Labora-Gomez-Serrano, Forum of Math, Pi 13 (2025).
Sonic ray Z = Z_s, r_s(t) = Z_s (-t)^lambda.
Collar [r_br, R_0], physical vacuum at R_0.
Lock set S: J_+(t, a_*) = sigma(t) on [t_0, 0),
sigma(t) = Jbar_+(t, etabar(t, abar_*)).

## §2 Stretched bridge

Order: Z_0 first, then L. No circular dependence.
Tail: r_in = Z_0 (-t_0)^lambda, Z_0 large so
max_{k=1,2,3} |d_r^k (u,c)| at r_in < Lip_*/8.
Then L > (35/16) |q0_br - q0_in| / (Lip_*/2).
Map D_t J_+ = -c d_r J_+ - c (d-1)/r u, det = c^6 > 0.
Degree-7 Hermite, C_* = 35/16.
Z_Gamma(t_0) > Z_s, mu(t_0) > 0.
Lip_* = min(1/|t_0|, mu(t_0)(-t_0)^{-lambda}/4).

## §3 Variational formulation

V_* = { phi in H^1(I) : phi(a_*) = 0 }.
Not V_00. The edge is free: v(1) = Rdot.
Operator -d_y(rho0^2 d_y ·) on L^2_rho0,
Dirichlet at a_*, natural rho0^2 d_y psi -> 0 at y=1.
Cutoff omega = 0 near a_*, omega = 1 near vacuum.
Lift v_L supported in {omega = 0}.

Working basis: Option B. phi_k(y) = (y-a_*)^k, k>=1.
[P_N, d_y(rho0^2 d_y)] is bounded at each finite N by 1D traces:
|int [P_N, d_y(rho0^2 d_y)] w * d_t^4 w| <= C(M0,N) E^{(N)}.
Uniform-in-N bounds come from the weak form on V_*, not from this C(M0,N).
Option A unused.

## §4 Energy estimates

Split E^{(N)} = E_in^{(N)} + E_vac^{(N)}.
Fluxes at a_* die by phi(a_*) = 0. Fluxes at y=1 die by p(1)=rho0(1)=0.

gamma >= 2, model energy a0 = 0:
d/dt (E_in^{(N)}+E_vac^{(N)}) + (7/8) kappa int_I omega rho0^2 |d_t^4 d_y w^{(N)}|^2
<= C(M0) (E_in^{(N)}+E_vac^{(N)}) + C ||sigma||_{W^{4,infty}}^2.
Drop the (7/8) dissipation to recover E-dot <= C1 E + C2.

gamma in (1,2): add the Theorem 8.1 sum
sum_{a=0}^{a0} || sqrt(d)^{1+1/(gamma-1)-a} d_t^{4+a0-a} d_y w^{(N)} ||_{L^2({omega=1})}^2,
d = 1-y, a0 from 1 < 1 + 1/(gamma-1) - a0 <= 2.

C_4 table, tested against d_t^4 w:
- j=1: int 4(-J^2 v_y) (d_y d_t^3 p) (d_t^4 w).
  L^infty: J^2 v_y by H^2 into C^1. L^2: Lemma 3.1 on d_t^3 p in H_0^1.
- j=2,3: velocity-jet pairings from E_vac, H^2 into C^1.
- j=4: int (d_y p)(d_y d_t^3 w)(d_t^4 w)
  via ||d_y p / rho0||_infty and the rho0-weighted jet from Theorem 8.1
  (gamma >= 2: model energy).

sum_j |int_{omega=1} C(4,j) (dt^j J)(dy dt^{4-j} p)(dt^4 w)|
<= C(M0) E_vac^{(N)} + (1/8) kappa int omega rho0^2 |dt^4 dy w^{(N)}|^2.

Citation: Coutand-Shkoller, CPAM 64 (2011), Lemma 3.1 and Theorem 8.1.
Not Theorem 1.1 (both ends vacuum).
Working space V_*. Notes that say V_00 are withdrawn.

T^* = min( |t_0|, C(M0)^{-1} ln(1 + C(M0) M_0 / (C(M0) M_0 + C ||sigma||_{W^{4,infty}}^2)) ).

## §5 Continuation and the theorem

Mesh t_k = t_0 + k T^*, K = ceil(|t_0|/T^*) (H2).
C(M0) and ||sigma||_{W^{4,infty}} stay finite as t -> 0-:
the collar sits in {r >= r_in > 0}, the tail, outside the sonic ray.

N -> infinity, kappa -> 0.
w^{(N)} in L^infty(t0,0; V_*), d_t w^{(N)} in L^2(t0,0; L^2_rho0).
Aubin-Lions on {omega=1}; Rellich-Kondrachov on {omega=0}.
Strong C^0([t0,0) x I) away from y=1. Nonlinear fluxes pass.
Lock exact on V_* for every kappa, so the limit lies in S.
Cone K = {(t,r) in [t0,0) x (0,infty) : r <= Z_s (-t)^lambda }.
Kato: 2x2 Friedrichs system in U = (2c/(gamma-1), u), A0 = I,
source F = (-(d-1) c u / r, 0).
Difference delta U = U - Ubar. Energy identity on K:
iint_K [ d_t |delta U|^2 + d_r (A1 delta U · delta U) ] + lower
= boundary integral on dK.
On the profile, dK is a sonic characteristic. No incoming minus family
from the collar. Lock supplies the trace on the inner particle.
Hence delta U = 0 on K. Do not stamp rdot_s <= u-c as an extra inequality;
that comparison is the definition of Z_s for the profile.


Conclusion, assuming §4: compactly supported physical-vacuum solution on
[t_0, 0) with (rho,u) = (rhobar, ubar) on {Z <= Z_s},
rho = 0 for r >= R(t), and R(t) > r_s(t).

Not Clay.


## Appendix. a0 for Theorem 8.1

a0 is the integer with 1 < 1 + 1/(gamma-1) - a0 <= 2.

- gamma = 5/3 (monoatomic): a0=1.
  ||d^{5/4} dt^5 dy w||^2 + ||d^{3/4} dt^4 dy w||^2. Not d^{1/4}.
- gamma = 7/5 (diatomic): a0=2.
  ||d^{7/4} dt^6 dy w||^2 + ||d^{5/4} dt^5 dy w||^2 + ||d^{3/4} dt^4 dy w||^2.
- gamma = 2 (model): a0=0. Model energy only.
