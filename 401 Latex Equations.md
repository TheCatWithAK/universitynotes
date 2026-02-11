Solenoid: $\vec{B} = \mu_0nI$

Gauss's Law: $\displaystyle \oint\vec{E}\cdot\text{d}\vec{A} = \dfrac{Q_{in}}{\epsilon_0}$, $\nabla\cdot\vec{E} = \dfrac{\rho}{\epsilon_0}$

Faraday's Law: $\displaystyle \oint\vec{E}\cdot\text{d}\vec{s} = -\dfrac{\text{d}\Phi_m}{\text{d}t}$, $\nabla \times \vec{E} = -\dfrac{\partial\vec{B}}{\partial t}$

Ampere-Maxwell: $\displaystyle \oint\vec{B}\cdot\text{d}\vec{s} = \mu_0I_{ext} + \epsilon_0\mu_0\dfrac{\text{d}\Phi_e}{\text{d}t}$

Charge Continuity: $\displaystyle \frac{\partial\rho}{\partial t} = -\nabla\cdot\vec{J}$

Energy Density: $\displaystyle u = \frac{\epsilon}{2}E^2 + \frac{1}{2\mu}B^2$

Poynting Vector: $\displaystyle \vec{S} = \frac{1}{\mu}\vec{E}\times\vec{B}$

Work-Energy: $\displaystyle \frac{\text{d}W}{\text{d}t} = -\frac{\partial}{\partial t}\int_v{u(r,t)\text{d}\tau} - \oint\vec{S}\cdot\text{d}\vec{a}$

Power: $\displaystyle P = \oint\vec{S}\cdot\text{d}\vec{a}$

Dissipated Power Density: $\displaystyle \vec{J}\cdot\vec{E}$

Dissipated Power: $\displaystyle \frac{\text{d}W}{\text{d}t} = \int\vec{E}\cdot\vec{J}\text{d}\tau$

Continuity Equation for EM Energy: $\displaystyle \frac{\partial u}{\partial t} = -\nabla\cdot\vec{S} - \vec{J}\cdot\vec{E}$

EM Energy Conservation: $\displaystyle \frac{\partial W_{\text{EM}}}{\partial t} = -\oint\vec{S}\cdot\text{d}\vec{a} - \int\vec{J}\cdot\vec{E}\text{d}\tau$

Momentum Density of EM Field: $\displaystyle \vec{g} = \epsilon_0\mu_0\vec{S} = \frac{\text{d}\vec{P}_{\text{EM}}}{\text{d}\tau}$

Momentum of EM Field: $\displaystyle \vec{P}_{\text{EM}} = \int_v \vec{g}\text{d}\tau$

Maxwell's Stress Tensor: $\displaystyle T_{ij} = \epsilon_0 \left(E_iE_j - \frac{1}{2}\delta_{ij}E^2 \right) + \frac{1}{\mu_0}\left(B_iB_j - \frac{1}{2}\delta_{ij}B^2 \right)$

Momentum: $\displaystyle\frac{\text{d}\vec{p}_{\text{mech}}}{\text{d}t} + \frac{\text{d}}{\text{d}t}\left( \int_v\vec{g}\text{d}\tau\right) = \oint_s\vec{T}\cdot\vec{a}$

Angular Momentum: $\vec{l}_{\text{EM}} = \vec{r}\times\vec{g}_{\text{EM}} = \epsilon_0\left[\vec{r}\times\left(\vec{E}\times\vec{B}\right) \right]$

EMF: $\displaystyle \varepsilon = \oint\vec{E}\cdot\text{d}\vec{l} = -\frac{\text{d}\Phi}{\text{d}t} = -\int\frac{\text{d}\vec{B}}{\text{d}t}\cdot \text{d}\vec{a}$

$\nabla\times\vec{E} = -\dfrac{\partial\vec{B}}{\partial t}$

Maxwell

$\nabla\cdot\vec{E} = 0$

$\nabla\times\vec{E} = -\dfrac{\partial\vec{B}}{\partial t}$

$\nabla\cdot\vec{B} = 0$

$\nabla\times\vec{B} = \epsilon_0\mu_0\dfrac{\partial\vec{E}}{\partial t}$

$\nabla^2\vec{E} = \epsilon_0\mu_0\dfrac{\partial^2\vec{E}}{\partial t^2}$

$\nabla^2\vec{B} = \epsilon_0\mu_0\dfrac{\partial^2\vec{B}}{\partial t^2}$

Monochromatic Plane Wave

$c = \dfrac{1}{\sqrt{\epsilon_0\mu_0}}$
$\omega = 2\pi v = kv$

Boundary Conditions:

