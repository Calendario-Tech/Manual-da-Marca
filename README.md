# Tech Date · Manual da marca

Site estático com os dois documentos da marca:

| Arquivo            | Conteúdo                                                                                                                                  |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| `index.html`       | **Brand Book**: estratégia, tom de voz, logo, cores, tipografia, ícone, posts, stories, feed, embaixadores, parceiros, eventos e merch    |
| `icon-system.html` | **Icon & Visual System**: processo do símbolo Grade Viva, matriz de variações, ícones de categoria, combinações de cor e elementos gráficos |

Cada arquivo é independente: o CSS e o JavaScript ficam dentro dele. As fontes vêm do Google Fonts, então a página precisa de internet para aparecer com a tipografia certa.

## Publicar com GitHub Pages

1. Crie um repositório e envie `index.html`, `icon-system.html` e este `README.md` para a raiz.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)` e salve.
4. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Também funciona em Netlify, Vercel ou Cloudflare Pages apontando para a pasta com os arquivos, sem etapa de build. Se o repositório for privado, confira se o seu plano do GitHub permite Pages em repositório privado.

## Como usar o site

- **Menu de seções:** no celular, tablet e notebook, o botão **Seções** abre o menu. A partir de 1440 px de largura, o menu fica fixo na lateral e marca a seção em que você está.
- **Copiar rápido:** dentro do menu ficam as 5 cores, as 3 fontes e atalhos para tokens CSS, tema Tailwind e link das fontes.
- **Clique para copiar:** tudo que tem o ícone de copiar, ou fica contornado em azul ao passar o mouse, vai para a área de transferência com um clique:
  - HEX, RGB, CMYK e variável CSS de cada cor; a paleta inteira em CSS, SCSS, Tailwind v4 ou JSON;
  - CSS de cada fonte, link do Google Fonts e cada linha da escala tipográfica;
  - legendas e textos das artes dos posts, do carrossel e dos stories; bio do perfil; assinatura de e-mail;
  - exemplos de tom de voz, frases de bottons, camisetas e objetos;
  - SVG do símbolo (e de cada versão da matriz), SVG de cada ícone de categoria e sprite com os 12;
  - SVG ou CSS de cada elemento gráfico (L1 a S4);
  - link direto de cada seção (ícone de corrente ao lado do número da seção).

## Como editar

Os textos estão direto no HTML, dentro de `<main>`, na mesma ordem do menu. Os desenhos são gerados pelo script no fim de cada arquivo a partir de atributos:

| Atributo  | Desenha                | Exemplo                                        | Opções                                                                                   |
| --------- | ---------------------- | ---------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `data-i`  | ícone de linha (24 px) | `<i data-i="cal"></i>`                         | `cal`, `job`, `edu`, `com`, `tec`, `idea`, `par`, `amb`, `cup`, `up`, `hack`, `pin`, `arrow`, `spark`, `check`… |
| `data-gv` | símbolo Grade Viva     | `<i data-gv="outline" data-f="#2E4BFF"></i>`   | `outline`, `filled`, `grid`, `circle`, `square`, `small`                                  |
| `data-sq` | rabisco azul           | `<span data-sq="a"></span>`                    | `a`, `b`, `c`, `d`, `e`                                                                   |
| `data-wm` | logo                   | `<span data-wm="a" style="--s:48px"></span>`   | `a` (recomendado), `b` (em linha), `c` (empilhado)                                        |
| `data-qr` | QR ilustrativo         | `<span class="qr" data-qr="qualquer-texto"></span>` | —                                                                                    |

Para tornar qualquer elemento copiável, adicione `class="js-copy"` e `data-copy="texto que será copiado"`.

As cores e fontes que os botões copiam ficam em um só lugar: `COLORS` e `FONTS`, no início da seção **4. Interface do site** do script.
