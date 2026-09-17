# Identidade visual da Tech Date (antes Calendário Tech) — status atual

## Documentos atuais (Tech Date · set/2026)

1. **Brand Book** — https://claude.ai/artifact/Dch3Mv4daHo8a2Cw4Tgrgz
   Capa; sobre o projeto (antes/depois do nome); propósito e missão; visão e valores; posicionamento e personalidade; tom de voz (como falamos / não falamos, palavras, volume por canal); logo (3 propostas de wordmark, versões por fundo, área de proteção, tamanho mínimo, "não faça"); paleta com contrastes; tipografia com hierarquia e escala; apresentação do ícone Grade Viva (anatomia, construção, tamanhos); sistema visual (kit de elementos, anatomia de post, duas linguagens + sugestão de unificação, teste de reconhecimento); 8 posts + carrossel de 5 cards + post de marca, todos com legenda pronta; 8 stories em celular; destaques; simulação de perfil com feed 3×3; embaixadores (credencial, selo, moldura de foto, assinatura de e-mail, regras); parceiros (cobranding, faixa de apoio, certo/errado); eventos (crachás participante/embaixadora/staff frente e verso, cordão, backdrop step and repeat, roll-up, sinalização); merch (4 camisetas, 10 bottons, adesivos, ecobag, caderno, squeeze, chaveiro, cartão de visita).

2. **Icon & Visual System** — https://claude.ai/artifact/QwZDmySuKr8mL7z7Jo6XYW
   Banner de decisão final (Grade Viva); 8 direções desenhadas (A Grade Viva escolhida; B–H como histórico); matriz 6 combinações de cor × 6 estilos (contorno, preenchido, reduzido, circular, quadrado, tamanho pequeno); família de 12 ícones de categoria com regras de construção (grade 24 px, traço 1,8); combinações de cor aprovadas e proibidas; biblioteca de 16 elementos com códigos (L1–L4 linhas, G1–G4 grades, F1–F4 formas, S1–S4 setas) e aplicações em post, story, camiseta e crachá.

3. **Versão site para GitHub Pages** (entregue como arquivos no chat, set/2026) — `index.html` (Brand Book), `icon-system.html` (Icon System) e `README.md` com passo a passo de publicação. Mesmo conteúdo dos artifacts, com: documento HTML completo e código comentado por seções; links relativos entre as duas páginas; menu de seções (gaveta no celular/tablet, barra lateral fixa a partir de 1440 px, seção ativa marcada); layout testado de 320 a 1920 px sem rolagem horizontal; botões e áreas de copiar (HEX/RGB/CMYK e variável de cada cor, paleta em CSS/SCSS/Tailwind v4/JSON, CSS e link de cada fonte, linhas da escala tipográfica, legendas e textos de posts/stories, bio, assinatura, exemplos de tom de voz, frases de merch, SVG do símbolo e de cada versão da matriz, SVG dos ícones e sprite, SVG/CSS dos elementos, link de cada seção). Tokens copiados usam os nomes `--td-azul`, `--td-azul-profundo`, `--td-ink`, `--td-sand`, `--td-branco`, `--td-fonte-titulo`, `--td-fonte-texto`, `--td-fonte-dados`. Os artifacts acima não receberam essas melhorias de site.

## Decisões fixas
- **Nome:** Tech Date (antes Calendário Tech). "Date" = data e encontro.
- **Paleta:** #2E4BFF azul (ação), #0305C6 azul profundo, #0B0B0F ink, #F7F3EA sand (fundo padrão), #FFFFFF branco.
- **Tipografia:** League Spartan (títulos), Inter (corpo), JetBrains Mono (tags e dados).
- **Símbolo Grade Viva:** moldura arredondada em contorno na cor de contraste, 2 pinos, 3 células azuis a 40%, linha fina até o nó, nó #2E4BFF sempre 100%. Exceção documentada: no estilo "preenchido" as células viram recortes na cor do fundo. Nunca aplicar o símbolo sobre #2E4BFF (o nó some) — usar Azul profundo.
- **Linguagem visual:** social (fundo liso, selo circular azul/ink no topo, botão circular de seta, rabisco azul no canto) é a base de tudo; a técnica (grade de pontos, cantos de câmera, texto de terminal) entra como tempero — no máximo um elemento por peça no digital, mais liberdade em palco, backdrop, cordão, camisetas e bottons.

## Em aberto
- **Wordmark:** 3 propostas — A "&lt;tech&gt;" pequeno em cima de "d[ícone]te" (recomendada e aplicada nos documentos), B "tech d[ícone]te" em linha única, C "tech / d[ícone]te" empilhado. Aguardando escolha do usuário; trocar o logo não afeta cores, ícone e sistema.
- **@ do Instagram:** @techdate, @techdates, @tech.date e @tech_dates já estão ocupados. Os documentos usam @techdatebr apenas como ilustração.

## Exemplos fictícios usados
Parceiros NEXA, Órbita e Baobá Labs; embaixadora Ana Ferreira (Salvador, BA); participantes Marina Costa, Rafael Lima (staff), Bruno Sato (palestrante); eventos Encontro Nordeste Dev (17/10, Fortaleza), Hackday Baía (03/10, Salvador), IA na Prática (08/10, Recife); comunidade Código Sertão (Petrolina/Juazeiro); cupom TECHDATE30.

## Histórico — documentos do Calendário Tech (mantidos, não atualizados)
- Brand Book antigo: https://claude.ai/artifact/GDDLqULGLoiLNKwnTJiaKA
- Icon & Visual System antigo: https://claude.ai/artifact/9QnqgTE6Nqy3RUqbiLpyw1

## Próximos passos possíveis
- Escolher o wordmark (A, B ou C) e gerar os arquivos finais do logo (SVG/PNG) nas 4 versões de fundo.
- Definir o @ oficial e substituir @techdatebr nas peças.
- Transformar posts, stories e crachás em modelos editáveis (Canva/Figma).