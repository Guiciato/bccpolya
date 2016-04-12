*********************************************
Algoritmo para calcular raízes

1.DESCRIÇÃO DO PROBLEMA

2.LINGUAGEM MATEMÁTICA

3.PORTUGUÊS ESTRUTURADO

4.FLUXOGRAMA

5.USO DO TERMO "POLYA" NO NOME DO REPOSITÓRIO.

*********************************************



1.DESCRIÇÃO DO PROBLEMA

Determinar a raiz quadrada consiste em calcular o número que, elevado ao quadrado, gera o valor desejado. Por exemplo, a raiz quadrada do número 25 corresponde ao número 5, pois 5² é igual a 25. Em algumas situações, descobrir esse número por tentativa pode ser muito cansativo e bastante complicado. 




2.LINGUAGEM MATEMÁTICA

q = q/2 + n/(2*q)

n = Descreva o valor da raiz;
q = Valor igual a n, que depedendo da aplicação da fórmula muda.



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

![Alt text] https://www.gliffy.com/go/html5/10400717



5.USO DO TERMO "POLYA" NO NOME DO REPOSITÓRIO.

Polya criou um método para resolver problemas que é dívido em 4 etapas:ENTENDA O PROBLEMA, CONSTRUA UMA ESTRATÉGIA DE RESOLUÇÃO, EXECUTE A ESTRATEGIA E REVISE.

1) ENTENDA O PROBLEMA: É necessário que você leia com atenção para entende-lô.

2) CONSTRUA UMA ESTRATÉGIA DE RESOLUÇÃO: Para fazer isso primeiro é necessário ter feito o primeiro passo corretamente para fazer uma estratédia que pode ser feita com elementos do problema.

3) EXECUTE A ESTRATEGIA:Para executar a estratédia é simples, só precisa usar os elementos conseguidos e representa-lôs com clareza

4) REVISE: Nesse passo é importante por causa dele podemos ver se estamos correto e ver a solução com outros métodos

