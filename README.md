# Big O: O(1)

## Exemplo prático

O `O(1)` representa uma operação que leva praticamente o mesmo tempo para ser executada, independente da quantidade de elementos.

Neste exemplo, temos uma lista com alguns números e acessamos diretamente o elemento que está no índice 1.

```python
numeros = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100]

# Acesso direto ao elemento de índice 1
elemento = numeros[1]

print("Elemento encontrado:", elemento)
```

O resultado será:

```text
Elemento encontrado: 20
```

## Por que é O(1)?

É O(1) porque estamos acessando diretamente uma posição da lista através do índice.

Não importa se a lista tem 10, 100 ou 1.000 elementos. Ao fazer `numeros[1]`, o programa vai direto para aquela posição, sem precisar passar pelos outros elementos.

Por isso, esse tipo de acesso possui complexidade constante, ou seja, **O(1)**.

## Como executar

Com o Python instalado, basta executar:

```bash
python pratica_bigO.py
```

E o resultado será:

```text
Elemento encontrado: 20
```
