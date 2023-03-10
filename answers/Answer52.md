#### Вопрос 52

Интерпретация исчисления. Теорема об истинности формулы, выводимой из набора формул, истинных в некоторой интерпретации. Теорема Геделя о полноте (без. док.)

*Семантика исчисления предикатов*

$L$ - логическое исчисление (исчисление предикатов)

$\Large\upsigma$ - сигнатура

Опр.

Интерпретацией исчисления $L$ называется любое множество $M$ с фиксированным отображением $\nu$ сигнатуры $\Large \upsigma$ в множество операций и предикатов множества $M$, при котором $n$-арной операции из $\Large \upsigma$ соответствует $n$-арная операция из множества $M$, а $n$ - арному предикату из $\Large \upsigma$ соответствует $n$-арный предикат над $M$.

$\nu$ - отображение

$f$ - $n$-арная операция из $\Large \upsigma$

$f^{\nu}$ - $n$-арная операция из $M$

$p$ - предикат из $\Large \upsigma$

$p^{\nu}$ - предикат над $M$

Интерпретация $(M,\nu)$

Константы $L$ - $\emptyset$- местные операции над $M$ 

Операции и предикаты из $\Large \upsigma$ - используем операции и предикаты над $M$

Получаем, $A'$ - представление $A$ в интерпретации $(M,\nu)$

Опр.

ФИП (формула исчисления предикатов) выполнима, истинна или ложна, если выполнима, истинна и ложна в интерпретации $(M,\nu)$

Опр.

ФИП (формула исчисления предикатов) тождественно истинна, если она истинна во всех интерпретациях

Теорема.

Если каждая формула множества $T$ истинна в некоторой интерпретации $(M,\nu)$, $T \vdash A \Rightarrow A$ истинна в этой интерпретации $(M,\nu)$

Доказательство

Метод математической индукции по длине вывода $A$. Формула $A$ приводит к проверке аксиом и правил вывода в $(M,\nu)$

Следствие 1.

Всякая формула исчисления предикатов, которая является доказуемой, истинна в любой интерпретации $(M,\nu)$ исчисления предикатов

Следствие 2.

ИП (исчисление предикатов) противоречиво - никакая формула ИП не может быть доказана вместе со своим отрицанием

Теорема. (Геделя о полноте)

ИП полно, то есть если формула исчисления предикатов истинна во всех интерпретациях $(M,\nu)$, то она доказуема в исчислениях предикатов.