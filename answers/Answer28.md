#### Вопрос 28

##### Алгоритм Нельсона получения сокращенной ДНФ из произвольной КНФ. Теорема о корректности алгоритма Нельсона

1. $\sqsupset f=k_1\dots k_s$ - КНФ, $k_i$ - ЭД (элементарная дизъюнкция)
2. По закону дистрибутивности раскроем скобки и каждую элементарную конъюнкцию заменим на $\O$, либо равной ей импликантой $t$
3. В получившейся на шаге 2. ДНФ выполним все операции сокращения $(x\vee xy\equiv x)$
4. В результате шага 3. имеем сокращенную ДНФ