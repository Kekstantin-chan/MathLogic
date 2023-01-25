#### Вопрос 22

##### Соседние элементарные конъюнкции. Склеивание и расклеивание э.к. Насыщенные ДНФ. Лемма о склеивании в насыщенных ДНФ.

Опр. Элементарные конъюнкции называются *соседними*, если они отличаются показателем только одного переменного.

$$
\varphi_1 = x_1^{\alpha_1} \cdot \ldots \cdot x_{i-1}^{\alpha_{i-1}} \cdot x_i^{\alpha_i} \cdot x_{i+1}^{\alpha_{i+1}} \cdot x_n^{\alpha_n}
$$

$$
\varphi_1 = x_1^{\alpha_1} \cdot \ldots \cdot x_{i-1}^{\alpha_{i-1}} \cdot x_i^{\overline{\alpha_i}} \cdot x_{i+1}^{\alpha_{i+1}} \cdot x_n^{\alpha_n}
$$

*Операция склеивания*

$$
\varphi_1 \vee \varphi_2 \equiv \varphi \wedge (x_i \vee \overline{x_i}) \equiv \varphi
$$

*Операция рассклеивания*

$$
\varphi \equiv \varphi \wedge (x_i \vee \overline{x_i}) \equiv \varphi_1 \vee \varphi_2
$$

Опр. Пусть $A(x_1, \dots, x_n) = \bigvee_{i=1}^{s}\varphi_{i}^{(r)}$ - все элементарные конъюнкции ранга $r$. Тогда $A(x_1, \dots, x_n)$ называется *насыщенной* ДНФ в том и только том случае, если $\nexists \varphi^{(r)}$, не лежащей среди перечисленного выше множества $A$: $\varphi^{(r)} \notin \{\varphi_1^{(r)}, \dots, \varphi_s^{(r)} \}$ и $\varphi^{(r)} \vee A \equiv A$ (является импликацией).

*Лемма*. Пусть $f(x_1, \dots, x_n) = \bigvee_{i=1}^{k}\varphi_{i}^{(r)}$ - насыщенная ДНФ и пусть $\varphi_1^{(r)}, \dots, \varphi_l^{(r)}$ - изолированные элементарные конъюнкции, $l < k$; $f = \varphi_1^{(r)} \vee \dots \vee \varphi_l^{(r)} \vee f_1$, где $f_1 = \varphi_1^{(r - 1)} \vee \dots \vee \varphi_{\tau}^{(r - 1)}$, тогда:

1. ДНФ $\varphi_1^{(r - 1)} \vee \dots \vee \varphi_{\tau}^{(r - 1)}$ - насыщенная ДНФ;
2. $\varphi_1^{(r - 1)}, \dots, \varphi_{\tau}^{(r - 1)}$ - все импликанты ранга $(r-1)$ функции $f$;
3. Множество всех простых импликантов ранга $(r-1)$ функции $f$ совпадает с множеством всех простых импликантов ранга $(r-1)$ функции $f_1$.