#### Вопрос 17

##### Монотонные, самодвойственные и аффинные функции. Критерий немонотонности.

Опр. Булева функция $f(x_1, \dots, x_n)$ называется *монотонной*, если из того, что $\alpha \preccurlyeq \beta$, следует, что $f(\alpha) \le f(\beta)$.

Опр. Наборы $\alpha = (a_1, \dots, a_n)$ и $\beta = (b_1, \dots, b_n)$ из $\Omega^n$ называют *соседними*, если они отличаются ровно в одной позиции, т.е.

$$
\exists i \in \overline{1,n}: a_i \ne b_i \text{ и } \forall j \ne i : a_j = b_j
$$

*Критерий немонотонности*. Булева функция $f(x_1, \dots, x_n)$ не является монотонной тогда и только тогда, когда существуют соседние наборы $\alpha$ и $\beta$, такие что $\alpha \preccurlyeq \beta$ и $f(\alpha) > f(\beta)$.

Опр. *Аффинной* называется булева функция аналитического вида

$$
f(x_0, x_1, \dots, x_{n-1}) = a_0x_0 \oplus a_0x_0 \oplus \dots \oplus a_{n-1}x_{n-1} \oplus b = \sum_{i=0}^{n-1}a_ix_i \oplus b \text{,}
$$

где $a_0, a_1, \dots, a_{n-1}, b \in \{0,1\}$.

Опр. Булева функция $f(x_1, \dots, x_n)$ называется *самодвойственной*, если $\overline{f}(\overline{x_1}, \dots, \overline{x_n}) = f(x_1, \dots, x_n)$.
