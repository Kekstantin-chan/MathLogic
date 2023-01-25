#### Вопрос 36
$\textsection$ Полные системы k-значных функций
1. $\textbraceleft 0, 1, 2, \dots, k - 1, \delta_0(x), \dots, \delta_{k-1}(x), x_1 \cdot x_2, x_1 + x_2 \textbraceright$ 
2. $\textbraceleft 0, 1, 2, \dots, k - 1, \delta_0(x), \dots, \delta_{k-1}(x), x_1 \cdot x_2, x_1 \vee x_2 \textbraceright$ 
3. $\textbraceleft 0, 1, 2, \dots, k - 1, \delta_0(x), \dots, \delta_{k-1}(x), x_1 \vee x_2, x_1 \wedge x_2 \textbraceright$ 
4. Система Поста: $\textbraceleft \overline{x}, x_1 \vee x_2 \textbraceright$ , где $\overline{x}$ - отрицание поста
5. Функция Вэбби образует полную систему $\bigvee_k (x_1 \cdot x_2)$ 

$\square$  (Это доказательства 1, 2, 3 пункта)
1. Покажем, что любая функция $f \in F_k (n)$ представляется формулой следующего вида: $f(x_1, \dots, x_n) \equiv \sum\limits_{a_1, \dots, a_n \in \Omega_k^n} \delta_{a_1}(x_1) \cdot \text{ } \dots \text{ } \cdot \delta_{a_n}(x_n)\cdot f(a_1, \dots, a_n)$ 
Пусть $a_i = b_i, i \in \overline{1, n}$. Слагаемые правой части = 0 все, в которых $a_i \neq b_i$. Данные слагаемые принимают значение $f(b_1, \dots, b_n) =>$ верно (правая часть = левой части)
2. $f(x_1, \dots, x_n) \equiv \bigvee\limits_{(a_1, \dots, a_n)\in \Omega_k^n} \delta_{a_1}(x_1) \cdot \text{ } \dots \text{ } \cdot \delta_{a_n}(x_n)f(a_1, \dots, a_n)$  
3. $f(x_1, \dots, x_n) \equiv \bigvee\limits_{(a_1, \dots, a_n)\in \Omega_k^n} J_{a_1}(x_1) \wedge \dots \wedge J_{a_n}(x_n) \wedge f(a_1, \dots, a_n)$

   