# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Contexto do projeto

Repositório pessoal de **Newton Rhomel Beck Angelini**, piloto amador de kart em Minas Gerais. Nas folhas de tempo de volta, o nome aparece como **NEWTON RHOMEL**. Contém registros da sua trajetória no esporte: sessões de treino, etapas de campeonato, controle financeiro e metodologia de evolução.

Todo o conteúdo é em **português do Brasil**.

Claude atua também como parceiro de brainstorm sobre karting — estratégia de corrida, análise de desempenho, técnica de pilotagem, setup de kart e evolução como piloto.

## Campeonatos e clubes

- **Tabajara**: clube de treinos no formato tomada de tempo. Acontece em Betim e no RBC. É o principal ambiente de treino.
- **Netkart**: campeonato amador regional de disputa de posição. Dividido entre os kartódromos de Betim e RBC. Objetivo competitivo principal.

## Kartódromos

- **Betim**: kartódromo principal, onde acontece a maioria dos treinos.
- **RBC**: kartódromo secundário, mas importante pois o Netkart divide etapas entre os dois.

## Estrutura dos documentos

- `tabajara/` — relatórios de sessões do clube Tabajara (um arquivo por sessão)
- `netkart/` — relatórios de cada etapa do campeonato Netkart
- `framework-treino.md` — metodologia de treino, objetivos e evolução como piloto
- `financeiro.md` — controle único de todos os gastos com karting

## Convenções de nomenclatura

Cada sessão ou etapa é uma **pasta nomeada por data** (`YYYY-MM-DD`). Dentro da pasta:

- `resultado.pdf` — folha de tempos original
- `relatorio.md` — análise e notas da sessão

Quando houver mais de uma sessão no mesmo dia, adicionar sufixo com o kartódromo: `2025-03-01-betim/`, `2025-03-01-rbc/`.
