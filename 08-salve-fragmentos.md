# 08. Salve fragmentos

> Arquive e restaure mudanças incompletas.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)

---

## Comandos desta seção (4)

### 1. `git stash`

```bash
git stash
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
ele serve para armazenar em uma pilha todas as alteracoes feitas tanto em staged unstaged, limpando todas as suas levados no stash.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 2. `git stash pop`

```bash
git stash pop
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
serve para trazer para a as alteracoes salvas na pilha anteriormente, trazendo todas as alteracoes, nesse caso no estilo lifo ulitmo a entrar primeiro a sair, removendo as modifcoes salvas da pilha

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 3. `git stash list`

```bash
git stash list
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
serve para listar todos os stash salvas na pilha, com suas respectivas posicoes na lista

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 4. `git stash drop`

```bash
git stash drop
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
ele vai deletar o determinado stash selecionado permanente sem aplicar no codigo atual.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

## Checklist deste arquivo

- [ x] 1. `git stash`
- [ x] 2. `git stash pop`
- [ x] 3. `git stash list`
- [x ] 4. `git stash drop`

---

[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)
