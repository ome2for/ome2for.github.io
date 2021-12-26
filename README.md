## Spatial number, multi-dimensional complex

### 1. Definition and expression
>We know that a complex number **Z=a+bi** indicates a point **(a, b)** in the complex plane, hence the modulus of the vector from (0,0) to (a,b) i.e  **$\vert \overrightarrow{Z} \vert $** is **$r=\sqrt{a^2+b^2}$** and it's argument is **$\theta=\arctan\left(\frac{b}{a}\right)$**, which is the angle turning conterclockwisely away from the real axis **X**. Regardless of it's periodicity, **$\theta\in{\left(-\pi, \pi\right]}$** . Expolently expressed it is as **$Z=re^{{\theta}i}$**。

>In the same way, we define **S=a+bi+cj** as a point **(a, b, c)** in three dimensional space, where the real part **a** is on axis **X**,  the first imaginary part **b** is on axis **Y**  and the second imaginary part **c** is on axis **Z**. The modulus of vector **$\overrightarrow{S}$** is **$r=\sqrt{a^2+b^2+c^2}$**. If let  **$r_1=\sqrt{a^2+b^2}$** , called first modulus, indicating the modulus of projective vector in $XY$ plane, then **$\theta_1=\arctan\left(\frac{b}{a}\right)$**, indicating the angle turning conterclockwisely away from the real axis **X**, is ranged in **$\left(-\pi, \pi\right]$**, while  **$\theta_2=\arctan\left(\frac{c}{r_1}\right)$** indicates the angle leaving the **X-Y** plane for **Z**  in range **$\left(-\frac{\pi}{2}, \frac{\pi}{2}\right]$** . We call **$\theta_1$** the first argument and **$\theta_2$** the second argument. So in polary coordinate the expression is **$S=re^{\theta_1{i}+\theta_2{j}}$**

>Now we generalize the idea above as the following statement: **$S=a_0+a_1\bar{\imath}+a_2\acute{\imath}+a_3\check{\imath}+a_4\grave{\imath}+\cdots\cdots+a_n\hat{\imath}$** (the **$\wedge$** on top of **$\imath$** should be **n**)
represents a point **$(a_0, a_1, a_2, \cdots\cdots, a_n )$** in **n+1** dimensional space. Such defined number is called **n+1** dimensional ***spatial number***.
If let  **$r_0=a_0$**,
**$r_1=\sqrt{a_0^2+a_1^2}$**,(first modulus)
**$\cdots\cdots$**,
**$r_{n-1}=\sqrt{a_0^2+a_1^2+\cdots\cdots+a_{n-1}^2}$**,
and  **$r=\sqrt{a_0^2+a_1^2+\cdots\cdots+a_n^2}$**,
then **$\theta_1=\arctan\left(\frac{a_1}{r_0}\right)$**,(first argument)
 **$\theta_2=\arctan\left(\frac{a_2}{r_1}\right)$**,**$\cdots\cdots$**,
 and **$\theta_n=\arctan\left(\frac{a_n}{r_{n-1}}\right)$**,
It also can be expressed in expolent form as **$S=re^{\theta_1\bar{\imath}+\theta_2\acute{\imath}+\theta_3\check{\imath}+\cdots\cdots+\theta_n\hat{\imath}}$**.

>To simplify the expression, let **$a$** represent the sequence **$\left[a_1, a_2, \cdots\cdots, a_n\right]$** (called **spatial-position-row**) and **$I$** represent the sequence **$\left[\bar{\imath}, \acute{\imath}, \check{\imath}, \grave{\imath}, \cdots\cdots, \hat{\imath}\right]$**  (called **spatial-axis-collum**), so that **$S=a_0+aI$**, where **$aI$** implies the dot product of **$a$** and **$I$**. We call it the ***spatial-position expression***.  If insert the real part **a_0** into **$a$** and **$1$**  into **$I$**, i.e. **$a=\left[a_0, a_1, \cdots\cdots, \right]$** and **$\hat{I}=\left[1, \bar{\imath}, \cdots\right]$**, we can get the simpliest form **$S=a\hat{I}$**, which is called ***all-position expression***.
>Parellely in expolent expression, if **$\theta=\left[\theta_1, \theta_2, \cdots\cdots, \theta_n\right]$**,  then **$S=re^{\theta{I}}$**, which is called ***spatial-phrase expression***. Since **$r\gt{0}$**, so if let **$\theta_0=\ln{r}$** and **$\theta=\left[\theta_0, \theta_1, \theta_2, \cdots\cdots, \theta_n\right]$**,  then **$S=e^{\theta{\hat{I}}}$**, that is called ***all-phrase expression***.
###2. Operation rules
 - ##### Addition and subtraction
