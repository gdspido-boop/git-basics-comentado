# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
Baixa todo o histórico, novas branches e commits do repositório remoto para a máquina.


**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
Combina o histórico baixado do repositório remoto com a branch local atual.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
Envia todos os commits locais da branch atual para o servidor remoto

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
Busca as novidades do servidor remoto e já as mescla imediatamente na branch atual.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

## Checklist deste arquivo

- [ x] 1. `git fetch [nome-remoto]`
- [ x] 2. `git merge [nome-remoto]/[branch]`
- [x ] 3. `git push [alias] [branch]`
- [ x] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
