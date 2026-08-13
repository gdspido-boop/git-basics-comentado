# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
serve para adicionar arquivos que vc gostaria que ficasse fora de rastramento do git.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

<!-- TODO: escreva sua explicação aqui. Uma frase por linha. -->
Lista todos os arquivos do projeto que estão sendo ignorados pelo seu gitignore
Mostra detalhadamente o que o Git está ocultando do monitoramento no momento.

**Quando usar / observação:**

<!-- TODO: opcional, mas conta ponto. -->

---

## Checklist deste arquivo

- [ x] 1. Arquivo `.gitignore`
- [ x] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
