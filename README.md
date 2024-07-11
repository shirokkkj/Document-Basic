# ** POR ONDE COMEÇAR? **

- Bom, na verdade o Python é muito amplo e com uma diversidade de áreas muito grande, então, sendo bem abrangente. Mas como o intuito dessa "documentação" é ser introdutória ao básico, vou escrever um roadmap simples pra você ter o guia de onde estudar.

_INTRODUÇÃO AO BÁSICO_ 
  - Tipos Primitivos
  - Inputs
  - Operadores Aritiméticos
  - Módulos
  - Manipulação de String
  - Condições
      - ~~Condições Aninhadas~~
    
_BÁSICO INTERMEDIÁRIO_
  - Listas e Dicionários
      - E seus métodos
  - Loops ( ~~While/For~~ )
  - Tuplas
      - **Sua utilidade e porquê usar**
  - Funções

_BÁSICO-AVANÇADO_
  - POO ( Programação Orientada a Objeto / Classes )
  - Bibliotecas como Flask, Selenium, Django...
  - Estudo à fundo sobre o básico intermediário.

**Alguns canais que EU recomendo você assistir: [Hashtag Programação]([url](https://www.youtube.com/c/HashtagProgramação)) e [Gustavo Guanabara]([url](https://youtu.be/S9uPNppGsGo?si=ITQVF5agodE68mTf))**

# DOCUMENTAÇÃO

- Bom, como nem só de recomendação vive o homem, eu vou te passar algumas informações do Básico Básico. O resto é por sua conta, meu filho.

  **TIPOS PRIMITIVOS**
  - Bem, você lembra que quando estavamos na parte do PvP do RPG, na hora de subtrair a vida do monstro pelo Dano do Player, deu erro, não foi? E se você analisar bem, o erro dizia que por tentarmos tratar uma variável do tipo **INT** e outra do tipo **STR**, não se foi possível executar o código. E bom, o que fizemos foi tratar aqueles dados a partir do seu **TIPO PRIMITIVO**, que em suma e de forma simplificada, é o tipo da variável. Seja ela um número, uma frase, um índice de itens, todas as variáveis tem um tipo, mas por padrão, ela é considerada como uma variável do tipo **STRING**, que são **TEXTOS**. Por isso que, ao tentar executar esse código:
```
n1 = input('Digite um número: ')
n2 = input('Digite um número: ')
soma = n1+n2
print(soma)
```
- Ele não vai executar da forma em que esperamos, mas por quê? Como eu falei, as variáveis por padrão são Tipadas ou tratadas como uma **STRING**, ou seja, um texto. E então, como resolver isso? Temos que tratar aquela variável como um valor inteiro, um número! E no Python, fazemos dessa maneira:
```
n1 = int(input('Digite um número: '))
n2 = int(input('Digite um número: '))
soma = n1+n2
print(soma)
```
- E agora sim, desta maneira, o código vai executar da maneira em que esperamos, sem falhas. Mas o que eu fiz aí? Eu tratei os dados das variávies **N1 E N2** como **"int"**, que são números inteiros, sem casas decimais. E agora que eu te expliquei sobre o que são tipos primitivos e qual é o "padrão", vou deixar uma listinha aí com os principais, deixando claro que também existem outros.

- int: Números INTEIROS como 1, 10, 100, 827192, 3
- float: Números FLUTUANTES, aqueles que levam casas decimais, como 1.0, 92002821.291, 91.0
- bool: Valores BOLEANOS, ou seja, **VERDADEIRO** e **FALSO**
- str: Strings, ou seja, textos e letras, como "Arroz", "Comi Feijão", "a"

- Lembrando que TODA STRING deve ser acompanhada de aspas, sejam elas duplas ou simples.

- Se você quiser complementar essa "aulinha", veja o vídeo do Guanabara. [Tipos Primitivos]([url](https://youtu.be/hdDHg1p3YVc?si=CS9qHBHYtPC9ZO0l))
