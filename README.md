# Prévia do bloco 9 "Live final 09/11" (BF26)

Prévia estática, **com dados fictícios**, do bloco novo da página
`grupoparticipa.app.br/marketing/projetos/bf26` (`?bloco=live-final`). Serve só para o Victor aprovar a estrutura
antes de o bloco entrar no sistema (repo `sistema-grupo-participa-v2`, via `ExtrasDoProjeto.cartoes`).

- O que tem: grade com os 8 blocos atuais (só o lugar deles) e o bloco 9; detalhe embaixo com 4 abas (Visão geral,
  Tráfego, Disparos, Indicação); cards que abrem modal com evolução por dia e por hora, comparação de até 4 métricas
  e recortes; ranking por código com modal do código.
- "Aguardando fonte": o que não está no banco hoje (dono do código, pontos, validade, autoindicação, matrículas,
  envios e custo dos disparos).
- Publicação: GitHub Pages pelo workflow `.github/workflows/pages.yml` a cada push na `main`. `noindex` na página e
  `robots.txt` bloqueando tudo.
- Situação (07/11/2026): publicada em https://victorhugo-alves.github.io/previa-bf26-live-final/ e testada no Chrome (desktop e janela estreita, sem erro no console). Aguarda o ok do Victor. Nada no sistema foi alterado.
- Ajustes depois do teste: gráficos de colunas e barras com largura máxima (texto não estoura no painel inteiro), rótulo de verba sem corte, alcance e frequência acumulados no modal (batem com o card), eixo inteiro em contagem.
- Plano completo: `2° cérebro/Projetos/marketing-bf26/live-encerramento/2026-11-07-plano-card-live-final.md`.
