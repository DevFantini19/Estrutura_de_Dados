# 🔁 Estrutura de Dados: Pilha e Fila em Python

Este projeto foi desenvolvido como parte da disciplina **Estruturas de Dados** no curso de Análise e Desenvolvimento de Sistemas da Unicesumar. O desafio consistia em identificar, analisar e separar corretamente os métodos de **Pilha (LIFO)** e **Fila (FIFO)** presentes em um código misturado, organizando-os em duas classes distintas em Python.

## 🎯 Objetivo

- Praticar os conceitos de estruturas de dados lineares: **Pilha** e **Fila**.
- Refatorar um código misto, separando corretamente os métodos por estrutura.
- Aplicar boas práticas de organização e legibilidade de código Python.

## 🧱 Estruturas Implementadas
🪜 Classe `Pilha`
- `empilhar(valor)`: Adiciona elemento ao topo da pilha.
- `retirar()`: Remove e retorna o elemento do topo da pilha.
- `esta_vazia()`: Verifica se a pilha está vazia.
- `__str__()`: Exibe os elementos do topo à base da pilha.

🧃 Classe `Fila`
- `adicionar(valor)`: Insere elemento no final da fila.
- `adicionar_varios(lista_valores)`: Insere vários elementos de uma vez.
- `remover()`: Remove e retorna o primeiro elemento da fila.
- `__str__()`: Exibe os elementos da frente para trás da fila.

🧪 Tecnologias
- Linguagem: **Python 3**
- Módulos utilizados:
  - `collections.deque`
  - `typing.Deque`

 📌 Aprendizados

- Diferença entre os comportamentos LIFO e FIFO.
- Aplicação de listas e `deque` em Python.
