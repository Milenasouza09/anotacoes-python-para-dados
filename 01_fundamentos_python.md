# 📘 Fundamentos de Python com Google Colab

Este material apresenta os **conceitos básicos de programação em Python**, explicados de forma simples e didática para iniciantes.

---

# 🚀 Google Colab

O **Google Colab** é uma plataforma online que permite escrever e executar **código Python diretamente no navegador**, sem precisar instalar nada no computador.

Ele é muito utilizado para:

- estudos de programação
- ciência de dados
- machine learning
- prototipagem de código

---

# 📄 Notebooks

No Google Colab utilizamos **Notebooks**.

Um Notebook é um documento interativo que pode conter:

- código
- textos explicativos
- gráficos
- equações
- resultados de execução

Os arquivos possuem a extensão:

```
.ipynb
```

---

# 🧩 Estrutura do Notebook

Os notebooks são divididos em **células**.

| Tipo | Função |
|-----|------|
| Célula de código | Executa programas |
| Célula de texto | Explicações e anotações |

Cada célula pode ser executada separadamente.

---

# 💻 O que é um Comando

Um **comando** é uma instrução que diz ao computador o que ele deve fazer.

Exemplo:

```python
print("Olá, mundo!")
```

Esse comando pede ao Python para **exibir um texto na tela**.

---

# 🖨️ Função `print()`

A função `print()` é usada para **mostrar informações na tela**.

```python
print("Olá, mundo!")
```

Saída:

```
Olá, mundo!
```

Também podemos imprimir números:

```python
print(10)
```

⚠️ Observação

- textos precisam de aspas
- números não precisam

---

# 📦 Variáveis

Uma **variável** é um espaço que armazena informações.

```python
idade = 20
```

Podemos usar depois:

```python
print(idade)
```

---

# ⚠️ Regras para nomes de variáveis

## ❌ Não podem começar com números

```
10_notas
2_alunos
```

## ❌ Não podem ter espaços

```
nome aluno
nota final
```

## ❌ Não podem usar nomes reservados do Python

```
print
input
type
```

---

# 🔤 Python diferencia maiúsculas e minúsculas

```python
idade = 1
Idade = 2
IDADE = 3

print(idade, Idade, IDADE)
```

Saída:

```
1 2 3
```

---

# 📊 Tipos de dados

| Tipo | Descrição | Exemplo |
|----|----|----|
| int | números inteiros | 10 |
| float | números decimais | 3.14 |
| str | texto | "Python" |
| bool | lógico | True / False |

---

# 🔍 Função `type()`

Mostra o tipo de dado.

```python
idade = 20
print(type(idade))
```

---

# ➗ Operadores matemáticos

## Exponenciação

```python
2 ** 3
```

Resultado:

```
8
```

---

## Módulo

Retorna o resto da divisão.

```python
7 % 3
```

Resultado:

```
1
```

---

## Divisão inteira

```python
7 // 3
```

Resultado:

```
2
```

---

# 📝 Strings

Strings armazenam textos.

```python
texto = "Python é incrível"
```

---

# 🔧 Métodos de String

```python
texto.upper()
texto.lower()
texto.strip()
texto.replace('y','t')
```

---

# 🌍 Unicode

Python utiliza o padrão **Unicode**, permitindo trabalhar com caracteres de diferentes idiomas.

---

## Função `chr()`

```python
chr(64)
```

Resultado:

```
@
```

---

# ⌨️ Entrada de dados

```python
nome = input("Digite seu nome: ")
```

⚠️ `input()` sempre retorna **string**.

---

# 🔄 Conversão de tipos

| Função | Conversão |
|------|------|
| int() | inteiro |
| float() | decimal |
| str() | texto |
| bool() | booleano |

Exemplo:

```python
idade = int(input("Digite sua idade: "))
```

---

# 🧾 Formatação de strings

## f-string

```python
nome = "Ana"
idade = 20

print(f"Meu nome é {nome} e tenho {idade} anos")
```

---

# 🔤 Caracteres especiais

| Código | Função |
|------|------|
| \n | nova linha |
| \t | tabulação |
| \\ | barra invertida |
