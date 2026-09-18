# Tech Date · Manual da marca

Site estático com os dois documentos da identidade visual da **Tech Date** — a agenda de eventos de tecnologia, inovação e empreendedorismo do Brasil.

> © 2026 Tech Date. Todos os direitos reservados. Repositório público **apenas para consulta** — veja [LICENSE.md](LICENSE.md).

| Arquivo | Conteúdo |
| --- | --- |
| `index.html` | **Brand Book**: estratégia, tom de voz, logo, cores, tipografia, ícone, posts, stories, feed, embaixadores, parceiros, eventos e merch |
| `icon-system.html` | **Icon & Visual System**: processo do símbolo Grade Viva, matriz de variações, ícones de categoria, combinações de cor e elementos gráficos |
| `BRAND.md` | Resumo da marca em texto: nome, propósito, valores, tom de voz, logo oficial, cores, tipografia e símbolo |
| `DESIGN.md` | Os mesmos valores em tokens (cores, tipografia, espaçamentos e componentes), para usar em código e em ferramentas de design |
| `LICENSE.md` | Direitos de uso do material |

Cada HTML é independente: o CSS e o JavaScript ficam dentro dele. As fontes vêm do Google Fonts, então a página precisa de internet para aparecer com a tipografia certa.

## Antes do primeiro commit: deixe seu e-mail privado

O e-mail configurado no Git fica visível no histórico de um repositório público. Para publicar com o endereço anônimo do GitHub:

1. No GitHub, clique na sua foto → **Settings** → **Emails**.
2. Marque **Keep my email addresses private** e **Block command line pushes that expose my email**. Nessa mesma tela aparece o seu endereço anônimo, no formato `12345678+SEU-USUARIO@users.noreply.github.com`.
3. No computador, rode uma vez (trocando pelo endereço que apareceu no passo 2):

   ```bash
   git config --global user.email "12345678+SEU-USUARIO@users.noreply.github.com"
   git config --global user.name "Seu Nome"
   ```

4. Confira com `git config --global user.email`.

Quem envia os arquivos pela própria página do GitHub (**Add file → Upload files**) já usa o endereço anônimo automaticamente depois do passo 2. Commits feitos antes disso continuam com o e-mail antigo gravado no histórico.

## Publicar com GitHub Pages

1. Envie `index.html`, `icon-system.html` e os arquivos `.md` para a raiz do repositório.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)` e salve.
4. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

No plano gratuito, o GitHub Pages só publica repositório público. Também funciona em Netlify, Vercel ou Cloudflare Pages apontando para a pasta com os arquivos, sem etapa de build.

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

Esses atalhos são ferramentas de trabalho para quem tem autorização de uso da marca — copiar não libera o uso.

## Como editar

Os textos estão direto no HTML, dentro de `<main>`, na mesma ordem do menu. Os desenhos são gerados pelo script no fim de cada arquivo a partir de atributos:

| Atributo | Desenha | Exemplo | Opções |
| --- | --- | --- | --- |
| `data-i` | ícone de linha (24 px) | `<i data-i="cal"></i>` | `cal`, `job`, `edu`, `com`, `tec`, `idea`, `par`, `amb`, `cup`, `up`, `hack`, `pin`, `arrow`, `spark`, `check`… |
| `data-gv` | símbolo Grade Viva | `<i data-gv="outline" data-f="#2E4BFF"></i>` | `outline`, `filled`, `grid`, `circle`, `square`, `small` |
| `data-sq` | rabisco azul | `<span data-sq="a"></span>` | `a`, `b`, `c`, `d`, `e` |
| `data-wm` | logo | `<span data-wm="a" style="--s:48px"></span>` | `a` (logo oficial Tech Date), `old` (logo antigo Calendário Tech, usado só na história da marca) |
| `data-qr` | QR ilustrativo | `<span class="qr" data-qr="qualquer-texto"></span>` | — |

Para tornar qualquer elemento copiável, adicione `class="js-copy"` e `data-copy="texto que será copiado"`.

As cores e fontes que os botões copiam ficam em um só lugar: `COLORS` e `FONTS`, no início da seção **4. Interface do site** do script.

## Direitos de uso

Este repositório é público para facilitar a consulta, não para liberar o uso da marca. O nome Tech Date, o logo, o símbolo Grade Viva, os ícones, os elementos gráficos, as peças, os textos e o código são da Tech Date e não podem ser usados, copiados, adaptados ou redistribuídos sem autorização por escrito. Condições completas em [LICENSE.md](LICENSE.md).

Pessoas, parceiros, eventos, comunidades, perfis, sites e e-mails que aparecem nos exemplos são fictícios, criados só para mostrar como a marca se comporta.

As fontes League Spartan, Inter e JetBrains Mono pertencem a seus autores e são carregadas do Google Fonts sob a SIL Open Font License 1.1 — não estão neste repositório.
