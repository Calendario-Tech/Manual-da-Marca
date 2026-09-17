---
version: alpha
name: Tech Date
description: "Sistema de design da Tech Date, a agenda do ecossistema tech brasileiro. Uma interface clara e comunitária: fundo Sand (#F7F3EA) no lugar do branco puro, Azul #2E4BFF como única cor de ação, títulos em League Spartan com espaçamento negativo, corpo em Inter e dados em JetBrains Mono. A assinatura é a Grade Viva — células azuis a 40% e um nó azul sólido que marca o que está acontecendo agora —, repetida em selos circulares de categoria, no botão redondo de seta e num rabisco azul feito à mão no canto das peças."

colors:
  primary: "#2E4BFF"
  primary-deep: "#0305C6"
  ink: "#0B0B0F"
  sand: "#F7F3EA"
  white: "#FFFFFF"
  primary-40: "#2E4BFF66"
  primary-tint: "#E5E4EC"
  primary-tint-white: "#ECEFFF"
  primary-40-white: "#ABB7FF"
  ink-muted: "#0B0B0FB8"
  ink-subtle: "#0B0B0F9E"
  hairline: "#0B0B0F24"
  hairline-soft: "#0B0B0F12"
  white-muted: "#FFFFFFBD"
  white-subtle: "#FFFFFFB3"
  hairline-on-dark: "#FFFFFF26"
  ink-raised: "#1F1F22"
  deep-raised: "#1719CB"

typography:
  display-hero:
    fontFamily: League Spartan
    fontSize: 132px
    fontWeight: 800
    lineHeight: 0.86
    letterSpacing: -0.04em
  display-statement:
    fontFamily: League Spartan
    fontSize: 70px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: -0.03em
  headline-display:
    fontFamily: League Spartan
    fontSize: 68px
    fontWeight: 700
    lineHeight: 0.96
    letterSpacing: -0.028em
  headline-lg:
    fontFamily: League Spartan
    fontSize: 54px
    fontWeight: 700
    lineHeight: 1.02
    letterSpacing: -0.025em
  headline-md:
    fontFamily: League Spartan
    fontSize: 40px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: League Spartan
    fontSize: 30px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.015em
  title-md:
    fontFamily: League Spartan
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.015em
  title-sm:
    fontFamily: League Spartan
    fontSize: 19px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.01em
  date-display:
    fontFamily: League Spartan
    fontSize: 48px
    fontWeight: 800
    lineHeight: 0.8
    letterSpacing: -0.04em
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.55
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.625
  body-md-strong:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.625
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  caption:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.54
  button-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.33
    letterSpacing: 0.08em
  label-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: 0.06em
  data-mono:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.5
  social-cover:
    fontFamily: League Spartan
    fontSize: 160px
    fontWeight: 800
    lineHeight: 136px
    letterSpacing: -0.03em
  social-title:
    fontFamily: League Spartan
    fontSize: 96px
    fontWeight: 700
    lineHeight: 90px
    letterSpacing: -0.025em
  social-number:
    fontFamily: League Spartan
    fontSize: 300px
    fontWeight: 800
    lineHeight: 0.74
    letterSpacing: -0.05em
  social-body:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: 400
    lineHeight: 1.42
  social-tag:
    fontFamily: JetBrains Mono
    fontSize: 32px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0.08em
  story-title:
    fontFamily: League Spartan
    fontSize: 120px
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: -0.028em

rounded:
  none: 0px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 20px
  xxl: 24px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  xxxl: 72px
  section: 128px
  section-mobile: 64px
  gutter: 48px
  gutter-mobile: 16px
  container: 1200px
  container-wide: 1320px
  topbar: 60px
  sidebar: 284px
  social-margin: 80px
  story-safe-zone: 250px

components:
  topbar:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.ink}"
    typography: "{typography.button-md}"
    height: 60px
    padding: 0 28px
  menu-drawer:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.ink}"
    width: 360px
  menu-item-active:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 7px 10px
  segmented-control-active:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 8px 13px
  section-sand:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.ink}"
    padding: 128px 48px
  section-white:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    padding: 128px 48px
  section-ink:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    padding: 128px 48px
  section-deep:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.white}"
    padding: 128px 48px
  eyebrow:
    textColor: "{colors.primary}"
    typography: "{typography.label-mono}"
  eyebrow-number:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    typography: "{typography.label-mono}"
    rounded: "{rounded.pill}"
    height: 22px
    padding: 0 7px
  text-body:
    textColor: "{colors.ink-muted}"
    typography: "{typography.body-md}"
  text-caption:
    textColor: "{colors.ink-subtle}"
    typography: "{typography.label-mono}"
  text-body-on-dark:
    textColor: "{colors.white-muted}"
    typography: "{typography.body-md}"
  text-caption-on-dark:
    textColor: "{colors.white-subtle}"
    typography: "{typography.label-mono}"
  divider:
    backgroundColor: "{colors.hairline}"
    height: 1px
  divider-soft:
    backgroundColor: "{colors.hairline-soft}"
    height: 1px
  divider-on-dark:
    backgroundColor: "{colors.hairline-on-dark}"
    height: 1px
  button-arrow:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 52px
  button-arrow-pressed:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 52px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 14px 22px
    height: 48px
  button-primary-pressed:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.white}"
    rounded: "{rounded.pill}"
  button-secondary:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 12px 18px
    height: 44px
  button-on-dark:
    backgroundColor: "{colors.ink-raised}"
    textColor: "{colors.white}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 12px 18px
    height: 44px
  link-sticker:
    backgroundColor: "{colors.white}"
    textColor: "{colors.primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 6px 6px 6px 18px
    height: 48px
  seal-category:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 48px
  seal-category-ink:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 48px
  seal-category-light:
    backgroundColor: "{colors.white}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    size: 48px
  tag:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.ink}"
    typography: "{typography.label-mono-sm}"
    rounded: "{rounded.pill}"
    padding: 7px 11px
  tag-filled:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    typography: "{typography.label-mono-sm}"
    rounded: "{rounded.pill}"
    padding: 7px 11px
  tag-ink:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    typography: "{typography.label-mono-sm}"
    rounded: "{rounded.pill}"
    padding: 7px 11px
  definition-callout:
    backgroundColor: "{colors.primary-tint}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 13px 16px 13px 48px
  card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xxl}"
    padding: 24px
  card-sand:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xxl}"
    padding: 24px
  card-on-ink:
    backgroundColor: "{colors.ink-raised}"
    textColor: "{colors.white}"
    rounded: "{rounded.xl}"
    padding: 22px
  card-on-deep:
    backgroundColor: "{colors.deep-raised}"
    textColor: "{colors.white}"
    rounded: "{rounded.xl}"
    padding: 22px
  event-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.xxl}"
    padding: 24px
  date-block:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.ink}"
    typography: "{typography.date-display}"
    rounded: "{rounded.lg}"
    size: 72px
  date-block-today:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    typography: "{typography.date-display}"
    rounded: "{rounded.full}"
    size: 72px
  calendar-day:
    backgroundColor: "{colors.primary-tint-white}"
    textColor: "{colors.ink}"
    typography: "{typography.data-mono}"
    rounded: "{rounded.sm}"
    size: 40px
  calendar-day-event:
    backgroundColor: "{colors.primary-40-white}"
    textColor: "{colors.ink}"
    typography: "{typography.data-mono}"
    rounded: "{rounded.sm}"
    size: 40px
  calendar-day-today:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    typography: "{typography.data-mono}"
    rounded: "{rounded.full}"
    size: 40px
  grade-cell:
    backgroundColor: "{colors.primary-40}"
    rounded: "{rounded.xs}"
    size: 18px
  grade-node:
    backgroundColor: "{colors.primary}"
    rounded: "{rounded.full}"
    size: 18px
  symbol-grade-viva:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.primary}"
    size: 52px
  symbol-grade-viva-on-dark:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    size: 52px
  wordmark:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.primary}"
    width: 96px
  wordmark-on-deep:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.white}"
    width: 96px
  squiggle:
    textColor: "{colors.primary}"
  text-input:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: 12px 16px
    height: 48px
  text-input-focus:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
  toast:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 10px 18px 10px 10px
  post-feed:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.ink}"
    typography: "{typography.social-title}"
    width: 1080px
    height: 1350px
    padding: 80px
  post-feed-white:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.social-title}"
  post-feed-ink:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    typography: "{typography.social-title}"
  post-feed-deep:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.white}"
    typography: "{typography.social-title}"
  story:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.ink}"
    typography: "{typography.story-title}"
    width: 1080px
    height: 1920px
    padding: 250px 80px
  story-sticker:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.social-body}"
    rounded: 54px
    padding: 50px
  highlight-cover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 660px
  highlight-cover-ink:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    size: 660px
  highlight-cover-light:
    backgroundColor: "{colors.white}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    size: 660px
  badge-participant:
    backgroundColor: "{colors.sand}"
    textColor: "{colors.ink}"
  badge-ambassador:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.white}"
  badge-staff:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