>>Spatial numbers follow the same rules of addition and subtraction as applied in complex numbers, that is to add or subtract each part respectively.
**$S=a_0+a_1\bar{\imath}+a_2\acute{\imath}+\cdots =a_0+aI$**
**$P=b_0+b_1\bar{\imath}+b_2\acute{\imath}+\cdots =b_0+bI$**
**$S{\pm}P=(a_0{\pm}b_0)+(a_1{\pm}b_1)\bar{\imath}+(a_2{\pm}b_2)\acute{\imath}+\cdots=(a_0{\pm}b_0)+(a{\pm}b)I$**
While in expolent expression, it has to be transformed in the follwing way:
If **$S=re^{\theta_1{\bar{\imath}}+\theta_2{\acute{\imath}}+\cdots+\theta_n{\hat{\imath}}}=re^{\theta{I}}$** and
**$P={\rho}e^{\varphi_1\bar{\imath}+\varphi_2\acute{\imath}+\cdots+\varphi_n\hat{\imath}}={\rho}e^{\varphi{I}}$**

>>then **$a_0=r\cos{\theta_1}\cos{\theta_2}\cdots\cos{\theta_n}$**
**$b_0=\rho\cos{\varphi_1}\cos{\varphi_2}\cdots\cos{\varphi_n}$**

>>**$a_1=r\sin{\theta_1}\cos{\theta_2}\cos{\theta_3}\cdots\cos{\theta_n}$**
**$b_1=\rho\sin{\varphi_1}\cos{\varphi_2}\cdots\cos{\varphi_n}$**

>>**$a_2=r\sin{\theta_2}\cos{\theta_3}\cdots\cos{\theta_n}$**
**$b_2=\rho\sin{\varphi_2}\cos{\varphi_3}\cdots\cos{\varphi_n}$**
**$\cdots\cdots$**
**$a_{n-1}=r\sin{\theta_{n-1}}\cos{\theta_n}$**
**$b_{n-1}=\rho{\sin{\theta_{n-1}}\cos{\theta_n}}$**
**$a_n=r\sin{\theta_n}$**
**$b_n=\rho\sin{\varphi_n}$**
For the sake of simplicity, we initiatively define two functions:
The first is **$Recursive-cosine$**, difined  as:
**$Recos\theta=\cos{\theta_1}\cos{\theta_2}\cdots\cos{\theta_n}$**, where
**$\theta=[\theta_1, \theta_2, \cdots, \theta_n]$**  
and the second is **$Recursive-sine$** function , defined as:
**$Resin\theta=[\sin{\theta_1}\cos{\theta_2}\cdots\cos{\theta_n},\sin{\theta_2}\cos{\theta_3}\cdots\cos{\theta_n},
\sin{\theta_3}\cos{\theta_4}\cdots\cos{\theta_n},
\cdots\cdots,
\sin{\theta_n}
]$**
therefore we can get the follwing expression:
**$S=re^{\theta{I}}=r(Recos\theta+IResin\theta)$**
**$P=\rho{e^{\varphi{I}}}=\rho(Recos\varphi+IResin\varphi)$**
**$S{\pm}P=(rRecos{\theta}{\pm}{\rho}Recos{\varphi})+(rResin{\theta}{\pm}{\rho}Resin{\varphi})I$**

 - #### multiplication and devision
 >>Before inquiring the method of multiplication on spatial numbers, we should review the rule applied in complex numbers:
 **$Z_1=r_1e^{\theta_1i}$**
 **$Z_2=r_2e^{\theta_2i}$**
 **$Z_1Z_2=r_1r_2e^{(\theta_1+\theta_2)i}$**
 We assume that this rule still holds for spatial numbers, so the multiplication of two spatial numbers can be defined as following statement:
 if they are given in expolent expressions, here in **$all-phrase-expression$**:
 **$S=e^{\theta{\hat{I}}}$**
 **$P=e^{\varphi{\hat{I}}}$**
 then  **$SP=e^{(\theta+\varphi)\hat{I}}$**
 Quite simple!
 However, it's truly not obvious to see how to multiply
 two spatial numbers given in coordinate expressions:
 **$S=a_0+a_1\bar{\imath}+a_2\acute{\imath}+\cdots=a\hat{\imath}$**
 **$P=b_0+b_1\bar{\imath}+b_2\acute{\imath}+\cdots=b\hat{\imath}$**
 where **$a=[a_0, a_1, a_2, \cdots, a_n]$**
 **$b=[b_0, b_1, b_2, \cdots, b_n]$**
 In fact, it is a recursive procession as follows:
 **$S_1=a_0+a_1\bar{\imath}$**
 **$S_2=a_0+a_1\bar{\imath}+a_2\acute{\imath}$**
 **$\cdots\cdots$**
 **$P_1=b_0+b_1\bar{\imath}$**
 **$P_2=b_0+b_1\bar{\imath}+b_2\acute{\imath}$**
 **$\cdots\cdots$**
 **$S_1P_1=a_0b_0(1-\frac{a_1b_1}{a_0b_0})+(a_1b_0+b_1a_0)\bar{\imath}$**(multiplication of two ordinary complex numbers )
 **$S_2P_2=S_1P_1(1-\frac{a_2b_2}{|S_1||P_1|})+(a_2|P_1|+b_2|S_1|)\acute{\imath}$**

 >>**$S_3P_3=S_2P_2(1-\frac{a_3b_3}{|S_2||P_2|})+(a_3|P_2|+b_3|S_2|)\check{\imath}$**
