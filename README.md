# 🚀 Exercício 5A — Controle de Entrada por Faixa Etária

Aplicação desenvolvida em PHP como etapa de uma tarefa prática de desenvolvimento de software.

---

## 📋 Visão Geral

A proposta deste exercício é construir uma aplicação direta que coleta o nome e o ano em que o usuário nasceu, processa sua idade exata e valida se a pessoa tem no mínimo 18 anos para conceder a entrada.

---

## ⚙️ Recursos e Comportamento

* 📝 Campo de entrada para o nome do visitante.
* 📅 Campo de entrada para o ano de nascimento.
* 🧮 Processamento automático da idade.
* ✅ Liberação de entrada para maiores de idade (≥ 18 anos).
* ❌ Bloqueio de entrada para indivíduos menores de idade.
* 📄 Armazenamento dos acessos autorizados no documento `log_acessos.txt`.

---

## 💬 Retorno de Mensagens

* **Para maiores de 18 anos:**
  > Entrada autorizada, [Nome]!

* **Para menores de 18 anos:**
  > Entrada recusada, [Nome]!

---

## 🛠️ Tecnologias Empregadas

* **PHP**
* **HTML**
* **Leitura e escrita de arquivos de texto (`.txt`)**

---

## 📁 Organização dos Arquivos

```text
.
├── 5a_desafio1.php
└── log_acessos.txt
