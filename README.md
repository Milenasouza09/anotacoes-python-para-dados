📘 Introdução ao Python com Google Colab

Este repositório contém anotações organizadas sobre fundamentos de Python, utilizadas durante aulas e estudos iniciais de programação.

O objetivo deste material é explicar conceitos de forma simples, clara e didática, para que qualquer iniciante consiga entender, mesmo sem experiência prévia com programação.

🚀 Google Colab

O Google Colab é uma plataforma online que permite escrever e executar código Python diretamente no navegador, sem precisar instalar nada no computador.

Ele é muito usado em:

Ciência de dados

Machine Learning

Estudos de programação

Prototipagem rápida de código

📄 Notebooks

No Colab, trabalhamos com Notebooks.

Um Notebook é um documento interativo que pode conter:

código

textos explicativos

gráficos

equações

resultados de execução

Os arquivos possuem a extensão:

.ipynb
🧩 Estrutura do Notebook

Os notebooks são divididos em células:

Tipo de célula	Função
Código	Executa programas
Texto	Explicações e documentação

Cada célula pode ser executada individualmente.

💻 O que é um Comando

Um comando é uma instrução que diz ao computador o que ele deve fazer.

Em programação, um programa é formado por vários comandos executados em sequência.

Exemplo:

print("Olá, mundo!")

Esse comando pede ao Python para exibir um texto na tela.

🖨️ Função print()

A função print() é usada para mostrar informações na tela.

Ela é muito utilizada para:

exibir resultados

testar códigos

depurar programas

Exemplo
print("Olá, mundo!")

Saída:

Olá, mundo!

Também podemos imprimir números:

print(10)

⚠️ Observação:

Textos precisam de aspas

Números não precisam

📦 Variáveis

Uma variável é um espaço na memória que armazena um valor.

Ela funciona como uma caixa com um nome, onde guardamos informações.

Exemplo
idade = 20

Nesse caso:

Elemento	Significado
idade	nome da variável
20	valor armazenado

Podemos usar essa variável depois:

print(idade)
⚠️ Regras para nomes de variáveis
❌ Não podem começar com números

Errado:

10_notas
2_alunos
❌ Não podem ter espaços

Errado:

nome aluno
nota final
❌ Não podem usar nomes reservados do Python

Errado:

print
input
type
🔤 Python diferencia maiúsculas e minúsculas

Em Python:

idade = 1
Idade = 2
IDADE = 3

São variáveis diferentes.

Exemplo:

print(idade, Idade, IDADE)

Saída:

1 2 3
📊 Tipos de dados em Python

Os principais tipos de dados são:

Tipo	Descrição	Exemplo
int	números inteiros	10, -5
float	números decimais	3.14, 2.5
str	texto	"Python"
bool	valores lógicos	True, False
🔍 Função type()

A função type() mostra o tipo de dado de uma variável.

Exemplo
idade = 20
print(type(idade))

Saída:

<class 'int'>
➗ Operadores Matemáticos
Exponenciação **

Usado para calcular potência.

2 ** 3

Resultado:

8

Porque:

2 × 2 × 2
Módulo %

Retorna o resto da divisão.

7 % 3

Resultado:

1
Divisão inteira //

Retorna apenas a parte inteira da divisão.

7 // 3

Resultado:

2
📝 Strings

Strings são variáveis que armazenam textos.

Exemplo:

texto = "Python é incrível"

Strings possuem métodos, que são funções usadas para manipular o texto.

🔧 Métodos de String
upper()

Transforma o texto em maiúsculo.

texto.upper()

Resultado:

PYTHON É INCRÍVEL
lower()

Transforma o texto em minúsculo.

texto.lower()
strip()

Remove espaços no início e no final do texto.

texto.strip()
replace()

Substitui um caractere por outro.

texto = "Sanyos"
texto.replace('y','t')

Resultado:

Santos
🌍 Unicode

Python utiliza o padrão Unicode, que permite trabalhar com caracteres de vários idiomas.

O Unicode possui mais de 140 mil caracteres.

Função chr()

Retorna um caractere a partir de um código Unicode.

chr(64)

Resultado:

@

Também podemos concatenar caracteres:

chr(79) + chr(108) + chr(225)

Resultado:

Olá
⌨️ Entrada de dados com input()

A função input() permite que o usuário digite informações.

Exemplo:

nome = input("Digite seu nome: ")

⚠️ Importante:

input() sempre retorna uma string.

🔄 Conversão de tipos

Para converter valores usamos:

Função	Conversão
int()	inteiro
float()	decimal
str()	texto
bool()	booleano

Exemplo:

idade = int(input("Digite sua idade: "))
🧾 Formatação de Strings
f-string (forma recomendada)
nome = "Ana"
idade = 20

print(f"Meu nome é {nome} e tenho {idade} anos")
Método .format()
print("Nome: {}".format(nome))
Operador %
print("Nome: %s" % nome)
🔤 Caracteres especiais
Código	Função
\n	nova linha
\t	tabulação
\\	barra invertida
\"	aspas duplas
\'	aspas simples

Exemplo:

print("Linha 1\nLinha 2")
🔀 Estruturas Condicionais

As estruturas condicionais permitem que o programa tome decisões.

Estrutura if
if condição:
    código
Estrutura if / else
if condição:
    código se verdadeiro
else:
    código se falso
Exemplo
media = 7

if media >= 6:
    print("Aprovado")
else:
    print("Reprovado")
⚖️ Operadores de comparação
Operador	Significado
>	maior que
<	menor que
>=	maior ou igual
<=	menor ou igual
==	igual
!=	diferente
🔗 Estrutura elif

Usada quando temos várias condições.

if condição1:
    código
elif condição2:
    código
else:
    código
Exemplo
nota = 7

if nota >= 9:
    print("Excelente")
elif nota >= 6:
    print("Aprovado")
else:
    print("Reprovado")
🧠 Operadores Lógicos
Operador	Função
and	todas as condições devem ser verdadeiras
or	pelo menos uma condição verdadeira
not	inverte o valor lógico
📌 Operador in

Verifica se um elemento está presente em um conjunto.

Exemplo:

lista = "Ana, Pedro, Carlos"

if "Pedro" in lista:
    print("Pedro está na lista")
📊 Tabelas Verdade
Operador AND
A	B	Resultado
False	False	False
False	True	False
True	False	False
True	True	True
Operador OR
A	B	Resultado
False	False	False
False	True	True
True	False	True
True	True	True
Operador NOT
A	Resultado
True	False
False	True
