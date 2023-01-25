#### Вопрос 47

Теорема об ограниченной дедукции.

Теорема. (об ограниченной дедукции)

Пусть $T$ - произвольное множество формул исчисления предикатов, $A,B$ - формулы исчисления предикатов. Если $T \cup \{A\} \vdash B ( T,A \vdash B)$ и $\exist$ вывод, не использующий правила $\forall$ введения и $\exist$ удаления, то $T,A \vdash B \Leftrightarrow T \vdash A \rightarrow B$.

Доказательство:

Метод математической индукции по длине вывода формулы $B$ 

$B_1,\ldots,B_m = B$ - есть вывод формулы $B$

1) $m = 1 \rightarrow $ существуют 2 случая:

   1) $B$ - аксиома $\Rightarrow$ по формуле 1: $\vdash A \rightarrow B$
   2) $B$ - исходная формула $(B \in T $ или $ B = A)$ 

   $B = A$ по формуле 2: $\vdash A \rightarrow B$

   $B \in T$ по формуле $I_1:B \rightarrow (A \rightarrow B)$ и правилу заключения $\frac{B,B\rightarrow (A\rightarrow B)}{A \rightarrow B} \space (B,B\rightarrow (A \rightarrow B) \vdash (A \rightarrow B))$

2) Шаг индукции

   Пусть теорема верна для вывода $< m$

   Докажем для $m$ 

   Если $B \in T \cup\{A\}$ или $B$ - аксиома, то верно по пункту 1.

   Предположим, что $B$ получено по правилу исключения из формул $B_i$ и $B_j$, $i,j < m$. Так как $i,j < m \Rightarrow T,A \vdash B_i, T,A \vdash B_j \Rightarrow T \vdash A \rightarrow B_i, T \vdash A \rightarrow B_j \Rightarrow T\vdash A \rightarrow (B_i \rightarrow B), T\vdash A \rightarrow (B_j \rightarrow B),$  

   Рассмотрим	$T\vdash A \rightarrow (B_i \rightarrow B)$

   $(A \rightarrow (B_i \rightarrow B)) \rightarrow ((A \rightarrow B_i) \rightarrow (A \rightarrow B))$

   $T \vdash (A \rightarrow B_i) \rightarrow (A \rightarrow B)$

   По правилу заключения, что и требовалось доказать.