**$\cdots\cdots$**
 if **$SP=c_0+c_1\bar{\imath}+c_2\acute{\imath}+\cdots=c\hat{\imath}$**
 then **$c_0=a_0b_0(1-\frac{a_1b_1}{a_0b_0})(1-\frac{a_2b_2}{|S_1||P_1|})(1-\frac{a_3b_3}{|S_2||P_2|})\cdots(1-\frac{a_nb_n}{|S_{n-1}||P_{n-1}|})=|S||P|\frac{a_0b_0-a_1b_1}{|S_1||P_1|}\frac{|S_1||P_1|-a_2b_2}{|S_2||P_2|}\cdots\frac{|S_{n-1}||P_{n-1}|-a_nb_n}{|S||P|}=|S||P|\cos(\theta_1+\varphi_1)\cos(\theta_2+\varphi_2)\cdots\cos(\theta_n+\varphi_n)$**
 **$c_1=(a_1b_0+b_1a_0)(1-\frac{a_2b_2}{|S_1||P_1|})(1-\frac{a_3b_3}{|S_2||P_2|})\cdots(1-\frac{a_nb_n}{|S_{n-1}||P_{n-1}|})=|S||P|\frac{a_1b_0+b_1a_0}{|S_1||P_1|}\frac{|S_1||P_1|-a_2b_2}{|S_2||P_2|}\cdots\frac{|S_{n-1}||P_{n-1}|-a_nb_n}{|S||P|}=|S||P|\sin(\theta_1+\varphi_1)\cos(\theta_2+\varphi_2)\cdots\cos(\theta_n+\varphi_n)$**
**$c_2=(a_2|P_1|+b_2|S_1|)(1-\frac{a_3b_3}{|S_2||P_2|})\cdots(1-\frac{a_nb_n}{|S_{n-1}||P_{n-1}|})=|S||P|\frac{a_2|P_1|+b_2|S_1|}{|S_2||P_2|}\frac{|S_2||P_2|-a_3b_3}{|S_3||P_3|}\cdots\frac{|s_{n-1}||P_{n-1}|-a_nb_n}{|S||P|}=|S||P|\sin(\theta_2+\varphi_2)\cos(\theta_3+\varphi_3)\cdots\cos(\theta_n+\varphi_n)$**
**$\cdots\cdots$**
**$c_n=a_n|P_{n-1}|+b_n|S_{n-1}|=|S||P|\frac{a_n|P_{n-1}|+b_n|S_{n-1}|}{|S||P|}=|S||P|\sin(\theta_n+\varphi_n)$**
therefore **$SP=|S||P|(Recos(\theta+\varphi)+IResin(\theta+\varphi))$**

In the recursive procession mentioned above,the $|S_{n-1}||P_{n-1}|$ shoul be non-zero. Otherwise, when one of the two is zero, if let $|S_{n-1}|\neq 0$ and $|P_{n-1}|=0$, then $$S_nP_n=(-S_{n-1}a_n \frac{|b_n|}{|S_{n-1}|}, b_n|S_{n-1}|)$$
If $|S_{n-1}|=|P_{n-1}|=0$, then $S_nP_n=-a_nb_n$.


