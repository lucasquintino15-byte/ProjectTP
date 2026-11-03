# ProjectTP

Tetra Pak — Supply Chain CoE (AMER) Wave 2 · KPMG

## Arquivos

- `tetrapak-process-atlas.html` — **Tetra Pak Process Atlas**, a versão oficial e única do painel. Seis capítulos, com uma linha de páginas em cada um:
  - **Início**: objetivo e como ler o painel.
  - **Cadeia e CoE**: como a cadeia funciona, o CoE Design da Wave 1, o que ainda não foi visto e como atuar.
  - **Mapa interativo**: fluxo das três áreas (Planning Hub, SCCT, Repro Design) com atividades, dores, paliativos, melhor cenário, simulações e o modo Percorrer.
  - **Dores**: as 85 dores em tabela, com filtros e busca.
  - **Paliativos × CoE**: o que já está na Wave 1, o que entra no CoE e em qual camada, com insights.
  - **Plano de ação**: fila de seis frentes do Planning Hub (eliminar → simplificar → padronizar → automatizar).
- `Plano_de_Acao_Planning_Hub_TetraPak.docx` — documento Word do plano de ação.

## Como usar

- Para ver: baixe o HTML e abra no navegador (Chrome/Edge), de preferência no computador. O arquivo funciona sozinho, sem internet.
- Para editar: abra num editor de texto (ex.: VS Code).
  - Conteúdo do mapa, das dores e dos paliativos: blocos `<script>` no fim do arquivo (`SECTORS`, `SIMS`, `COE`, `PLAN`).
  - Capítulos Início e Cadeia e CoE: HTML nas seções `<section class="chap" id="inicio">` e `id="cadeia"`.
  - Visual: bloco `<style>` do início. Fonte KPMG só em títulos e destaques; o restante usa Arial. Segue o tema claro ou escuro do sistema.
