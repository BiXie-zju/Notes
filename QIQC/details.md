# detailed process

The Hamiltonian

$$
\hat{H}=\underbrace{4E_C\hat{n}^2+\frac{1}{2}E_J\hat{\varphi}^2}_{\text{QHO}}-\underbrace{\frac{1}{24}E_J\hat{\varphi}^4}_{\text{nonlinear item}}
$$

and the annihilation operator

$$
\begin{align*}\hat{\varphi}&=\left(\frac{2E_C}{E_J}\right)^{1/4}(\hat{b}+\hat{b}^\dagger)\\\hat{n}&=\frac{\mathrm{i}}{2}\left(\frac{E_J}{2E_C}\right)^{1/4}(\hat{b}^\dagger-\hat{b})\end{align*}
$$

The QHO item 

$$
\begin{align*}4E_C\times\left(-\frac{1}{4}\sqrt{\frac{E_J}{2E_C}}\right)&\times\left(\hat{b}+\hat{b}^\dagger\right)^2+\frac{1}{2}E_J\sqrt{\frac{2E_C}{E_J}}\times\left(\hat{b}^\dagger-\hat{b}\right)^2\\&=\sqrt{8E_JE_C}\left(\hat{b}^\dagger\hat{b}+\frac{1}{2}\right)\end{align*}
$$

The nonlinear item

$$
\begin{align*}&-\frac{1}{12}E_C\left(\hat{b}+\hat{b}^\dagger\right)^4\\&=-\frac{1}{12}E_C\left({\hat{b}}^4+4{\hat{b}}^3\hat{b}^\dagger+\underline{6{\hat{b}}^2{\hat{b}^{\dagger}}^2 }+4\hat{b}{\hat{b}^\dagger}^3+{\hat{b}^\dagger}^4+6\left({\hat{b}}^2+{\hat{b}^\dagger}^2\right)+\underline{12\hat{b}^\dagger\hat{b}}+3\right)\end{align*}
$$

**The constant and the item with unequal annihilation and create operators can be neglected.** So that, the Hamiltonian becomes

$$
\begin{align*}\hat{H}&=\hbar\omega\hat{b}^\dagger\hat{b}-\frac{E_C}{2}\hat{b}^\dagger\hat{b}^\dagger\hat{b}\hat{b}\\&=\hbar\omega_q\left(\hat{b}^\dagger\hat{b}\right)\hat{b}^\dagger\hat{b}\end{align*}
$$

***Proof:***

transform to a rotating reference frame, the transformation operator

$$
U=\mathrm{e}^{-\mathrm{i}\frac{H}{\hbar}t}=\mathrm{e}^{-\mathrm{i}\omega\left(\hat{b}^\dagger\hat{b}+\frac{1}{2}\right)t}
$$

The transformation of annihilation is

$$
\begin{align*}\hat{b}\rightarrow U\hat{b}U^\dagger=\mathrm{e}^{-\mathrm{i}\omega\left(\hat{b}^\dagger\hat{b}\right)t}\,\hat{b}\,\mathrm{e}^{\mathrm{i}\omega\left(\hat{b}^\dagger\hat{b}\right)t}\end{align*}
$$

Utilize the BH formula

$$
\mathrm{e}^{A}B\mathrm{e}^{-A}=\sum_{n=0}^{\infty}\frac{1}{n!}\underbrace{[A,[A,\cdots[A,B]]]}_{\text{n times commutors}}
$$

Thus

$$
\begin{align*}\hat{b}\rightarrow&\sum_{n=0}^{\infty}\frac{\left(-\mathrm{i}\omega t\right)^n}{n!}[\hat{b}^\dagger\hat{b},[\hat{b}^\dagger\hat{b},\cdots[\hat{b}^\dagger\hat{b},\hat{b}]]]\\&=\hat{b}\sum_{n=0}^{\infty}\frac{\left(\mathrm{i}\omega t\right)^n}{n!}\\&=\hat{b}\,\mathrm{e}^{\mathrm{i}\omega t}\end{align*}
$$

Similarly, we can deduce $\displaystyle \hat{b}^\dagger\rightarrow\hat{b}^\dagger\mathrm{e}^{-\mathrm{i}\omega t}$.

Therefore, for the item with unequal $\hat{b}$ and $\hat{b}^\dagger$, there factor $\displaystyle \mathrm{e}^{\pm\mathrm{i}\omega t}$ left which is oscillating item and can be eliminate by averaging on time.