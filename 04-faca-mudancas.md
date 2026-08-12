# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
ele mostra os status de todos os arquivos, por exmeplo arquivos modificados , arquvios novos, arquivos ainda n adicionados em um commit, arquivos adicionados.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
ele mostra todas diferencas da branch atual a branch inicialmente, ou seja, estou num branch, modifio alguns arquivos, se eu der git diff vou consegui validar as modificacoes.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
ele e utilzado para mandar as alteracoes para o estagio de preparacao, que seria o stage, que depois que fazer alteracoes e dar esse comando vc consegue dar commit e enviar essas alteracoes, se eu n der git add essas alteracoes n iriam entrar no commit como alteracoes novas.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
nesse ele vai verificar somente as alteracoes que estao staged.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
serve para o desenvolvedor retonar o commit as alteracoes feitas em um commit anteriormente.
**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
serve para commit na branch local com um nome bem estruturado, dae depois da pra dar push e ir para branch remota. 

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

## Checklist deste arquivo

- [ x ] 1. `git status`
- [ x ] 2. `git diff`
- [ x ] 3. `git add [arquivo]`
- [ x ] 4. `git diff --staged`
- [ x ] 5. `git reset [arquivo]`
- [ x ] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
