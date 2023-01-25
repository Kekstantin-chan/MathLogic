#### Вопрос 25

##### Операция обобщенного склеивания. Алгоритм Блейка.

1. Операция обобщенного склеивания:

$XA∨\overline{X}B=XA∨\overline{X}B∨AB$

2. Метод Блейка

Метод Блейка для построения сокращенной ДНФ из произвольной ДНФ состоит в применении правил обобщенного склеивания и поглощения.
Подразумевается, что правила применяются слева направо. На первом этапе производится операция обобщенного склеивания до тех пор, пока это возможно.
На втором производится операция поглощения. (поглощение: $A∨A∙b=A$)

**АЛГОРИТМ БЛЕЙКА**

1) Cтроим произвольную ДНФ функции $f$.
2) Выполняем все возможные операции обобщенного склеивания
3) Каждую ЭК (элементарную конъюнкцию) вида $\phi \psi$ заменяем либо равносильной ей импликантой $f$, либо $\varnothing$. В результате получаем кукую-то ДНФ функции $f$.
4) Выполняем все операции поглощения ($\phi \vee \phi \wedge \psi \equiv \phi$)
5) в п.4 нашли сокращенную ДНФ функции $f$

#### Пример:

Построить сокращенную ДНФ по ДНФ $D$ функции $F(X,Y,Z)$, где
$D=xy∨\overline{x}z∨\overline{y}z$

После первого этапа получаем:
$D_1=xy∨\overline{x}z∨\overline{y}z∨yz∨xz∨z$

После второго этапа получаем сокращенную ДНФ:
$D_2=xy∨z$