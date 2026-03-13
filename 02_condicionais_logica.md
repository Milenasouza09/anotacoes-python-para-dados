# 📘 Estruturas Condicionais e Lógica em Python

Este material explica como programas podem **tomar decisões usando condições**.

---

# 🔀 Estruturas Condicionais

Estruturas condicionais permitem executar **diferentes ações dependendo de uma condição**.

---

# Estrutura `if`

```python
if condição:
    código
```

---

# Estrutura `if / else`

```python
if condição:
    código se verdadeiro
else:
    código se falso
```

Exemplo:

```python
media = 7

if media >= 6:
    print("Aprovado")
else:
    print("Reprovado")
```

---

# ⚖️ Operadores de comparação

| Operador | Significado |
|------|------|
| > | maior que |
| < | menor que |
| >= | maior ou igual |
| <= | menor ou igual |
| == | igual |
| != | diferente |

---

# 🔗 Estrutura `elif`

Usada quando temos várias condições.

```python
if condição1:
    código
elif condição2:
    código
else:
    código
```

Exemplo:

```python
nota = 7

if nota >= 9:
    print("Excelente")
elif nota >= 6:
    print("Aprovado")
else:
    print("Reprovado")
```

---

# 🧠 Operadores lógicos

| Operador | Função |
|------|------|
| and | todas as condições devem ser verdadeiras |
| or | pelo menos uma condição verdadeira |
| not | inverte o valor lógico |

---

# 📌 Operador `in`

Verifica se um elemento está dentro de um conjunto.

```python
lista = "Ana, Pedro, Carlos"

if "Pedro" in lista:
    print("Pedro está na lista")
```

---

# 📊 Tabelas verdade

## Operador AND

| A | B | Resultado |
|---|---|---|
| False | False | False |
| False | True | False |
| True | False | False |
| True | True | True |

---

## Operador OR

| A | B | Resultado |
|---|---|---|
| False | False | False |
| False | True | True |
| True | False | True |
| True | True | True |

---

## Operador NOT

| A | Resultado |
|---|---|
| True | False |
| False | True |

---

# 📚 Conclusão

Esses conceitos são fundamentais para aprender programação em Python e criar programas que tomam decisões.