- Discussion on imaginary unit
 >>**$\bar{\imath}\acute{\imath}=?$**
 **$\bar{\imath}\rightarrow(0, 1, 0) ,  \acute{\imath}\rightarrow(0, 0, 1)$**
 so **$\bar{\imath}\acute{\imath}=\acute{\imath}$**
 or **$\bar\imath=e^{\frac{\pi}{2}{\bar{\imath}}}$**
 **$\acute\imath=e^{\frac{\pi}{2}{\acute\imath}}$**
 **$\bar\imath\acute\imath=e^{\frac{\pi}{2}\bar\imath+\frac{\pi}{2}\acute\imath}=(\cos\frac{\pi}{2}\cos\frac{\pi}{2}, \sin\frac{\pi}{2}\cos\frac{\pi}{2}, \sin\frac{\pi}{2})=\acute\imath$**
 Similarily, **$\bar\imath\check\imath=\acute\imath\check\imath=\bar\imath\acute\imath\check\imath=\check\imath$**

 >>**$\acute\imath^2=?$**
 Jast like **$i^2=-1$** in complex number, **$\acute{\imath}^2=-1$** still holds. In fact, **$\acute{\imath}^2=-(\cos{\theta}+\bar{\imath}\sin{\theta})$**, where **$\theta\in(-\pi, \pi]$**, i.e it is an inverse  unit circle in the complex plane.
 Similarily, **$\check{\imath}^2=-e^{\theta{\bar{\imath}}+\varphi\acute{\imath}}$**, representing the inverse unit sphere in 3-D space.


 >>**$\frac{1}{\acute{\imath}}=?$**
**$\frac{1}{\acute{\imath}}=e^{(0-\frac{\pi}{2})}=-\acute{\imath}$**.
  **$\frac{1}{\check{\imath}}=-\check{\imath}$**
$**
###3. Extension on complex number
- On C-R function
>>Cauchy-Riemann theorem says that for complex number **$Z=x+yi$**,
if **$f(Z)=u(x, y)+v(x, y)i$** is differential at **$(x_0, y_0)$**,
then exists: **$\left\{\begin{array}{r}u_x=v_y\\u_y=-v_x\end{array}\right.$**
If spatial number **$S=x+y\bar{\imath}+z\acute{\imath}$** and function **$f(Z)=u(x, y, z)+v(x, y, z)\bar{\imath}+w(x, y, z)\check{\imath}$** is differential at **$(x_0,y_0,z_0)$**
then exists: **$\left\{\begin{array}{r}u_x=v_y=w_z\\v_x=-u_y=0\\w_x=-w_y=-v_z-u_z\end{array}\right. $**

If spatial number **$S=x+y\bar{\imath}+z\acute{\imath+t\check\imath}+t\grave{\imath}$** and function **$f(Z)=u(x, y, z, t)+v(x, y, z, t)\bar{\imath}+w(x, y, z, t)\check{\imath}+r(x, y, z, t)\grave{\imath}$** is differential at **$(x_0,y_0,z_0, t_0)$**
then exists: **$\left\{\begin{array}{r}u_x=v_y=w_z=r_t\\v_x=-u_y=0\\w_x=-w_y=-v_z-u_z=0\\r_x=-r_y=-r_z=-u_t-v_t-w_t\end{array}\right. $**

- The angle between two spatial numbers
If two complex numbers **$Z_1=re^{\theta{i}}=r(\cos{\theta}+i\sin{\theta})$** and **$Z_2=\rho e^{\varphi{i}}=\rho(\cos{\varphi}+i\sin{\varphi})$**,
the angle between **$Z_1$** and **$Z_2$**  is **$\theta-\varphi$**
**$\cos(\theta-\varphi)=\cos{\theta}\cos{\varphi}+\sin{\theta}\sin{\varphi}$**

If two spatial numbers are given in **spatial-phase** expressions, as follows: **$S_1=re^{\theta{I}}=r(Recos{\theta}+IResin\theta)=aI$** and **$S_2=\rho e^{\varphi{I}}=\rho(Recos{\varphi}+IResin\varphi)=bI$**, then the angle between **$S_1$** and **$S_2$** is symblized as **$\theta\wedge\varphi$**
**$\cos(\theta\wedge\varphi)=Recos\theta Recos\varphi+Resin\theta Resin\varphi=\frac{ab}{|a||b|}$**
