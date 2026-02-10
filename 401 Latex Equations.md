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

$\nabla\times\vec{B} = \epsilon\mu\dfrac{\partial\vec{E}}{\partial t}$

$\nabla^2\vec{E} = \epsilon\mu\dfrac{\partial^2\vec{E}}{\partial t^2}$

Monochromatic Plane Wave
$v = \dfrac{1}{\sqrt{\epsilon\mu}} = \dfrac{c}{n}$
$\displaystyle n\equiv\sqrt{\frac{\epsilon\mu}{\epsilon_0\mu_0}}\approx \sqrt{\epsilon_r}$

Boundary Conditions:

$\epsilon_1E^{\perp}_1 = \epsilon_2E^{\perp}_2$

$B^{\perp}_1 = B^{\perp}_2$

$\vec{E}^{\parallel}_1 = \vec{E}^{\parallel}_2$

$\displaystyle \frac{1}{\mu_1}\vec{B}^{\parallel}_1 = \frac{1}{\mu_2}\vec{B}^{\parallel}_2$


$\displaystyle \tilde{\vec{E}}(\vec{r}, t) = \tilde{E_0}e^{i(\vec{k}\cdot\vec{r} - \omega t)}\hat{n}$

$\displaystyle \tilde{\vec{B}}(\vec{r}, t) = \frac{1}{c}\tilde{E}_0e^{i(\vec{k}\cdot\vec{r} - \omega t)}(\hat{k}\times\hat{n}) = \frac{1}{c}\hat{k}\times\tilde{\vec{E}}$

$\hat{n}\times\hat{k} = 0$

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

