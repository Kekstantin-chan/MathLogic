#### Вопрос 45

Основные аксиомы исчисления предикатов и правила вывода.

$ \Large\textsection$ Аксиомы исчисления предикатов

$A,B,C$ - формулы, $I,II,\ldots$ - группы аксиом

$I.$ 		

1) $A \rightarrow (B \rightarrow A)$

2) $(A \rightarrow (B \rightarrow C)) \rightarrow ((A \rightarrow B) \rightarrow (A \rightarrow C))$ 

$II.$ 	  

1) $A \& B \rightarrow A$
2) $A\&B \rightarrow B$
3) $(A \rightarrow B) \rightarrow ((A \rightarrow C) \rightarrow(A \rightarrow B\&C) )$

$III.$

1) $A \rightarrow A \vee B $
2) $B \rightarrow A \vee B$
3) $(A \rightarrow C) \rightarrow ((B \rightarrow C) \rightarrow(A \vee B \rightarrow C) )$;

$IV.$

1) $A \rightarrow \overline{\overline{A}}$
2) $\overline{\overline{A}} \rightarrow A$
3) $(A \rightarrow B) \rightarrow (\overline{B} \rightarrow \overline{A})$

$V.$ Навешивание кванторов

1) $\forall x: A(x) \rightarrow A(t)$
2) $A(t) \rightarrow \exist x:A(x)$

$A(x)$ - формула, содержащая свободное вхождение $x$

A(t) получено из A(x) заменой x параметром t

$\Large \textsection$ Правила вывода 

1) Правило заключения $A,\frac{A \rightarrow B}{B} \space (A,A \rightarrow B \vdash B)$ - из $A$ и $A \rightarrow B$ доказуема (выводится) $B$
2) Правило введения всеобщности (правило $\forall$ введения) $\frac{B \rightarrow A}{B \rightarrow \forall \times A} \space (B\rightarrow A \vdash B \rightarrow \forall \times A)$
3) Правило удаления существования $\frac{A\rightarrow B}{\exist \times A \rightarrow B} \space (A \rightarrow B \vdash \exist \times A \rightarrow B)$

