# 普通物理2复习提纲

## 光的反射和折射

### 电磁波基本性质

电磁波是一种横波

$$v=\frac c n$$，其中v为介质光速，c为真空光速，n为折射率

光强$I$定义为平均能流密度，$I\varpropto E_0^2$$,$$E_0$​为电场的振幅

### 光的偏振态

线偏振（只在一个方向有分布）

自然光（无偏振）

部分偏振光（在部分方向有更多分布）

圆偏振（偏振方向随时间变化，强度不变，呈圆形）

椭圆偏振（偏振方向随时间变化，强度改变，呈椭圆型）

### 光波的描述和复数表示

平面波
$$
U(\vec{r},t)=A_0\cdot cos(\omega t-\vec k \cdot \vec r +\varphi_0)\\
or\\
\tilde U(\vec r,t)=A_0e^{i(\omega t-\vec k \cdot \vec r +\varphi_0)}
$$


球面波
$$
U(\vec{r},t)=\frac {A_0}{r}\cdot cos(\omega t-\vec k \cdot \vec r +\varphi_0)\\
or\\
\tilde U(\vec r,t)=\frac {A_0}{r}e^{i(\omega t-\vec k \cdot \vec r +\varphi_0)}
$$
以上两个公式均是正号汇聚，负号发散，$$\vec k$$表示波传播的方向



光强计算
$$
I=A_0^2=\tilde U \cdot \tilde U^*
$$

### 反射和折射

**菲涅尔公式**考试会提供

**反射率与透射率**