$\epsilon_1E^{\perp}_1 = \epsilon_2E^{\perp}_2$

$B^{\perp}_1 = B^{\perp}_2$

$\vec{E}^{\parallel}_1 = \vec{E}^{\parallel}_2$

$\displaystyle \frac{1}{\mu_1}\vec{B}^{\parallel}_1 = \frac{1}{\mu_2}\vec{B}^{\parallel}_2$


$\displaystyle \tilde{\vec{E}}(\vec{r}, t) = \tilde{E_0}e^{i(\vec{k}\cdot\vec{r} - \omega t)}\hat{n}$

$\displaystyle \tilde{\vec{B}}(\vec{r}, t) = \frac{1}{c}\tilde{E}_0e^{i(\vec{k}\cdot\vec{r} - \omega t)}(\hat{k}\times\hat{n}) = \frac{1}{c}\hat{k}\times\tilde{\vec{E}}$

$\hat{n}\times\hat{k} = 0$

Assuming $\hat k = \hat z$
$\hat{n} = \cos(\theta)\hat{x} + \sin(\theta)\hat{y}$
$\tilde{\vec{f}}(z,t) = \left(\tilde{A}\cos(\theta)\right)e^{i(kz-\omega t)}\hat{x} + \left(\tilde{A}\sin(\theta)\right)e^{i(kz-\omega t)}\hat{y}$ 

Real fields:

$\vec{E}(\vec{r},t) = E_0\cos\left(\vec{k}\cdot\vec{r} - \omega t + \delta\right)\hat{n}$

$\displaystyle \vec{B}(\vec{r},t) = \frac{1}{c}E_0 \cos\left(\vec{k}\cdot\vec{r} - \omega t + \delta \right)(\hat{k}\times\hat{n})$

Momentum Density for monochromatic plane waves:

$\displaystyle \vec{g} = \frac{1}{c}\epsilon_0E^2_0 \cos^2(kz - \omega t + \delta)\hat{z} = \frac{1}{c}u\hat{z}$

Average over complete cycle:

$\langle u \rangle = \dfrac{1}{2}\epsilon_0E^2_0$

$\langle \vec{S} \rangle = \dfrac{1}{2}c\epsilon_0E_0^2\hat{z}$

$\langle\vec{g}\rangle = \dfrac{1}{2c}\epsilon_0E_0^2\hat{z}$

Intensity:

$I \equiv \langle S \rangle = \dfrac{1}{2}c\epsilon_0E^2_0$

Radiation Pressure (average force per unit area):

$P = \dfrac{1}{A}\dfrac{\Delta p}{\Delta t} = \dfrac{1}{2}\epsilon_0E^2_0 = \dfrac{I}{c}$

Inside matter with on free charge or free current
Assuming Linear Medium: $\displaystyle \vec{D} = \epsilon\vec{E}$, $\vec{H} = \dfrac{1}{\mu}\vec{B}$
Maxwell simply replace $\epsilon_0, \mu_0$ with $\epsilon, \mu$

$v = \dfrac{1}{\sqrt{\epsilon\mu}} = \dfrac{c}{n}$

$\displaystyle n\equiv\sqrt{\frac{\epsilon\mu}{\epsilon_0\mu_0}}\approx \sqrt{\epsilon_r}$

Waves at Normal Angles

$\tilde{\vec{E}}_I(z,t) = \tilde{E}_{0_I}e^{i(k_1z - \omega t)}\hat{x}$, $\tilde{\vec{B}}_I(z,t) = \dfrac{1}{v_1}\tilde{E}_{0_I}e^{i(k_1z-\omega t)}\hat{y}$

$\tilde{\vec{E}}_R(z,t) = \tilde{E}_{0_R}e^{i(-k_1z - \omega t)}\hat{x}$, $\tilde{\vec{B}}_R(z,t) = -\dfrac{1}{v_1}\tilde{E}_{0_R}e^{i(k_1z-\omega t)}\hat{y}$

$\tilde{\vec{E}}_T(z,t) = \tilde{E}_{0_T}e^{i(k_2z - \omega t)}\hat{x}$, $\tilde{\vec{B}}_T(z,t) = \dfrac{1}{v_2}\tilde{E}_{0_T}e^{i(k_2z-\omega t)}\hat{y}$

Boundary Conditions:

$\epsilon_1E^{\perp}_1 = \epsilon_2E^{\perp}_2 = 0$

$B^{\perp}_1 = B^{\perp}_2 = 0$

$\tilde{E}_{0_I} + \tilde{E}_{0_R} = \tilde{E}_{0_T}$

