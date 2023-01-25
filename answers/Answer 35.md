#### Вопрос 35
K - значные функции
$f: \Omega_2^n \rightarrow \Omega_2$ -   булевы функции
$f: \Omega_k^n \rightarrow \Omega_k$ -   k - значные функции
$n = 0: \Omega = \textbraceleft 0, 1, 2, ..., k - 1 \textbraceright$ множество констант
$|F_k(n)| = k^{k^n}$ - мощность множества всех k-значных функций

Часто используемые функции k-значной логики
1. $\begin{equation} \delta_a(x) = \begin{cases} 1, & x=a \\ 0, & x\neq a \end{cases}\end{equation}$ 
2. $\begin{equation} J_a(x) = \begin{cases} k - 1, & x=a \\ 0, & x\neq a \end{cases}\end{equation}$ 
3. Сложение: $(x_1 + x_2)mod \text{ } k$ 
4. Умножение $(x_1 \times x_2)mod \text{ } k$ 
5. Дизъюнкиця $(x_1 \vee x_2) = max \textbraceleft x_1, x_2 \textbraceright$ 
6. Конъюнкция $(x_1 \wedge x_2) = min \textbraceleft x_1, x_2 \textbraceright$
7. Отрицание Поста: $\bar x_1 = (x_1 + 1) mod \text{ } k$ 
8. Отрицание Лукашевича: $\sim x = (k - 1 - x) mod \text{ } k$ 
9. Функция Вэбба: $V_k = \overline{x_1 \vee x_2} = (max \textbraceleft x_1, x_2 \textbraceright + 1) mod \text{ } k$ 