$$
\tilde{r_p}=\frac{\tilde{E_{1p}'}}{E_{1p}} ,
\tilde{r_s}=\frac{\tilde{E_{1s}'}}{E_{1s}} \\
\tilde{t_p}=\frac{\tilde{E_{2p}}}{E_{1p}} ,
\tilde{t_s}=\frac{\tilde{E_{2s}}}{E_{1s}} \\
R_p=\frac{I'_{1p}}{I_{1p}}=|\tilde{r_p}|^2 ,
R_s=\frac{I'_{1s}}{I_{1s}}=|\tilde{r_s}|^2 \\
T_p=\frac{I_{2p}}{I_{1p}}=\frac{n_2}{n_1}|\tilde{t_p}|^2 ,
T_s=\frac{I_{2s}}{I_{1s}}=\frac{n_2}{n_1}|\tilde{t_s}|^2 \\
\mathcal{R}_p=\frac{W_{1p}'}{W_{1p}}=R_p ,
\mathcal{R}_s=\frac{W_{1s}'}{W_{1s}}=R_s \\
\mathcal{T}_p=\frac{W_{2p}}{W_{1p}}=\frac {cosi_2}{cosi_1}T_p ,
\mathcal{T}_s=\frac{W_{2s}}{W_{1s}}=\frac {cosi_2}{cosi_1}T_s
$$


**斯托克斯倒逆关系（运用了光路可逆原理）**
$$
\tilde{r}^2+\tilde t \tilde t'=1 \\
\tilde r '=-\tilde r
$$


**由光疏到光密用由光密到光疏的反射与折射**

从光疏射向光密时，s方向反射率单调上升，p方向反射率先下降再上升，在某个角度降为0（布儒斯特角）。s方向的相位差始终为$\pi$，p方向的相位差在$t_B$前为0，在$t_B$后为$\pi$。s与p方向的透射率均单调下降，相位差为0。

从光密射向光疏时，在发生全反射前，s方向反射率单调上升，p方向反射率先下降后上升，在**布儒斯特角**降为0。再往后将发生全反射（注意全反射的角度与布儒斯特角并非同一个角）相位变化见书

**全反射与隐失波**
$$
\tilde U_2=E_2\cdot e^{-k'_{2z}\cdot z}\cdot e^{ik_{2x}\cdot x}
$$
定义穿透深度为衰变为原来1/e时的距离(k是波数，$k=\frac{2\pi}{n\lambda}$),$k_{2z}'=k_2\cdot Im\{cosi_2\}=k_2\cdot\sqrt{(\frac{n_1}{n_2}sini_1)^2-1}$
$$
d=\frac{1}{k_{2z}'}=\frac{1}{k_2\cdot \sqrt{(\frac{n_1}{n_2}sini_1)^2-1}}=\frac{\lambda_0}{2\pi\sqrt{(n_1sini_1)^2-n_2^2}}
$$


**半波跃变**

即为之前提到的在反射过程中发生的相位变化，由于刚好相差$\pi$，故称为半波跃变

## 光的干涉

**波的叠加原理**：直接加

**点光源的干涉**：
$$
I\varpropto A_1^2+A_2^2+2A_1A_2\cdot cos\delta=I_1+I_2+2\sqrt{I_1I_2}\cdot cos \delta
$$
可见与相位差有关

**形成干涉的条件**

有稳定的相位关系，频率一致，振动方向相同或相反

**分波前干涉**：

——杨氏双缝实验：

亮纹：
$$
\delta=2k\pi\rightarrow x=\frac{D}{d}k\lambda
$$
暗纹：
$$
x=\frac{D}{d}(k+\frac{1}{2})\lambda
$$
条纹移动：
$$
x=\frac{D}{d}k\lambda-\frac{D}{R}\xi
$$
其他分波前装置：

略

相干性：

光源宽度的影响
$$
\gamma=\frac{I_{max}-I_{min}}{I_{max}+I_{min}}
$$
$\frac{D}{R}b=\frac D d \lambda$,即$b=\frac R d \lambda$时，衬比度降为0

时间相干性：

实际光波并非无限长，设$\tau_0$为发光时间，则相干的最大光程差为$L=c\cdot\tau_0$

**分振幅干涉**：

等厚干涉：尖劈、牛顿环：看到同一条亮纹或暗纹是等厚的/注意半波跃变；增透膜及增反膜为控制膜的厚度，利用半波跃变来消除或增强反射光

等倾干涉：厚度增大，从中间冒出条纹
$$
\Delta L=2nd\cdot cosr+\frac \lambda 2=k\lambda
$$
**各种干涉仪**：盲猜不考

## 光的衍射

**菲涅尔原理与基尔霍夫积分公式**：会提供，了解原理

**基尔霍夫边界条件**：并不严格成立（主要是无法做到$\Sigma_2$为半径无穷大的半球面；傍轴假设）

**巴比涅原理**：互补屏造成的衍射场中复振幅之和等于自由波场的复振幅，可利用巴比涅原理由一种衍射屏的图样求其互补屏的衍射图样

由于自由光场在像点外$\tilde U_0=0\rightarrow\tilde U_a(P)=-\tilde U_b(P)\rightarrow I_a(P)=I_b(P)$​,即除几何像点外，互补屏衍射图样一样

**菲涅尔衍射**：

半波带法和矢量图解法；波带片及其变形

**半波带法**
$$
\tilde U(P)=-\frac i {2\lambda}\oiint_{\Sigma_0}(cos\theta_0+cos\theta)\tilde U_0(Q)\frac{e^{ikr}} r d\Sigma
$$
自由传播$|\tilde U(P)|=\frac 1 2A_1(P),I=\frac 1 4 I_1$

圆孔看是奇数个还是偶数个半波带，圆屏中心一定为亮点

当有非整数个半波带时，应该使用**矢量图解法**

例：当圆孔包含1/2个半波带时，轴上的衍射振幅为自由光场的$\sqrt 2$​倍，光强为自由光场时的两倍

**波带片**：涂黑一些半波带，以增强几何像点处的光强
$$
\frac 1 R +\frac 1 b=\frac 1 f\\
f=\frac {\rho_k^2}{k\lambda}
$$
**夫琅禾费衍射**：（复数积分法或矢量图解法）

单缝衍射：记$\alpha=\frac{ka\cdot sin\theta}{2}=\frac{\pi a \cdot sin\theta}{\lambda}$,则$I_\theta=I_0\cdot \frac{sin^2\alpha}{\alpha^2}$

极大值不好算，但是极小值好算，当$\alpha=k\pi$,即$sin\theta=\frac{k\lambda}{a}$时

矩孔衍射：
$$
\alpha =\frac{ka\cdot sin \theta_1}{2},\beta=\frac{kb\cdot sin \theta_2}{2}\\
I(P)=I_0\cdot(\frac{sin\alpha}\alpha)^2\cdot(\frac{sin\beta}\beta)^2
$$
圆孔衍射：艾里斑（零级衍射斑）、分辨本领（$\Delta\theta=1.22\lambda/D$）

