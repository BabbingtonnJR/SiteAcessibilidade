# Site de Acessibilidade

Site educativo sobre acessibilidade digital na Web, com conteúdo 
baseado no material eMAG Conteudista (Enap - Escola Nacional de Administração 
Pública) e nas diretrizes internacionais WCAG 2.0. Além de documentar boas 
práticas, o site implementa funcionalidades reais de acessibilidade.

## Funcionalidades

- **Leitura em voz alta**: usa a Web Speech API do navegador 
  (`SpeechSynthesisUtterance`) para ler o conteúdo da página em voz alta, 
  ativada/desativada por botões flutuantes
- **Ajuste de tamanho de fonte**: três níveis (pequeno/médio/grande), com a 
  preferência salva no `localStorage` e recarregada automaticamente
- **Alto contraste**: alternância de tema, também persistida entre sessões
- **Navegação por teclado com indicação visual**: botões com contorno (`outline`) 
  visível ao receber foco, para quem navega sem mouse
- **Para Desenvolvedores**: guia de boas práticas, HTML semântico, textos 
  alternativos, navegação por teclado, contraste, ARIA, e ferramentas de teste 
  (WAVE, Lighthouse, axe, Color Contrast Analyzer)
- **Legislação**: panorama da legislação brasileira sobre acessibilidade digital 
  (Lei Brasileira de Inclusão nº 13.146/2015, Decreto nº 5.296/2004, NBR 9050) e 
  a relação com as diretrizes WCAG
- **Artigos**: disponibiliza para download os módulos 1 e 2 do eMAG Conteudista (Enap)

## Tecnologias

HTML, CSS, JavaScript (Web Speech API, localStorage)

## Referências utilizadas

- eMAG (Modelo de Acessibilidade em Governo Eletrônico) — módulos 1 e 2, Enap
- WCAG 2.0 (Web Content Accessibility Guidelines)
- Lei Brasileira de Inclusão (LBI) — Lei nº 13.146/2015
- Decreto nº 5.296/2004
