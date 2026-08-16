# Dataset de Exercícios Físicos Adaptado (PT-BR)

Uma base de dados estruturada em JSON com mais de **800 exercícios físicos** traduzidos e adaptados para o português brasileiro, focada em entregar termos e nomenclaturas naturais do dia a dia das academias no Brasil.

---

## 🎯 Por que esta versão?

Muitas traduções automáticas ou literais de datasets em inglês mantêm expressões que soam estranhas para praticantes e treinadores brasileiros (como *"Banda"* em vez de *"Faixa/Elástico"*, ou traduções incorretas de termos técnicos consagrados como *"Rollout"*). 

Esta versão passou por uma revisão minuciosa de **revisão e localização terminológica** para garantir que a busca e a exibição de treinos em aplicativos e sistemas fitness ofereçam uma experiência intuitiva e profissional.

---

## 💡 Principais Melhorias

* **Linguagem Natural de Academia:** Ajuste dos nomes dos exercícios para os termos realmente falados nas academias brasileiras.
* **Vocabulário Técnico Adequado:** Preservação de termos em inglês amplamente adotados no mercado fitness brasileiro (ex: *Rollout*, *Stiff*, *Pulloff*).
* **Pronto para Aplicativos:** Estrutura otimizada para inclusão direta em bancos de dados (PostgreSQL, MongoDB, etc.) e consumo via APIs REST / GraphQL.

---

## 📁 Estrutura dos Arquivos

### 1. `exercises_pt-BR.json`
Ideal para buscas rápidas e telas simplificadas no app. Contém apenas os campos básicos:
* `id`: Identificador único do exercício.
* `name`: Nome do exercício adaptado para PT-BR.
* `instructions`: Instruções de execução em português.

---

## 🖼️ Mídia e Imagens

Os caminhos das imagens (`images`) no JSON foram preservados como referência para facilitar o vínculo com seus próprios assets. No entanto, as imagens em si não estão inclusas neste repositório por razões de direitos autorais.

---

## 📍 Créditos e Origem

Este projeto é uma reestruturação e revisão terminológica de iniciativas de código aberto:

* **Revisão e Adaptação Terminológica (PT-BR):** Este repositório
* **Tradução Inicial (PT-BR):** [joao-gugel/exercicios-bd-ptbr](https://github.com/joao-gugel/exercicios-bd-ptbr)
* **Dataset Original (Inglês):** [yuhonas/free-exercise-db](https://github.com/yuhonas/free-exercise-db)