---

# Tech Date · DESIGN.md

Sistema de design da Tech Date para interfaces (site, plataforma, e-mail), redes sociais e materiais impressos. Os tokens no topo do arquivo são os valores oficiais; o texto explica quando e como usar cada um. Os títulos das seções principais seguem a especificação [DESIGN.md](https://github.com/google-labs-code/design.md) em inglês, para que ferramentas e agentes de IA encontrem cada parte; o conteúdo está em português.

> **Fontes:** Brand Book Tech Date v1.0 e Icon & Visual System v1.0 (setembro de 2026) e o site do manual (`index.html` e `icon-system.html`). Onde o manual ainda não cobre algo — formulários, calendário da plataforma, cartão de evento —, a proposta está marcada como **derivada** e segue as mesmas regras.

## Overview

A Tech Date é a agenda do ecossistema tech brasileiro: eventos, cursos, vagas, comunidades e hackathons, conferidos e reunidos num só lugar. O design traduz isso numa ideia só, **a grade viva**: uma agenda organizada (células azuis a 40%) com algo sempre acontecendo agora (um nó azul sólido). Essa ideia está no símbolo, nos calendários, nos marcadores de progresso e até na estampa das camisetas.

A interface é clara, comunitária e direta. O fundo padrão é **Sand** (`{colors.sand}`), um creme quente no lugar do branco puro. O **Azul** (`{colors.primary}`) é a única cor de ação. Títulos em **League Spartan**, pesados e com espaçamento negativo, dão presença; **Inter** carrega a leitura; **JetBrains Mono** marca tudo o que é dado — datas, horários, locais, categorias, preços — com um sotaque pontual de código.

Duas linguagens convivem no sistema:

- **Social (a base de tudo):** fundos lisos (Sand, Branco, Ink ou Azul profundo), um selo circular de categoria no topo, um botão redondo de seta como chamada para ação e um rabisco azul feito à mão num canto. Vale para interface, posts, stories, destaques, feed e crachás.
- **Técnica (o tempero):** grade de pontos, cantos de câmera (viewfinder), texto de terminal (`$ tech-date --agenda outubro`) e numeração 01, 02, 03 quando existe ordem de verdade. No máximo **um** desses elementos por peça digital; mais liberdade no mundo físico — palco, backdrop, cordão, camisetas e bottons —, onde a marca precisa chamar atenção de longe.

**Personalidade:** curiosa, parceira, direta, bem-humorada na medida e confiável. Se a Tech Date fosse gente, seria aquela amiga dev que sempre sabe o que está rolando na cidade — e te chama para ir junto. A interface nunca é fria nem elitista: todo termo técnico vem acompanhado de uma explicação curta.

**Teste de reconhecimento:** tampando o logo e o @, a peça ainda precisa ser da Tech Date — creme e azul, selo redondo, título em League Spartan, dado em mono, seta azul e rabisco no canto.

**Características principais:**

- Paleta fechada de **cinco cores**. Variações só por opacidade, nunca por cores novas.
- `{colors.primary}` é o sinal único de ação: botões, links, destaques, o nó do símbolo e os rabiscos.
- Seções em faixas de cor inteira (Sand → Branco → Ink → Azul profundo). A troca de fundo é o divisor; não há bordas entre seções.
- Três formas-assinatura: **círculo** (categoria, ação, "agora"), **pílula** (tags e botões com texto) e **quadrado de cantos bem arredondados** (moldura do símbolo, células e dias do calendário).
- Tipografia em três papéis fixos. Títulos em frase normal; caixa alta só nas tags em mono.
- Quase nenhuma sombra. Profundidade vem da troca de fundo; sombra só em objetos que "flutuam" (crachá, celular, figurinha de story, aviso).

## Colors

### Paleta oficial

- **Azul** (`{colors.primary}` — #2E4BFF): a cor de ação. Botões, links, chamadas para ação, o nó da Grade Viva, rabiscos e selos de categoria. RGB 46 75 255 · CMYK aproximado 82 71 0 0. É mais vibrante do que a impressão comum alcança: peça prova de cor à gráfica.
- **Azul profundo** (`{colors.primary-deep}` — #0305C6): dá peso sem sair da família azul. Fundos de impacto (seções, posts, stories, crachá de embaixador) e estado pressionado dos botões azuis. RGB 3 5 198 · CMYK 98 97 0 22.
- **Ink** (`{colors.ink}` — #0B0B0F): texto principal e fundo escuro. Substitui o preto puro em tudo. RGB 11 11 15 · CMYK 27 27 0 94.
- **Sand** (`{colors.sand}` — #F7F3EA): o fundo padrão da marca, no lugar do branco puro. RGB 247 243 234 · CMYK 0 2 5 3.
- **Branco** (`{colors.white}` — #FFFFFF): respiro e contraste, com moderação — cartões, figurinhas de story, adesivos e texto sobre azul.

**Proporção numa peça típica:** Sand 45% · Ink 25% · Azul 15% · Azul profundo 10% · Branco 5%.

### Derivados por opacidade (não são cores novas)

Toda variação sai de uma das cinco cores com transparência. Os valores sólidos abaixo são o resultado sobre o fundo indicado, para usar em ferramentas que não trabalham com opacidade.

| Token | Valor | Origem | Uso |
|---|---|---|---|
| `{colors.primary-40}` | #2E4BFF66 | Azul 40% | Células da Grade Viva e dias com evento. Continua azul até sobre fundo azul (contraste tonal). |
| `{colors.primary-tint}` | #E5E4EC | Azul 9% sobre Sand | Caixa "o que é isso?", fundos suaves de destaque |
| `{colors.primary-tint-white}` | #ECEFFF | Azul 9% sobre Branco | Dias do calendário sem evento |
| `{colors.primary-40-white}` | #ABB7FF | Azul 40% sobre Branco | Dias com evento em calendários de interface |
| `{colors.ink-muted}` | #0B0B0FB8 | Ink 72% | Texto de corpo e parágrafos |
| `{colors.ink-subtle}` | #0B0B0F9E | Ink 62% | Legendas, metadados e rótulos |
| `{colors.hairline}` | #0B0B0F24 | Ink 14% | Bordas de botões secundários, tags e campos |
| `{colors.hairline-soft}` | #0B0B0F12 | Ink 7% | Anel de cartões brancos, divisórias leves, trilho do seletor |
| `{colors.white-muted}` | #FFFFFFBD | Branco 74% | Corpo sobre Ink e Azul profundo |
| `{colors.white-subtle}` | #FFFFFFB3 | Branco 70% | Legendas sobre fundos escuros |
| `{colors.hairline-on-dark}` | #FFFFFF26 | Branco 15% | Bordas e divisórias sobre escuro |
| `{colors.ink-raised}` | #1F1F22 | Branco 8% sobre Ink | Painéis e botões dentro de seções Ink |
| `{colors.deep-raised}` | #1719CB | Branco 8% sobre Azul profundo | Painéis dentro de seções Azul profundo |

> **Ajuste de acessibilidade.** O manual publicado usa Ink 54% e Branco 55% nas legendas. Em texto pequeno isso fica abaixo do mínimo WCAG AA (4,1:1 sobre Sand e 3,9:1 sobre Azul profundo). Este documento sobe para **Ink 62%** (5,4:1 sobre Sand) e **Branco 70%** (5,8:1 sobre Azul profundo).

### Contraste

**Contraste** é a diferença de claridade entre texto e fundo. O mínimo para texto comum é 4,5:1; títulos a partir de 24px aceitam 3:1.

| Texto sobre fundo | Razão | Uso |
|---|---|---|
| Ink sobre Sand | 17,7:1 | Combinação principal de leitura |
| Ink sobre Branco | 19,6:1 | Cartões e campos |
| Azul sobre Branco | 5,9:1 | Links e destaques curtos |
| Azul sobre Sand | 5,3:1 | Palavra em destaque no título |
| Branco sobre Azul | 5,9:1 | Botões e selos |
| Branco sobre Azul profundo | 11,4:1 | Posts, stories e seções de impacto |
| Sand sobre Ink | 17,7:1 | Fundos escuros |
| Azul sobre Ink | 3,3:1 | **Só** títulos a partir de 24px |
| Azul sobre Azul profundo | 1,9:1 | **Nunca** para texto; aceito apenas no nó do símbolo |

### Gradientes e texturas

**Não existe gradiente na marca.** A única textura é a **grade de pontos** da linguagem técnica: pontos brancos a 16% com 1px de raio a cada 22px, usada só sobre Ink ou Azul profundo e nunca em posts.

## Typography

### Famílias

- **League Spartan** — títulos, números grandes e logo. Pesos 600, 700 e 800. Traço geométrico e forte, que segura a leitura de longe.
- **Inter** — corpo, interface, legendas e botões. Pesos 400, 500 e 600. Neutra e muito legível em tela pequena.
- **JetBrains Mono** — tags, categorias, datas, horários, locais, valores (HEX, CSS) e texto de terminal. Pesos 400, 500 e 600. O toque pontual de código; **nunca** para texto longo.

Pilhas com alternativas, para o caso de a fonte não carregar:

```css
--td-fonte-titulo: "League Spartan", "Futura", "Avenir Next", sans-serif;
--td-fonte-texto: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
--td-fonte-dados: "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace;
```

As três estão no Google Fonts:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@600;700;800&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;500;600&display=swap">
```

### Hierarquia de interface

Valores de desktop. Os títulos grandes diminuem com a tela (ver Responsive Behavior).

| Token | Fonte | Tamanho | Peso | Entrelinha | Espaçamento | Uso |
|---|---|---|---|---|---|---|
| `{typography.display-hero}` | League Spartan | 132px | 800 | 0.86 | -0.04em | Capa, título de campanha |
| `{typography.display-statement}` | League Spartan | 70px | 700 | 1.0 | -0.03em | Manifesto, propósito, frase de impacto |
| `{typography.headline-display}` | League Spartan | 68px | 700 | 0.96 | -0.028em | Título de seção |
| `{typography.headline-lg}` | League Spartan | 54px | 700 | 1.02 | -0.025em | Visão, citações grandes |
| `{typography.headline-md}` | League Spartan | 40px | 700 | 1.0 | -0.015em | Título dentro de seção, cabeçalho de página interna |
| `{typography.headline-sm}` | League Spartan | 30px | 700 | 1.05 | -0.015em | Subtítulo, título de bloco |
| `{typography.title-md}` | League Spartan | 24px | 700 | 1.05 | -0.015em | Título de cartão e de evento |
| `{typography.title-sm}` | League Spartan | 19px | 700 | 1.1 | -0.01em | Título de cartão pequeno, item de lista |
| `{typography.date-display}` | League Spartan | 48px | 800 | 0.8 | -0.04em | Dia do mês em blocos de data |
| `{typography.body-lg}` | Inter | 20px | 400 | 1.55 | 0 | Texto de abertura (lead) |
| `{typography.body-md}` | Inter | 16px | 400 | 1.625 (26px) | 0 | Parágrafos |
| `{typography.body-md-strong}` | Inter | 16px | 600 | 1.625 | 0 | Ênfase no corpo |
| `{typography.body-sm}` | Inter | 14px | 400 | 1.5 | 0 | Descrições de cartão, textos de apoio |
| `{typography.caption}` | Inter | 13px | 500 | 1.54 (20px) | 0 | Legendas de imagem e créditos |
| `{typography.button-md}` | Inter | 14px | 600 | 1.0 | 0 | Botões, itens do seletor, aviso |
| `{typography.label-mono}` | JetBrains Mono | 12px | 500 | 1.33 (16px) | 0.08em | Rótulo de seção, tag de dados, metadados — caixa alta |
| `{typography.label-mono-sm}` | JetBrains Mono | 11px | 500 | 1.0 | 0.06em | Pílulas de tag — caixa alta |
| `{typography.data-mono}` | JetBrains Mono | 13px | 500 | 1.5 | 0 | Datas, horários, locais, valores e comandos |

### Escala das peças sociais (canvas de 1080px de largura)

| Token | Tamanho | Peso | Entrelinha | Uso |
|---|---|---|---|---|
| `{typography.social-cover}` | 160px | 800 | 136px | Capa de campanha, abertura de carrossel |
| `{typography.social-title}` | 96px | 700 | 90px | Título do post (até 3 linhas) |
| `{typography.social-number}` | 300px | 800 | 0.74 | Dia do mês quando a data é a notícia |
| `{typography.social-body}` | 40px | 400 | 1.42 | Texto de apoio e figurinhas |
| `{typography.social-tag}` | 32px | 600 | 1.25 | Tag em mono, caixa alta: categoria · formato · preço |
| `{typography.story-title}` | 120px | 700 | 0.95 | Título de story |

### Princípios

- **Espaçamento negativo nos títulos**, de -0.01em a -0.04em; quanto maior o título, mais apertado. Nunca em texto de corpo.
- **Títulos em frase normal** ("Encontro Nordeste Dev chega a Fortaleza"), nunca em CAIXA ALTA. Caixa alta só em JetBrains Mono, sempre com +6% a +8% de espaçamento.
- **Pesos com função:** 800 para capa, números grandes e logo; 700 para títulos; 600 para botões e ênfase; 400 para leitura. Nada de 300 (fino) na marca.
- **Corpo em 16/26px.** Texto de abertura de 17 a 20px. Largura de leitura de 62 a 64 caracteres; títulos com `text-wrap: balance`.
- **No máximo três tamanhos de texto por peça.**
- **Alinhado à esquerda.** Centralizado só em bottons e adesivos.
- **Dado logo abaixo do título**, em mono e separado por ponto médio: `SÁB · 17/10 · 09:00 · FORTALEZA, CE`.
- **Destaque dentro do título:** uma palavra ou expressão em Azul ("Oportunidades **da semana**"), sem mudar peso nem fonte.
- **Números alinhados:** use `font-variant-numeric: tabular-nums` em tabelas e colunas de valores em Inter.

## Layout

### Espaçamento

- **Unidade base:** 4px, com 8px como passo principal.
- **Tokens:** `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.xxxl}` 72px · `{spacing.section}` 128px.
- **Seções:** padding vertical `clamp(64px, 9vw, 128px)` — de `{spacing.section-mobile}` a `{spacing.section}`.
- **Margem lateral (gutter):** `clamp(16px, 4vw, 48px)` — de `{spacing.gutter-mobile}` a `{spacing.gutter}`. Nunca menos de 16px, em nenhuma tela.
- **Cabeçalho de seção até o conteúdo:** `clamp(40px, 6vw, 72px)`. **Entre blocos da mesma seção:** `clamp(48px, 7vw, 88px)`.
- **Grades de cartões:** gap `clamp(16px, 2.4vw, 28px)`; listas e fileiras densas, 12 a 16px.
- **Dentro de cartões:** 22 a 24px (`{spacing.lg}`); caixas de definição, 13×16px com 48px à esquerda para o ícone.

### Grade e contêiner

- **Contêiner:** `{spacing.container}` (1200px) centralizado; 1320px a partir de 1680px de tela e 1480px a partir de 2200px.
- **Colunas mais usadas:** posts, stories, combinações de cor e elementos gráficos em 4; propostas de logo e cartões de fonte em 3; paleta em 5; ícones de categoria em 6.
- **Estrutura de site/plataforma:** barra superior fixa de `{spacing.topbar}` (60px). A partir de 1440px, menu lateral fixo de `{spacing.sidebar}` (284px) à esquerda do conteúdo; abaixo disso, o menu vira gaveta.

### Ritmo das seções

Seções ocupam a largura toda e se alternam em fundos lisos: Sand → Branco → Ink (com grade de pontos, se for linguagem técnica) → Sand → Branco → Azul profundo. Sem borda e sem sombra entre elas — **a troca de cor é o divisor**. Evite duas seções escuras seguidas.

Cabeçalho padrão de seção: rótulo em mono com número (`{component.eyebrow}` + `{component.eyebrow-number}`), título (`{typography.headline-display}`), texto de abertura (`{typography.body-lg}` em `{colors.ink-muted}`) e, se houver termo técnico, uma `{component.definition-callout}`. Largura máxima do cabeçalho: 860px.

### Peças sociais e impressas

- **Post de feed:** 1080 × 1350px (4:5), margem de segurança `{spacing.social-margin}` (80px, 7,5% da largura).
- **Story:** 1080 × 1920px (9:16), com `{spacing.story-safe-zone}` (250px) livres em cima e embaixo para o nome do perfil e a caixa de resposta.
- **Capa de destaque:** arquivo de story com um círculo de 660px no centro.
- **Feed:** regra do tabuleiro — dois posts com o mesmo fundo nunca se encostam, nem na horizontal nem na vertical.

### Filosofia de espaço

Espaço generoso e confiante. Conteúdo relacionado fica agrupado em cartões com respiro interno; o vazio de uma peça social fica entre o título e a seta, nunca espremendo o texto contra a borda. A leitura é de cima para baixo: categoria → data → título → dados → ação.

## Elevation & Depth

A marca é **plana**. Hierarquia vem primeiro da troca de fundo, depois do anel fino e só por último da sombra.

| Nível | Tratamento | Uso |
|---|---|---|
| 0 · Plano | Sem sombra, sem borda | Seções, posts, stories, selos, botões, textos |
| 1 · Anel | `box-shadow: 0 0 0 1px` `{colors.hairline-soft}` | Cartões brancos sobre Sand, campos, peças de exemplo |
| 2 · Objeto | `0 30px 60px -40px rgba(11, 11, 15, 0.45)` · crachá `0 22px 44px -26px rgba(11, 11, 15, 0.5)` · celular `0 26px 50px -26px rgba(11, 11, 15, 0.55)` | Cartão em destaque, mockups de crachá, celular e objetos |
| 3 · Sobreposição | Barra superior: Sand a 92% + `backdrop-filter: blur(12px)` · gaveta: `-30px 0 60px -30px rgba(11, 11, 15, 0.45)` + véu `rgba(11, 11, 15, 0.42)` · aviso: `0 20px 40px -20px rgba(11, 11, 15, 0.6)` | Menu, gaveta, aviso "Copiado" |

**Filosofia da sombra.** Sombra é física, não decoração: só aparece em algo que existe como objeto (crachá, celular, figurinha de story) ou que flutua sobre a página (barra, gaveta, aviso). Botões, selos, tags e textos **nunca** têm sombra, e as artes de post também não — exceto as figurinhas brancas dos stories (`0 26px 76px rgba(11, 11, 15, 0.2)` no canvas de 1080px).

**Profundidade decorativa.** Na linguagem social, o rabisco azul dá movimento sem pesar. Na técnica, a grade de pontos e os cantos de câmera criam textura em fundos escuros. Nenhuma das duas usa gradiente.

## Shapes

### Escala de cantos

| Token | Valor | Uso |
|---|---|---|
| `{rounded.none}` | 0px | Seções de largura total, posts e stories exportados |
| `{rounded.xs}` | 4px | Células pequenas da grade viva, anel de foco |
| `{rounded.sm}` | 8px | Valores clicáveis (HEX), dias do calendário pequenos, cartão de visita |
| `{rounded.md}` | 12px | Campos de formulário, itens de menu |
| `{rounded.lg}` | 16px | Caixa de definição, blocos de data, tiles de exemplo |
| `{rounded.xl}` | 20px | Painéis sobre fundo escuro, cartões médios |
| `{rounded.xxl}` | 24px | Cartões e painéis principais |
| `{rounded.pill}` | 9999px | Tags, botões com texto, seletor, aviso, figurinha de link |
| `{rounded.full}` | 9999px | Círculos com largura = altura: selo, botão de seta, nó, dia de hoje, avatar |

### Linguagem de formas

- **Círculo = categoria, ação e agora.** Selo de categoria, botão de seta, nó da Grade Viva, dia de hoje, avatar de embaixador.
- **Pílula = informação e comando com texto.** Tags em mono, botões, seletor de documento, aviso, figurinha de link.
- **Quadrado de cantos bem arredondados (raio ≈ 24% do lado) = a agenda.** Moldura do símbolo, células e dias do calendário, ícone de app.
- **Linha fina feita à mão = o toque humano.** Rabisco sempre azul, sempre saindo de um canto.
- **Folha (forma de apoio):** quadrado com dois cantos opostos bem arredondados (`border-radius: 10px 46px 10px 46px` num quadrado de 92px). Aparece grande e clarinha (Azul a 7%) atrás do conteúdo, como em crachás.

### Construção do símbolo Grade Viva

Desenhado numa tela de 52 × 52 unidades:

- **Moldura:** quadrado 42 × 42 em (5, 7), raio 10, traço 2,6, sem preenchimento, na cor de contraste do fundo.
- **Pinos:** dois traços verticais em x = 17,3 e x = 34,7, de y = 5,6 a 10,6, espessura 3,6, pontas redondas — o calendário de parede, pendurado.
- **Células:** três quadrados 7,4 × 7,2 com raio 1,7 em (14, 20), (25,4, 20) e (14, 31,2), sempre em Azul a 40% — inclusive sobre fundo azul.
- **Linha:** de (28,6, 23,4) a (31,4, 29), traço 1,3, Azul. Sai da célula de cima e desce até o nó.
- **Nó vivo:** círculo de raio 6,2 em (32,5, 34,6), Azul 100%, sempre.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 52 52" width="52" height="52">
  <rect x="5" y="7" width="42" height="42" rx="10" fill="none" stroke="#2E4BFF" stroke-width="2.6"/>
  <path d="M17.3 5.6v5M34.7 5.6v5" stroke="#2E4BFF" stroke-width="3.6" stroke-linecap="round"/>
  <g fill="#2E4BFF" fill-opacity=".4">
    <rect x="14" y="20" width="7.4" height="7.2" rx="1.7"/>
    <rect x="25.4" y="20" width="7.4" height="7.2" rx="1.7"/>
    <rect x="14" y="31.2" width="7.4" height="7.2" rx="1.7"/>
  </g>
  <path d="M28.6 23.4 31.4 29" stroke="#2E4BFF" stroke-width="1.3" stroke-linecap="round"/>
  <circle cx="32.5" cy="34.6" r="6.2" fill="#2E4BFF"/>
</svg>
```

Em 24px ou menos, use a versão **tamanho pequeno**: moldura 39 × 38 com traço 5, pinos com 5,4 de espessura e só o nó (raio 8,2), sem células nem linha.

## Components

> Estados documentados: padrão e pressionado. Pressionado usa Azul profundo e `transform: scale(0.96)` (derivado). Foco de teclado, como no site do manual: contorno 2px `{colors.primary}` com 3px de afastamento.

### Navegação

**`topbar`** — Barra superior fixa com 60px de altura. Fundo `{colors.sand}` a 92% com `backdrop-filter: blur(12px)` e borda inferior 1px `{colors.hairline-soft}`. À esquerda, o logo (`{component.wordmark}` com 24px de corpo) e o seletor de área (`{component.segmented-control-active}`); à direita, a seção atual (número em pílula Azul + nome em `{typography.label-mono}`) e o botão "Seções".

**`segmented-control-active`** — Seletor em pílula. Trilho com 3px de respiro em Ink 7% (`{colors.hairline-soft}`); item ativo branco com `box-shadow: 0 1px 3px rgba(11, 11, 15, 0.12)`; itens inativos em `{colors.ink-muted}`.

**`menu-drawer`** + **`menu-item-active`** — Abaixo de 1440px, gaveta de 360px (máximo 90% da tela) que entra pela direita sobre um véu escuro; fecha com o X, com Esc ou tocando fora. A partir de 1440px, vira barra lateral fixa de 284px com borda direita `{colors.hairline-soft}`. Itens com número em pílula mono (Ink 7%, vira Azul quando ativo) e nome em Inter 14,5px/500; grupos com rótulo em `{typography.label-mono}` e `{colors.ink-subtle}`. Item ativo: fundo branco e anel 1px.

### Seções e texto

**`section-sand`**, **`section-white`**, **`section-ink`**, **`section-deep`** — Faixas de largura total com padding de 128px (64px no celular) e gutter de 48px (16px no celular). A seção Ink pode receber a grade de pontos da linguagem técnica.

**`eyebrow`** + **`eyebrow-number`** — Rótulo de seção em JetBrains Mono, caixa alta, +8%, Azul (branco a 74% em fundo escuro). O número fica numa pílula Azul de 22px de altura. Use numeração só quando a ordem importa.

**`text-body`**, **`text-caption`** e as versões **`-on-dark`** — Corpo em `{colors.ink-muted}` (branco a 74% no escuro); legendas e metadados em `{colors.ink-subtle}` (branco a 70% no escuro).

**`divider`**, **`divider-soft`**, **`divider-on-dark`** — Linhas de 1px. Use `divider` em tabelas e listas de valores, `divider-soft` dentro de cartões e `divider-on-dark` sobre Ink ou Azul profundo.

### Botões

**`button-arrow`** — A assinatura de ação da marca: círculo Azul de 52px com uma seta branca (ícone de 22px, traço 1,8). Um por peça ou por cartão. Nas peças sociais, fica embaixo à esquerda, alinhado à margem, com 135px de diâmetro no canvas de 1080px. Pressionado: `{component.button-arrow-pressed}`.

**`button-primary`** — Pílula Azul com texto branco em `{typography.button-md}`, 48px de altura e padding 14px × 22px. Pode levar uma seta de 18px à direita. O texto diz exatamente o que acontece ("Garantir minha vaga", "Ver a agenda de outubro"). Pressionado: `{component.button-primary-pressed}`. Um botão primário por tela.

**`button-secondary`** — Pílula branca com borda 1px `{colors.hairline}` e texto Ink, 44px de altura. Usada para ações de apoio ("Copiar legenda", "Seções"). Em fundo escuro, use **`button-on-dark`**: fundo branco a 8%, borda `{colors.hairline-on-dark}` e texto branco.

**`link-sticker`** — A "figurinha de link" que nasceu nos stories ("Vem com a gente →"): pílula branca com texto Azul e um `{component.button-arrow}` de 36px no fim. Funciona como chamada para ação sobre fundos Azul profundo, Ink e fotos.

### Selos, tags e caixas

**`seal-category`**, **`seal-category-ink`**, **`seal-category-light`** — Círculo com o ícone da categoria (ícone = 46% do selo). Fica no topo de toda peça e diz do que ela trata. Alterna Azul e Ink com ícone branco; a versão clara (branca com ícone Azul) completa a sequência dos destaques. Tamanhos: 48px na interface, 135px em posts, 150px em stories.

**`tag`**, **`tag-filled`**, **`tag-ink`** — Pílula de dados em `{typography.label-mono-sm}`, caixa alta: categoria, formato e preço ("HACKATHON", "REMOTO", "GRÁTIS"). A principal é cheia em Azul; as secundárias têm contorno 1px da cor do texto sobre o fundo da seção; Ink serve para destaque neutro. No máximo três por cartão.

**`definition-callout`** — A caixa "o que é isso?", que explica um termo técnico em uma frase simples. Fundo `{colors.primary-tint}`, raio 16px, círculo Azul de 22px com "?" branco a 14px da borda esquerda, termo em Inter 600 Ink seguido da explicação em `{colors.ink-muted}`. Sobre Ink: fundo branco a 8% e termo em branco. Sobre Azul profundo: o mesmo, com o "?" em círculo branco e texto Azul profundo.

### Cartões

**`card`** — Branco, raio 24px, padding 24px e anel `0 0 0 1px` em `{colors.hairline-soft}`. Em fileiras de cartões, os botões ficam alinhados na base.

**`card-sand`** — Painel Sand sem borda, para agrupar conteúdo dentro de seções brancas.

**`card-on-ink`** / **`card-on-deep`** — Painel branco a 8% sobre fundo escuro, raio 20px, padding 22px, texto branco.

### Agenda (derivado, para a plataforma)

**`event-card`** — Versão de interface do post "Evento". `{component.card}` com:

1. `{component.date-block}` à esquerda (dia em `{typography.date-display}`; mês e dia da semana em `{typography.label-mono}` embaixo);
2. linha de tags (`{component.tag-filled}` para a categoria + `{component.tag}` para formato e preço);
3. título em `{typography.title-md}`, até três linhas;
4. dados em `{typography.data-mono}` com ícones de 16px (horário, local);
5. `{component.button-arrow}` de 44px no canto inferior.

Fora de listas filtradas por categoria, o cartão leva um `{component.seal-category}` de 40px no topo.

**`date-block`** / **`date-block-today`** — Bloco de data quadrado (raio 16px) em Sand. O dia de hoje, ou um evento ao vivo, vira círculo Azul: é o "nó vivo" da marca.

**`calendar-day`**, **`calendar-day-event`**, **`calendar-day-today`** — Calendário do mês em 7 colunas (D S T Q Q S S em mono), gap de 5 a 9px, dentro de um `{component.card}`. Dias sem evento em `{colors.primary-tint-white}`, dias com evento em `{colors.primary-40-white}` e hoje em círculo Azul com halo `0 0 0 6px rgba(46, 75, 255, 0.14)`. A legenda ("dia com evento na agenda" · "hoje: acontecendo agora") fica sempre visível.

**`grade-cell`** + **`grade-node`** — Elemento G1, a grade viva em fileira: células de 18px com gap de 6px em Azul a 40%, e uma única posição vira nó (círculo Azul). Serve como marcador de progresso ("5 de 6"), padrão de fundo e estampa.

### Marca

**`symbol-grade-viva`** / **`symbol-grade-viva-on-dark`** — O símbolo (ver Shapes). `textColor` é a cor da moldura e dos pinos; células e nó continuam azuis em qualquer fundo. Tamanho mínimo: 16px, usando a versão "tamanho pequeno" até 24px.

**`wordmark`** / **`wordmark-on-deep`** — Logo em League Spartan 800. Proposta A (em validação): "&lt;tech&gt;" pequeno (52% do tamanho) acima de "d▢te", com o símbolo em contorno ocupando o lugar do "a" (lado de 0,571em). Largura mínima: 96px na tela, 25mm impresso. Área de proteção: a altura do ícone do "a" livre em todos os lados. Versões: Azul sobre Sand (padrão), Azul sobre Branco, Branco sobre Ink e Branco sobre Azul profundo — nunca sobre o Azul #2E4BFF.

**`squiggle`** — O rabisco: traço contínuo de 1,6px na interface (cerca de 6px no canvas de 1080px), pontas e junções redondas, sempre `{colors.primary}`. Sai de um canto — em posts, o oposto ao botão de seta — e nunca cruza texto. Há cinco desenhos oficiais: laço, onda, trilhos, seta desenhada e onda simples.

### Formulários (derivado)

**`text-input`** / **`text-input-focus`** — Campo branco de 48px, raio 12px, borda 1px `{colors.hairline}`, texto em `{typography.body-md}`. Rótulo acima em `{typography.label-mono}` e `{colors.ink-subtle}`; texto de ajuda abaixo em `{typography.body-sm}`. Foco: borda 2px Azul com halo `0 0 0 4px rgba(46, 75, 255, 0.14)`. Erro: borda 2px Ink, ícone "x" e uma mensagem que diz como resolver (a marca não tem vermelho — ver Known Gaps).

### Feedback

**`toast`** — Aviso em pílula Ink com texto branco em `{typography.button-md}` e, à esquerda, um círculo Azul de 26px com check branco. Aparece na base da tela, acima da área segura do celular, por cerca de 2 segundos. Texto curto: "Copiado", "Evento salvo".

### Peças sociais e eventos

**`post-feed`**, **`post-feed-white`**, **`post-feed-ink`**, **`post-feed-deep`**, **`story`**, **`story-sticker`**, **`highlight-cover`**, **`highlight-cover-ink`**, **`highlight-cover-light`**, **`badge-participant`**, **`badge-ambassador`** e **`badge-staff`** — Tokens de base das peças. Anatomia, medidas e regras completas na seção Social & Print.

## Do's and Don'ts

### Do

- Use `{colors.sand}` como fundo padrão. Branco é respiro: cartões, figurinhas e adesivos.
- Use `{colors.primary}` para toda ação e todo destaque — e só para isso.
- Comece peças sociais com o `{component.seal-category}` no topo e termine com o `{component.button-arrow}` embaixo à esquerda.
- Alterne fundos lisos (Sand, Branco, Ink, Azul profundo) para criar ritmo. A troca de cor é o divisor.
- Escreva títulos em frase normal, em League Spartan 700, com espaçamento negativo.
- Coloque datas, horários, locais, categorias e preços em JetBrains Mono, caixa alta, com o ponto médio (·) separando.
- Explique todo termo técnico em uma frase simples, com `{component.definition-callout}` ou na própria legenda.
- Mantenha as células do símbolo sempre Azul a 40% e o nó sempre Azul 100%, em qualquer fundo.
- Aplique o rabisco sempre em Azul, saindo de um canto, sem cobrir texto.
- Deixe livre em volta do logo pelo menos a altura do ícone que substitui o "a".
- Sinalize conteúdo pago ("parceria paga") e mostre a faixa salarial em toda vaga.
- Faça o teste de reconhecimento em qualquer peça nova: sem o logo, ainda parece Tech Date?

### Don't

- Não crie cores fora das cinco, não use preto puro (#000000) e não use gradiente.
- Não coloque o símbolo nem texto Azul sobre o Azul #2E4BFF: o nó some. Use Azul profundo.
- Não use Azul sobre Ink em textos menores que 24px (3,3:1).
- Não estique, gire, incline, contorne ou aplique sombra no logo; não mude a cor do nó nem redesenhe o logo com outra fonte.
- Não escreva títulos em CAIXA ALTA nem use JetBrains Mono em texto longo.
- Não centralize textos (exceto em bottons e adesivos) e não use mais de três tamanhos de texto numa peça.
- Não coloque sombra em botões, selos, tags, textos ou na arte dos posts.
- Não use mais de um elemento da linguagem técnica (pontos, cantos de câmera, terminal, numeração) por peça digital.
- Não use a grade de pontos em fundo claro nem em posts.
- Não deixe dois posts de mesmo fundo encostados no feed.
- Não coloque o logo de um parceiro maior que o da Tech Date, não cole os logos sem respiro e não funda as duas marcas num logo só.
- Não use logo grande no meio de camisetas.
- Não escreva "disruptivo", "sinergia", "alavancar", "ninja", "rockstar", "imperdível" ou "game changer".

## Iconography

### Ícones de categoria

- **Grade:** 24 × 24px com 2px de margem — o desenho mora na área útil de 20px.
- **Traço:** 1,8px, pontas e cantos arredondados, sem preenchimento, sem sombra e sem degradê.
- **Detalhe cheio** só quando ajuda a leitura, como o ponto maior do calendário, que ecoa o nó da Grade Viva.
- **Cor:** branco dentro de selos Azul ou Ink; Azul quando solto sobre Sand ou Branco; Ink em listas neutras.
- **Tamanhos:** 16, 20, 24, 32 e 48px.

| Categoria | Ícone | Uso |
|---|---|---|
| Eventos | calendário com nó | Meetups, conferências, feiras; destaque "Agenda" |
| Vagas | maleta | Estágio, júnior, primeiras oportunidades |
| Cursos | capelo | Trilhas, bolsas, formações |
| Comunidade | duas pessoas | Grupos e meetups recorrentes |
| Tecnologia | notebook com prompt | Ferramentas e temas |
| Conteúdo | lâmpada | Guias e carrosséis educativos |
| Presença em eventos | pino de mapa | Cobertura ao vivo |
| Cupons | tíquete | Descontos de parceiros |
| Embaixadores | megafone | Gente de cada cidade |
| Crescimento | seta de gráfico subindo | Carreira e dicas |
| Hackathons | colchetes de código | Maratonas de criação |
| Parceiros | dois círculos entrelaçados | Marcas que apoiam |

Ícones utilitários no mesmo desenho: seta, relógio, local, copiar, check, x, link, menu, sino, wi-fi, e-mail, globo, faísca, coração, enviar, play, usuário e escudo.

### Variações do símbolo

O Icon & Visual System tem uma matriz de **6 estilos × 6 combinações de cor**; fora dela, a versão não existe.

- **Estilos:** contorno (principal) · preenchido (moldura cheia; as células viram recortes na cor do fundo a 50% e o nó ganha um anel da cor do fundo — única exceção à regra das células azuis) · reduzido (sem moldura: três células, linha e nó) · circular (dentro de um círculo) · quadrado (dentro de um quadrado com raio de 25%) · tamanho pequeno (≤ 24px).
- **Combinações:** Primária (moldura Azul sobre Sand) · Clara (Azul sobre Branco) · Sóbria (Ink sobre Sand) · Negativa (Branco sobre Ink) · Profunda (Branco sobre Azul profundo) · Elétrica (Azul sobre Ink, só a partir de 48px).

### Elementos gráficos de apoio

| Código | Elemento | Regra |
|---|---|---|
| L1 | Rabisco laço | Assinatura das peças sociais; sai de um canto |
| L2 | Rabisco onda | Mais calmo; crachás e peças com muita informação |
| L3 | Trilhos | Três linhas em curva; melhor em fundo escuro |
| L4 | Linha-nó | Célula → linha → nó; o gesto do símbolo na horizontal |
| G1 | Grade viva | Células a 40% e um nó; progresso, padrão, estampa |
| G2 | Grade de pontos | Linguagem técnica; só sobre Ink ou Azul profundo |
| G3 | Calendário do mês | Grade real do mês; eventos a 40%, hoje em círculo |
| G4 | Moldura de câmera | Quatro cantos de 24px × 2px; enquadra títulos no palco e na camiseta |
| F1 | Selo circular | Categoria da peça; Azul e Ink alternados |
| F2 | Pílula de tag | Dados em mono; cheia para o principal |
| F3 | Folha | Forma de apoio, grande e clarinha atrás do conteúdo |
| F4 | Faísca | Novidade ou destaque; no máximo uma por peça, nunca no lugar do selo |
| S1 | Botão de seta | Chamada para ação; um por peça |
| S2 | Seta de linha | Liga informações: de → para, hoje → amanhã |
| S3 | Seta desenhada | Aponta um detalhe dentro de post ou story |
| S4 | Colchetes | `< ● >`, o sotaque de código herdado do antigo &lt;tech&gt; |

## Social & Print

### Post de feed (1080 × 1350px)

| # | Parte | Especificação no canvas de 1080px |
|---|---|---|
| 1 | Selo de categoria | 135px, canto superior esquerdo, a 80px das bordas |
| 2 | Logo | Canto superior direito, cerca de 100px de altura; nunca maior que o selo |
| 3 | Data em destaque | Quando a data é a notícia: dia em `{typography.social-number}` Azul, mês em League Spartan 700 80px e dia da semana em mono |
| 4 | Tag | `{typography.social-tag}` em Azul: categoria · formato · preço |
| 5 | Título | `{typography.social-title}`, até três linhas; uma palavra pode ir em Azul |
| 6 | Dados | Mono 32px com ícones de 40px: horário, local |
| 7 | Botão de seta | 135px, embaixo à esquerda; ao lado, o @ ou o prazo em mono 30px a 60% |
| 8 | Rabisco | Canto oposto ao botão, saindo da borda (cerca de 540 × 370px), traço de ≈6px |

- **Fundos:** Sand, Branco, Ink ou Azul profundo, sempre lisos.
- **Formatos recorrentes:** Evento · Oportunidades da semana (lista com pílulas "Bolsa", "Estágio", "Curso") · Calendário do mês (grade 7 × 5, dias com evento em círculo Azul) · Vaga (tags + faixa salarial obrigatória) · Carrossel educativo (5 cards: capa, três dicas numeradas 01–03, fechamento com chamada; contador "1/5") · Comunidade (três números) · Embaixador(a) (avatar com anel Azul + citação) · Parceiro (etiqueta "parceria paga" + cupom em pílula branca) · Post de marca.
- **Legenda:** gancho curto, depois o essencial (data, local, preço), a chamada para ação e 2 ou 3 hashtags.

### Story (1080 × 1920px)

- **Área segura:** 250px livres em cima e embaixo.
- **Tipografia:** título `{typography.story-title}`, corpo em Inter ≈46px, tag em mono ≈38px; selo de 150px.
- **Figurinhas (`{component.story-sticker}`):** cartão branco com raio de ≈54px e sombra suave. Enquete (barras em pílula, opção vencedora em Azul) · contagem regressiva (três blocos Sand com números Azuis + botão "Lembrar") · vaga · caixinha de perguntas (topo Azul) · cupom (pílula branca com o código em mono).
- **Link:** `{component.link-sticker}`.
- **Agenda da semana:** lista de dias em blocos de data; o destaque da semana vira círculo.

### Destaques

Arquivo de story em Sand com um círculo de 660px no centro (`{component.highlight-cover}`); ícone branco ocupando 44% do círculo. Cores em sequência Azul → Ink → Branco (`-light`, com ícone Azul). Nome com uma palavra só: Agenda, Vagas, Cursos, Comunidade, Hackathons, Cupons, Embaixadores, Parceiros.

### Perfil

Foto de perfil com o símbolo em contorno Azul sobre Sand e anel Azul. Bio: "A agenda do ecossistema tech brasileiro. Eventos, cursos, vagas, comunidades e hackathons — conferidos um por um." Feed montado com a regra do tabuleiro.

### Embaixadores

- **Credencial digital:** 85,6 × 54mm (tamanho de cartão), fundo Sand, avatar com anel Azul e o selinho do megafone, cargo em mono Azul, nome em League Spartan 700, ID em mono e QR.
- **Selo oficial:** círculo branco com o texto "EMBAIXADORA OFICIAL · TECH DATE" em mono ao redor e centro Azul com megafone branco.
- **Moldura de foto:** anel Azul com o selinho do megafone no canto.
- **Assinatura local:** a cidade vai numa etiqueta em mono (pílula Azul ou Ink) ao lado do logo — nunca dentro dele.

### Parceiros

- **Assinatura com divisória** para eventos em conjunto e **assinatura com "×"** para posts de parceria: mesma altura visual e respiro de 1x de cada lado.
- **Faixa de apoio:** "realização" (Tech Date) + "apoio" (parceiros em uma cor só, mesma altura, na ordem do contrato), em banners, backdrops e rodapés.

### Eventos físicos

- **Crachás** na proporção 10 × 14,6 (ex.: 100 × 146mm), com furo no topo.
  - `{component.badge-participant}`: frente Sand, verso Branco com programação, Wi-Fi e QR de check-in.
  - `{component.badge-ambassador}`: frente Azul profundo com selo branco e a etiqueta "pode me perguntar sobre a agenda"; verso Sand com o roteiro do dia.
  - `{component.badge-staff}`: frente Ink com "Staff" gigante em Azul e faixa Azul na base; verso Branco com contatos rápidos e código de conduta.
  - Num crachá de 100mm: cargo em League Spartan 800 com ≈12mm, nome em 700 com ≈9mm (legível a 2 metros), detalhes em Inter com ≈4mm, ID em mono com ≈3mm.
- **Cordão:** 2cm, Azul, com "tech date · salva a data" em mono branco.
- **Backdrop (step and repeat):** 3 × 2m, Azul profundo com grade de pontos; logo branco e símbolo alternados em diagonal.
- **Banner roll-up:** 85 × 200cm, Sand: logo no topo, selo, título, grade viva, QR com "aponte a câmera" e apoio só na base.
- **Sinalização:** placas A3 (Ink ou Sand) e displays de mesa A6. De longe, só três coisas: logo, uma frase e uma seta. Letras com pelo menos 2,5cm de altura para cada metro de distância de leitura.

### Merchandising

- **Camisetas:** composições de cultura tech, nunca logo grande no meio — Terminal (Ink), Grade viva (Sand), Erro 404 (Azul profundo) e Loop infinito (Branco, nas costas). Serigrafia em duas cores.
- **Bottons de 38mm:** frases curtas e espirituosas ("sudo me dá um estágio", "404: sono not found", "deploy na sexta? jamais", "hackathon é meu cardio", "funciona na minha máquina"), fundos nas cinco cores, anel de texto em mono opcional.
- **Adesivos:** vinil fosco de 5 a 8cm, corte especial com borda branca de 3mm, em kit com 6.
- **Objetos:** ecobag de algodão cru, caderno Azul profundo com o símbolo em baixo-relevo, squeeze Ink de 600ml com tampa Azul, chaveiro de acrílico com o símbolo preenchido e cartão de visita de 85 × 55mm (frente Azul profundo com logo, verso Sand com contato e QR).

## Voice in Interface

O tom de voz — o jeito como a marca escreve — faz parte do design. Na interface ele é **direto** (o importante primeiro: o quê, quando, onde, quanto custa), **caloroso** (convite, não ordem), **sem jargão à toa** (termo técnico sempre explicado) e **de dentro** (fala de quem vai aos eventos).

| Situação | Assim | Não assim |
|---|---|---|
| Botão principal | "Garantir minha vaga" · "Ver a agenda de outubro" | "Clique aqui" · "Saiba mais" |
| Confirmação | "Evento salvo" · "Copiado" | "Operação realizada com sucesso" |
| Erro | "Não deu para salvar. Confira sua conexão e tente de novo." | "Erro 500" · "Algo deu errado" |
| Tela vazia | "Nada marcado para esse dia ainda. Que tal ver a semana inteira?" | "Nenhum resultado encontrado" |
| Mudança | "Mudou: o evento agora é dia 24/10. O link de inscrição continua o mesmo." | "Informamos que o evento foi reprogramado" |
| Termo técnico | "Pitch: a apresentação curtinha do seu projeto" | "Prepare seu pitch" (sem explicar) |

**Palavras que usamos:** bora, cola, tá rolando, salva a data, comunidade, trilha, primeiro passo, de graça.
**Palavras que evitamos:** disruptivo, sinergia, alavancar, ninja, rockstar, imperdível, game changer.

## Responsive Behavior

### Breakpoints

| Nome | Largura | O que muda |
|---|---|---|
| Celular pequeno | ≤ 360px | Botão "Seções" só com ícone; combinações de cor em 1 coluna |
| Celular | 361–600px | Cartões, posts e stories em 1 coluna; seletor de área vai para dentro do menu (≤ 560px); crachás em 1 coluna (≤ 520px) |
| Tablet | 601–1040px | Posts, stories e bottons em 2 colunas; cartões de 3 colunas empilham até 980px; seção atual some da barra (≤ 900px) |
| Notebook | 1041–1439px | Grades completas (4 posts, 4 stories, 6 ícones); menu em gaveta |
| Desktop | ≥ 1440px | Menu lateral fixo de 284px |
| Monitor grande | ≥ 1680px | Contêiner de 1320px |
| Monitor muito grande | ≥ 2200px | Contêiner de 1480px |

### Como os blocos se reorganizam

- **Posts:** 4 → 2 colunas (≤ 1040px) → 1 (≤ 560px). O carrossel vira rolagem lateral com encaixe por card.
- **Stories:** 4 → 2 (≤ 1040px) → 1 (≤ 600px), com o celular limitado a 290px de largura.
- **Paleta:** 5 colunas → linhas com cor à esquerda (≤ 980px) → empilhado (≤ 480px).
- **Ícones de categoria:** 6 → 3 (≤ 900px) → 2 (≤ 420px). **Destaques:** 8 → 4 (≤ 900px) → 3 (≤ 440px).
- **Tabelas largas** (matriz do símbolo, escala tipográfica) rolam dentro do próprio quadro; a página nunca rola na horizontal.
- **Cartões vizinhos** mantêm os botões alinhados na base em qualquer largura.

### Tipografia fluida

| Token | Fórmula |
|---|---|
| `{typography.display-hero}` | `clamp(56px, 10vw, 132px)` |
| `{typography.display-statement}` | `clamp(34px, 5.4vw, 70px)` |
| `{typography.headline-display}` | `clamp(36px, 5.6vw, 68px)` |
| `{typography.headline-lg}` | `clamp(30px, 4.2vw, 54px)` |
| `{typography.headline-sm}` | `clamp(23px, 2.5vw, 30px)` |
| `{typography.body-lg}` | `clamp(17px, 1.7vw, 20px)` |

### Área de toque

- Mínimo de 44 × 44px na plataforma. `{component.button-arrow}` tem 52px; `{component.button-primary}`, 48px; campos, 48px.
- As pílulas utilitárias do manual (≈32px de altura) servem para desktop; em telas de toque, suba para 44px.
- Respeite `env(safe-area-inset-*)` em barras fixas e no aviso.

## Iteration Guide

1. Trabalhe um componente por vez e cite os tokens pelo nome (`{component.event-card}`, `{colors.primary}`).
2. Variantes entram como componentes separados (`-pressed`, `-focus`, `-ink`, `-today`, `-on-dark`).
3. Não escreva HEX solto: use tokens. Precisa de um tom novo? Faça uma opacidade de uma das cinco cores.
4. Antes de adicionar borda ou sombra, troque o fundo (Sand ↔ Branco ↔ Ink ↔ Azul profundo).
5. Títulos sempre em League Spartan 700/800 com espaçamento negativo; corpo em Inter 400 16/26; dados em JetBrains Mono.
6. Toda tela tem, no máximo, um botão primário e um rabisco.
7. Valide o arquivo com `npx @google/design.md lint DESIGN.md`. Para gerar o tema do Tailwind v4: `npx @google/design.md export --format css-tailwind DESIGN.md`.

## Known Gaps

- **Logo final pendente.** Os tokens `wordmark` descrevem a proposta A; as propostas B (em linha) e C (empilhada) seguem em avaliação.
- **@ oficial do Instagram não definido.** As peças de exemplo usam @techdatebr apenas como ilustração.
- **Sem cores de estado.** A paleta não tem vermelho, verde ou amarelo. Proposta até haver decisão: sucesso em Azul com ícone check; erro em Ink com ícone "x" e mensagem que explica como resolver; atenção com `{component.tag-ink}`. Criar cores semânticas quebra a regra das cinco cores e precisa de aprovação.
- **Modo escuro de interface não definido.** As seções Ink e Azul profundo e os tokens `-on-dark` são o ponto de partida.
- **Movimento sem tokens.** O site do manual usa 150ms em trocas de cor, 200ms no aviso e 280ms na gaveta, com `ease`, e respeita `prefers-reduced-motion`.
- **Formulários, calendário da plataforma e cartão de evento** são derivados deste documento; ainda não existem no Brand Book.
- **Fotografia, ilustração e gráficos de dados** não foram definidos; os exemplos usam avatares com iniciais e nenhuma foto.
- **Legendas do manual publicado** usam Ink 54% e Branco 55%, abaixo do mínimo AA; este documento corrige para 62% e 70%.
