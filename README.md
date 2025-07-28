# 01 - Introdução às Linguagens de Programação
##  Linha do Tempo (Resumo)

 Destaques: 

-**Ano: 1957 – Linguagem: Fortran    Destaque: Primeira linguagem de alto nível**
-**Ano: 1958  –Linguagem: LISP       Destaque: Primeira linguagem funcional, usada em Inteligência Artificial.**
-**Ano: 1964 – Linguagem: BASIC      Destaque: Desenvolvida para iniciantes.**
-**Ano: 1970 – Linguagem: Pascal     Destaque: Linguagem estruturada para ensino.**
-**Ano: 1972 – Linguagem: C          Destaque: Controle direto de memória** 
-**Ano: 1983 – Linguagem: C++        Destaque: Introduziu OOP** 
-**Ano: 1991 – Linguagem: Python     Destaque: Alta legibilidade**
-**Ano: 1995 – Linguagem: Java       Destaque: Plataforma independente (JVM)**
-**Ano: 1995 – Linguagem: JavaScript Destaque: Linguagem para web.**
-**Ano: 2000 – Linguagem:C#:         Destaque: Utilizada no desenvolvimento de aplicações .NET, jogos, e outros tipos de software.**
-**Ano:2009 – Linguagem: Go         Destaque: Simplicidade + concorrência** 
-**Ano:2010  – Linguagem: Rust       Destaque: Segurança sem GC**

# 2. Ambientes de Programação

    Compilador: traduz todo o código antes da execução (ex.: GCC para C).

    Interpretador: executa linha a linha (ex.: Python).

    Máquina Virtual: simula um ambiente (ex.: JVM para Java). Um diagrama pode mostrar esses três atuando sobre diferentes linguagens e suas interações com hardware.

   # 3. Descrições Sintáticas e Semânticas
      Linguagem GSM
      Printar("Ola mundo");
      Se(1+1==2){
      retornar verdade;}
      ou{retornar falso;}

   #   4. Tipos de Dados

     Python: tipagem dinâmica e forte. x = 5

    C: tipagem estática e fraca. int x = 5;

    JavaScript: dinâmica e fraca. var x = 5; x = "texto"; Explica como cada uma lida com tipos durante execução.

  # 5. Estruturas de Controle
   Python
for i in range(5):
    if i % 2 == 0:
        print(f"{i} é par")
    else:
        continue
Esse código usa repetição, seleção e controle de fluxo.


# 6. Subprogramas

    C:void altera(int* x) { *x = 10; }
    Python:def altera(x): x[0] = 10
   Demonstram passagem por referência.

  # 7. Implementação de Subprogramas

Desenhe uma pilha para uma função recursiva como:
def fatorial(n):
    return 1 if n == 0 else n * fatorial(n - 1)
A pilha cresce até n==0 e depois desfaz.

# 8. Programação Orientada a Objetos

Modelo com classes:
class Personagem:
    def __init__(self, nome): self.nome = nome

class Guerreiro(Personagem):
    def atacar(self): print("Ataque poderoso!")
    
# 9. Concorrência

Diferença:

    Thread: compartilha memória.

    Processo: memória isolada. Exemplo com Python:

    from threading import Thread
def tarefa(): print("Executando em thread")
Thread(target=tarefa).start()

# 10. Gerenciamento de Memória
Linguagem	Tipo de Gerenciamento	Exemplo
C	Manual (malloc/free)	|int* p = malloc(sizeof(int));
Java	Automático (GC)	  |Integer x = new Integer(5);


# 11. Programação Funcional
python
def dobra(x): return x * 2
lista = [1, 2, 3]
print(list(map(dobra, lista)))  # [2, 4, 6]
Funções de alta ordem + recursão = essência funcional.

# 12. Programação Lógica

Exemplo em pseudocódigo:

pai(joao, pedro).
pai(pedro, lucas).
avo(X, Y) :- pai(X, Z), pai(Z, Y).
Consulta: avo(joao, lucas) retorna verdadeiro.

# 13. Linguagens para Scripts e Web
 python:
    import os
print("Arquivos:", os.listdir())
Um script simples para listar arquivos locais.

# 14. Tendências em Linguagens de Programação
Rust é uma linguagem moderna que foca em:

    Segurança sem coletor de lixo

    Performance comparável ao C++

    Excelente para sistemas embarcados e web (via WebAssembly)

      
