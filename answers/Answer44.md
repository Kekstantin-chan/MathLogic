#### Вопрос 16

Общее понятие о логическом исчислении. Выводимость и доказуемость формул.

Логическое исчисление характеризуется наличием алфавита, правил построения формул,  системой аксиом и правилами вывода.

§ Выводимость и доказуемость формул

$T$ - множество ФИП (формулы исчисления предикатов)

$A$ - ФИП (формула исчисления предикатов)

Опр.

Говорят, что $A$ выводится из $T (T \vdash A)$, если $\exist$ конечная последовательность формул $A_1,\ldots,A_n$, такая, что:

1) $A_n = A$
2) $\forall i \in \overline{1,n},A_i$ - либо аксиома, либо $A_i \in T$, либо получена из остальных $A_i$ по каким-то правилам вывода.

$T = \oslash \Rightarrow$ говорят $A$ - доказуема и обозначается: $+A$ 

$A+B \Rightarrow +(A\rightarrow B)$, где $A$ - любая формула

1) $I_1, \space B \rightarrow (A \rightarrow B)$ - согласимся на аксиомы, применяем аксиому 1 $\Rightarrow B \Rightarrow$ - используем правильно заключения 
2) $B$
3) По правилу заключения $A \rightarrow B$