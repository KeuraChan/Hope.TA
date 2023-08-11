# Hope.TA
Repositório criado para manter os exercícios realizados em aula de tópicos avançados com o professor algusto manzano

##As aulas e exercícios aqui apresentados utilizaram da linguagem Hope para entender o conceitos da programação funcional.

hope
```
dec x_pi : num;
--- x_pi <= 3.14159;

dec acirc : num -> num;
--- acirc r <= x_pi * pow (r, 2);

dec soma : num # num -> num;
--- soma (x, y) <= x + y;

dec media: num # num # num -> num;
--- media (x,y,z) <= (x + y + z) / 3;
```

No código:

hope
```
dec x_pi : num;
--- x_pi <= 3.14159;
```
É feita a declaração da função x_pi que não tem entrada, e possui um 'retorno' de valor NUMÉRICO (num);
'---' é a codificação da ação que será realizada. No exemplo, colocando o valor 3.14159 em x_pi