$\displaystyle \frac{1}{\mu_1}\frac{1}{v_1}\left(\tilde{E}_{0_I} - \tilde{E}_{0_R} \right) = \frac{1}{\mu_2}\frac{1}{v_2}\left(\tilde{E}_{0_T})\right)$
or
$\tilde{E}_{0_I} - \tilde{E}_{0_R} = \beta\tilde{E}_{0_T}$
where
$\beta = \dfrac{\mu_1v_1}{\mu_2v2} = \dfrac{\mu_1n_2}{\mu_2n_1}$

Intensity: $I = \dfrac{1}{2}\epsilon v E^2_0$

$R = \dfrac{I_R}{I_I} = \left(\dfrac{n_1-n_2}{n_1+n_2}\right)^2$
$T = \dfrac{I_T}{I_I} = \dfrac{4n_1n_2}{(n_1+n_2)^2}$
$R + T = 1$

Waves at Oblique Angles

$\displaystyle \tilde{\vec{E}}_I(\vec{r},t) = \tilde{\vec{E}}_{0I} e^{i(\vec{k_I}\cdot\vec{r} - \omega t)}$, $\displaystyle \tilde{\vec{B}}_I(\vec{r},t) = \frac{1}{v_1}\left(\hat{k}_I\times\tilde{\vec{E}}_I\right)$

$\displaystyle \tilde{\vec{E}}_R(\vec{r},t) = \tilde{\vec{E}}_{0R} e^{i(\vec{k_R}\cdot\vec{r} - \omega t)}$, $\displaystyle \tilde{\vec{B}}_R(\vec{r},t) = \frac{1}{v_1}\left(\hat{k}_R\times\tilde{\vec{E}}_R\right)$

$\displaystyle \tilde{\vec{E}}_T(\vec{r},t) = \tilde{\vec{E}}_{0T} e^{i(\vec{k_T}\cdot\vec{r} - \omega t)}$, $\displaystyle \tilde{\vec{B}}_T(\vec{r},t) = \frac{1}{v_2}\left(\hat{k}_T\times\tilde{\vec{E}}_T\right)$

1) $k_I\sin(\theta_I) = k_R\sin(\theta_R) = k_T\sin(\theta_T)$
2) $\theta_I = \theta_R$
3) $\dfrac{\sin(\theta_T)}{\sin(\theta_I)} = \dfrac{n_1}{n_2}$



$\epsilon_1\left(\tilde{\vec{E}}_{0_I} + \tilde{\vec{E}}_{0_R} \right)_z = \epsilon_2\left(\tilde{\vec{E}}_{0_T}\right)_z$

$\left(\tilde{\vec{B}}_{0_I} +\tilde{\vec{B}}_{0_R} \right)_z = \left(\tilde{\vec{B}}_{0_T}\right)_z$

$\left(\tilde{\vec{E}}_{0_I} + \tilde{\vec{E}}_{0_R} \right)_{x,y} = \left(\tilde{\vec{E}}_{0_T}\right)_{x,y}$

$\dfrac{1}{\mu_1}\left(\tilde{\vec{B}}_{0_I} +\tilde{\vec{B}}_{0_R} \right)_{x,y} = \dfrac{1}{\mu_2}\left(\tilde{\vec{B}}_{0_T}\right)_{x,y}$

$\tilde{\vec{B}}_0 = \dfrac{1}{v}\left(\hat{k}\times\tilde{\vec{E}}_0 \right)$

For a wave polarized parallel to the plane of incidence (the $xy$ plane) (**TM Polarization**):

$\epsilon_1\left(-\tilde{E}_{0_I}\sin(\theta_I) + \tilde{E}_{0_R}\sin(\theta_R) \right) = \epsilon_2\left(-\tilde{E}_{0_T}\sin(\theta_T) \right)$

No $B$-field perpendicular, so $0=0$

$\tilde{E}_{0_I}\cos(\theta_I) + \tilde{E}_{0_R}\cos(\theta_R) = \tilde{E}_{0_T}\cos(\theta_T)$

$\dfrac{1}{\mu_1v_1}\left(\tilde{\vec{E}}_{0_I} -\tilde{\vec{E}}_{0_R} \right) = \dfrac{1}{\mu_2v_2}\left(\tilde{\vec{E}}_{0_T}\right)$

Again, 
$\tilde{E}_{0_I} - \tilde{E}_{0_R} = \beta\tilde{E}_{0_T}$
where
$\beta = \dfrac{\mu_1v_1}{\mu_2v2} = \dfrac{\mu_1n_2}{\mu_2n_1} \approx \dfrac{n_2}{n_1}$

$\tilde{\vec{E}}_{0_I} +\tilde{\vec{E}}_{0_R} = \alpha\tilde{\vec{E}}_{0_T}$
where
$\alpha \equiv \dfrac{\cos(\theta_T)}{\cos(\theta_I)}$

