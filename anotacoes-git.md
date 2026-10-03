# 📝 Anotações de Git

Registro dos principais comandos praticados durante meu laboratório de **Git e GitHub**.

Este arquivo funciona como uma referência rápida para revisar os comandos já estudados.

---

## 🚀 Inicialização

### `git init`

Inicializa um novo repositório Git na pasta atual.

```bash
git init
```

Após esse comando, o Git passa a acompanhar o projeto.

---

## 🔎 Verificando o repositório

### `git status`

Mostra o estado atual do repositório.

```bash
git status
```

Com esse comando é possível verificar:

- arquivos modificados;
- arquivos ainda não rastreados;
- arquivos adicionados à área de staging;
- estado atual da branch.

---

## 📦 Staging

### `git add`

Adiciona alterações à área de preparação (**staging area**) antes de criar um commit.

Para adicionar um arquivo específico:

```bash
git add README.md
```

Para adicionar todas as alterações:

```bash
git add .
```

---

## 💾 Commits

### `git commit`

Cria um registro das alterações adicionadas à área de staging.

```bash
git commit -m "mensagem do commit"
```

Exemplo:

```bash
git commit -m "docs: atualiza README"
```

Uma boa mensagem de commit deve indicar de forma objetiva o que foi alterado.

---

## 📜 Histórico

### `git log`

Exibe o histórico de commits do repositório.

```bash
git log
```

O histórico pode mostrar informações como:

- hash do commit;
- autor;
- data;
- mensagem do commit.

---

## 🔄 Comparação de alterações

### `git diff`

Mostra diferenças entre versões ou alterações ainda não adicionadas à área de staging.

```bash
git diff
```

Esse comando ajuda a revisar o que foi modificado antes de criar um commit.

---

## 🌿 Branches

### `git branch`

Exibe as branches existentes no repositório.

```bash
git branch
```

Neste laboratório, a branch principal utilizada é:

```text
main
```

Branches permitem trabalhar em linhas de desenvolvimento separadas dentro do mesmo projeto.

---

## 🧠 Fluxo básico praticado

Um fluxo simples de trabalho com Git pode seguir esta sequência:

```bash
git status
git add .
git commit -m "mensagem do commit"
git log
```

Quando necessário, também posso revisar as alterações antes do commit:

```bash
git diff
```

---

## 📌 Resumo rápido

| Comando | Função |
|---|---|
| `git init` | Inicializa um repositório Git |
| `git status` | Mostra o estado atual dos arquivos |
| `git add` | Adiciona alterações à área de staging |
| `git commit` | Registra alterações no histórico |
| `git log` | Exibe o histórico de commits |
| `git diff` | Mostra diferenças entre alterações |
| `git branch` | Exibe as branches do repositório |

---

## ✅ Status das anotações

Comandos registrados até o momento:

- [x] `git init`
- [x] `git status`
- [x] `git add`
- [x] `git commit`
- [x] `git log`
- [x] `git diff`
- [x] `git branch`

Este arquivo será ampliado conforme novos comandos forem realmente praticados.
