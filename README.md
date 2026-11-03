# ProjectTP

Tetra Pak — Supply Chain CoE (AMER) Wave 2 · KPMG

## Arquivos

- `tetrapak-process-atlas.html` — **Tetra Pak Process Atlas**: mapa interativo dos processos do CoE (Planning Hub → SCCT → Repro Design). Quatro abas: Mapa de processos, Painel de dores (tabela com filtros), Paliativos × CoE (o que já está na Wave 1, o que entra e em qual camada) e Plano de ação do Planning Hub.
- `painel-coe-tetrapak.html` — **Painel CoE Tetra Pak**: o mesmo conteúdo em capítulos e páginas, no template do painel COE (Início, Cadeia e CoE, Dores, Paliativos × CoE, Plano de ação).
- `Plano_de_Acao_Planning_Hub_TetraPak.docx` — documento Word do plano de ação: seis frentes no formato eliminar → simplificar → padronizar → automatizar.

## Como usar

- Para ver: baixe o HTML e abra no navegador (Chrome/Edge), de preferência no computador. Os dois HTMLs funcionam sozinhos, sem internet.
- Para editar: abra num editor de texto (ex.: VS Code). No Atlas, o conteúdo fica nos blocos `<script>` no fim do arquivo (`SECTORS`, `PLAN`, `COE`); o visual fica no `<style>` do início. No painel, cada capítulo é uma `<section class="panel">` e cada página um `<article class="page">`.
- Fonte KPMG só em títulos e destaques; o restante usa Arial. Os dois HTMLs seguem o tema claro ou escuro do sistema.
