# DE
差分进化算法的参数设计与实现
算法实现来自https://pablormier.github.io/2017/09/05/a-tutorial-on-differential-evolution-with-python/
$$Ackley:\quad f(x)=20+exp(1)+20exp(-0.2\sqrt{\frac 12 \sum_{i=1}^2 x_i^2} - exp(\frac 12 \sum_{i=1}^2cos(2 \pi x_i))\quad -32.768\le x_i \le 32.768$$
$$Schaffer:\quad f(x)=\frac{(\sin^2\sqrt{x_1^2+x_2^2}-0.5)}{(1+0.001(x_1^2+x_2^2))^2}-0.5\quad-100\le x_1,x_2 \le100$$
$$Rastrigin:\quad f(x)=\sum_1^{30}(x_i^2-10cos(2\pi x_i)+10)\quad -5.12\le x_i \le 5.12$$
$$Griewank:\quad f(x)=\frac 1{4000}\sum_{i=1}^{30}x_i^2-\prod_{i=1}^n cos{\left(\frac {x_i}{\sqrt i}\right)}+1\quad -60\le {x_i}\le 60$$
