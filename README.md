----------------
Algoritmo para calcular raízes

1.DESCRIÇÃO DO PROBLEMA
2.LINGUAGEM MATEMÁTICA
3.PORTUGUÊS ESTRUTURADO
4.FLUXOGRAMA
5.USO DO TERMO "POLYA" NO NOME DO REPOSITÓRIO.

----------------



1.DESCRIÇÃO DO PROBLEMA





2.LINGUAGEM MATEMÁTICA

q = q/2 + n/(2*q)

n = Valor que se deseja obter a raiz;
q = Valor igual a n, que conforme a aplicação da fórmula muda.



3.PORTUGUÊS ESTRUTURADO


algoritmo "CalculaRaiz"

raizq: real (real);

variável
    n:real;

inicio  
  
    ler(n);
    
    escrever(raizq(n));
fim



raizq: real (n: real)

inicio
    x:inteiro;
    q: real;
    q = n;
    
    para x de 0  até 200 passo x faça
          q = q/2 + n/(2*q);

    retorne (n);

    fim_para
            
fim



4.FLUXOGRAMA

![Alt text]()



5.USO DO TERMO "POLYA" NO NOME DO REPOSITÓRIO.


