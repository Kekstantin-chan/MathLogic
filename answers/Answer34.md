#### Вопрос 34

##### Понятие нелинейности булевой функции, значение нелинейности. k-значные функции.

Опр.

Афинной называется булева функция вида: $f(x_0...x_{n-1})=a_0x_0⊕...⊕a_{n-1}x_{n-1}⊕b$

Опр.

Нелинейностью бф называется минимальное расстояние от этой функции до множества афинных функций: $(f)=\min\limits_{c\in A_n}(f,c)$

k-значные функции

$f: Ω_2^n→Ω_2$ - булевы функции

$f: Ω_k^n→Ω_2$ - k-значные функции

$n=0: Ω=$ { $0, 1, ... k-1$ } - множество констант

$|F_k(n)|=k^{k^n}$ - мощность множества всех k-значных функций

Часто используемые функции:

1. $δ_a(x)=\begin{equation} \delta_a(x) = \begin{cases} 1, & x=a \\ 0, & x\neq a \end{cases}\end{equation}$
2. $⊐_a(x)=\begin{equation} \delta_a(x) = \begin{cases} k-1, & x=a \\ 0, & x\neq a \end{cases}\end{equation}$
3. Сложение: $(x_1+x_2)mod(k)$
4. Умножение: $(x_1∙x_2)mod(k)$
5. Дизъюнкция: $x_1∨x_2=max(x_1,x_2)$
6. Конъюнкция: $x_1∧x_2=min(x_1,x_2)$
7. Отрицание Поста: $\overline{x_1}=(x_1+1)mod(k)$
8. Отрицание Лукашевича: $⁓x=(k-1-x)mod(k)$
9. Функция Вэба: $V_k=\overline{x_1∨x_2}=(max(x_1, x_2)+1)mod(k)$