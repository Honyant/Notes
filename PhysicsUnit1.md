
# Fictitious Forces

$$ u' = \frac{dx'}{dt}=\frac{dx}{dt}-\frac{d}{dt} \int v dt = u-v$$
$$ a =\frac{du}{dt}$$
$$ a'=\frac{du'}{dt}=\frac{du}{dt}-\frac{dv}{dt} $$

If v=constant, then $$a'=a$$
$$ma'=ma$$

Newtons Laws hold in inertial ref. frame!

$$F_{net}=ma'$$ $$F_{net}=ma'$$

If S' is accelerating $$v=v(t), a'\neq a$$
$$F_{net} \neq ma'$$

add fictitious forces to fix ur problems

Take inertial frame S and frame S' accelerating relative to S at A.

In S: $$F_{net}=m \frac{d^2 \vec{r}}{dt^2}$$

In S': $$\frac{d \vec{r}'}{dt}=\frac{d \vec{r}'}{dt}-\vec{v}$$ and $$m \frac{d^2 \vec{r}}{dt^2}=m \frac{d^2 \vec{r}}{dt^2}-m \vec{A}$$
$$m \vec{A}$$ is the additional force.

recover 2nd law if we pretend the additional force, "inertial force" $$-m \vec{A}$$
$$F_{net} - m\vec{A}=ma'$$

Centripetal force is a good examples of fictitious force.

If you are on a train and the train accelerates while you juggle balls, the balls appear to be acted on by a force -mA

Find accel of train ST box is stationary on a frictionless surface

$$F=m (g \cos \theta - a \sin \theta )$$
$$a= \frac{mg \cos \theta-F}{\sin \theta} $$

$$\cos \theta F_n=mg$$
$$\sin \theta F_n=a \sin \theta $$

$$\Sigma F_x=ma \cos \theta- mg \sin \theta=0 $$

$$a=g \tan \theta$$

Now, $$a=\frac{3}{2} g \tan \theta$$

$$\Sigma F_x=ma \cos \theta- mg \sin \theta=ma' $$

$$mg  \sin( \theta) \left(\frac{3}{2} -1\right)=ma'$$

$$g  \sin (\theta) 0.5=a'$$
$$d=1/2at^2$$

$$t=\sqrt{\frac{2d}{g  \sin(\theta) 0.5} }$$

$$t=\sqrt{\frac{4d}{g  \sin(\theta)} }$$

$$t=2\sqrt{\frac{d}{g  \sin(\theta)} }$$

# Linear air resistance Freefall

$$ma=-bv+mg$$
$$m \frac{\mathrm dv}{ \mathrm dt} = -bv +mg$$
$$m \frac{\mathrm dv}{ -bv +mg}=dt$$
$$\int_{v_0}^{v(t)} m \frac{\mathrm dv}{ -bv +mg}=\int_0^t dt$$
$$ \ln(|-bv+mg|) \Big|_{v_0}^{v(t)}=t$$
$$\ln\left(\frac{|-bv+mg|}{|-bv_0+mg|}\right)=$$
$$\frac{-bv+mg}{-bv_0+mg}=e^{-\frac{b}{m}t}$$
$$-bv+mg=e^{-\frac{b}{m}t}(-bv_0+mg)$$
$$v=-\frac{e^{-\frac{b}{m}t}(-bv_0+mg)-mg}{b}$$
$$v=\frac{mg-e^{-\frac{b}{m}t}(-bv_0+mg)}{b}$$
$$v=\frac{mg}{b}-e^{-\frac{bt}{m}}\left(-v_0+\frac{mg}{b}\right)$$
