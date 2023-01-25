#### Вопрос 23

##### Построение сокращенной ДНФ из СДНФ.

*Алгоритм построения сокращенной ДНФ из СДНФ*

**Вход**: $f(x_1, \dots, x_n) = \bigvee x_1^{\alpha_1} \cdot \ldots \cdot x_n^{\alpha_n} = \varphi_1^{(n)} \vee \dots \vee \varphi_k^{(n)}$. $\varphi_i^{(n)}$ - элементарная конъюнкция длины $n$.

1. Для каждой $\varphi_1^{(n)} , \dots , \varphi_k^{(n)}$ находим соседние и выполняем операцию склеивания: 

$$
f = \varphi_1^{(n)} \vee \dots \vee \varphi_l^{(n)} \vee f_1 \text{, где } f_1 = \varphi_1^{(n-1)} \vee \dots \vee \varphi_t^{(n-1)}
$$

2. Применяем шаг 1 к $f_1$: $f_1 = \varphi_1^{(n-1)} \vee \dots \vee \varphi_s^{(n-1)} \vee f_2$.

**Выход**: сокращенная ДНФ