TM Polarization:
$\tilde{E}_{0_R} = \dfrac{\alpha - \beta}{\alpha + \beta}\tilde{E_{0_I}}$
$\tilde{E}_{0_T} = \dfrac{2}{\alpha + \beta}\tilde{E}_{0_I}$
$R = \left(\dfrac{\alpha-\beta}{\alpha + \beta}\right)^2$
$T = \dfrac{4\alpha\beta}{(\alpha + \beta)^2}$

TE Polarization:
$\tilde{E}_{0_R} = \dfrac{1 - \alpha\beta}{1+ \alpha\beta}\tilde{E_{0_I}}$
$\tilde{E}_{0_T} = \dfrac{2}{1+ \alpha\beta}\tilde{E}_{0_I}$
$R = \left(\dfrac{1-\alpha\beta}{1+\alpha\beta} \right)^2$
$T = \dfrac{4\alpha\beta}{(1+\alpha\beta)^2}$

Brewster Angle: No T:
Only for TM: $\alpha = \beta$

Total Internal Reflection
$\sin(\theta_T) = \dfrac{n_1}{n_2}\sin(\theta_C) = 1 \implies \sin(\theta_C) = \dfrac{n_2}{n_1}$

EM Waves in Conductor
$\vec{J}_f = \sigma\vec{E}$ 

Maxwell's in a conductor

$\nabla \cdot \vec{E} = 0$

$\nabla\cdot\vec{B} = 0$

$\nabla \times\vec{E} = -\dfrac{\partial\vec{B}}{\partial t}$

$\nabla\times\vec{B} = \epsilon\mu\dfrac{\partial\vec{E}}{\partial t} + \mu\sigma\vec{E}$

Modified wave equations:
$\nabla^2\vec{E} = \mu\epsilon\dfrac{\partial^2\vec{E}}{\partial t^2} + \mu\sigma\dfrac{\partial\vec{E}}{\partial t}$, $\nabla^2\vec{B} = \mu\epsilon\dfrac{\partial^2\vec{B}}{\partial t^2} + \mu\sigma\dfrac{\partial\vec{B}}{\partial t}$

Gives us plane waves with complex $k$

$\tilde{\vec{E}}(z,t) = \tilde{\vec{E_0}}e^{i(\tilde{k}z-\omega t)}$, $\tilde{\vec{B}}(z,t) = \tilde{\vec{B_0}}e^{i(\tilde{k}z-\omega t)}$
where
$\tilde{k}^2 = \epsilon\mu\omega^2 + i\mu\sigma\omega$

$\tilde{k} = k + i\varkappa$
where
$\displaystyle k \equiv \omega\sqrt{\dfrac{\epsilon\mu}{2}}\left[\sqrt{1+\left(\dfrac{\sigma}{\epsilon\omega}\right)^2} \pm 1 \right]^{1/2}$

Good conductor:
$\dfrac{\sigma}{\epsilon\omega} \gg 1$
$k \approx \varkappa \approx \sqrt{\dfrac{\omega\mu\sigma}{2}}$
Bad conductor
$\dfrac{\sigma}{\epsilon\omega} \ll 1$
$k \approx \omega\sqrt{\epsilon\mu} \gg \varkappa \approx \dfrac{1}{2}\dfrac{\sigma}{\epsilon\omega}k$

Field Structure:
$\tilde{\vec{E}}(z,t) = \tilde{E_0}e^{-\varkappa z}e^{i(kz-\omega t)}\hat{x}$, $\tilde{\vec{B}}(z,t) = \tilde{B_0}e^{-\varkappa z}e^{i(kz-\omega t)}\hat{y}$
where
$\tilde{B}_0 = \dfrac{\tilde{k}\tilde{E_0}}{\omega}$

$\displaystyle \tilde{E}_0 = |\tilde{E}_0| e^{i\delta_E}$
$\displaystyle \tilde{B}_0 = |\tilde{B}_0| e^{i\delta_B}$
$\tilde{k} = |\tilde{k}|e^{i\varphi}$

$\delta_B - \delta_E = \varphi = \arctan\left(\dfrac{\varkappa}{k}\right)$

Real fields:
$\vec{E}(z,t) = E_0e^{-\varkappa z}\cos(kz-\omega t + \delta_E)\hat{x}$
$\vec{B}(z,t) = B_0e^{-\varkappa z}\cos(kz-\omega t + \delta_E + \varphi)\hat{y}$

$\dfrac{B_0}{E_0} = \dfrac{K}{\omega} = \sqrt{\epsilon\sqrt}