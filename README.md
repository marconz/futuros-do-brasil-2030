# Futuros do Brasil 2030

Jogo interativo sobre as propostas dos dois candidatos do segundo turno da eleição presidencial de 2026. A pessoa escolhe entre dois futuros possíveis em 12 cenas de 2030 e, no final, vê com qual plano de governo suas escolhas mais combinam, tema por tema, com a página de cada proposta.

## Fontes

Todo o conteúdo vem dos planos de governo oficiais:

- Programa de Governo de Lula (84 páginas)
- Diretrizes do Plano de Governo de Flávio Bolsonaro 2027–2030 (76 páginas)

As páginas citadas no jogo e no comparativo são as dos PDFs oficiais.

## Estrutura

| Arquivo | O que é |
| --- | --- |
| `index.html` | A página do jogo: introdução, perguntas, resultado, compartilhamento e comparativo |
| `data.js` | O conteúdo: as 12 perguntas, as cartas "Você sabia?" e a matriz comparativa com 88 temas |
| `img/` | As 12 fotos do letreiro 2030, em WebP (482 KB no total) |

Para editar o texto de uma pergunta ou de uma linha do comparativo, altere só o `data.js`.

## Como testar no computador

Abra o arquivo `index.html` no navegador. Não precisa instalar nada.

## Como publicar

É um site estático: funciona em Cloudflare Pages, Vercel, Netlify ou GitHub Pages, sem banco de dados.

O site está publicado em https://futuros-do-brasil-2030.vercel.app, que a Vercel atualiza a cada alteração no GitHub. Se mudar de domínio, troque o endereço em `SHARE_URL` e nas etiquetas `og:` no topo do `index.html`.

## Privacidade

O jogo não guarda respostas nem soma resultados de jogadores. Tudo roda no navegador de quem joga. Não acrescente coleta de respostas: opinião política é dado sensível pela LGPD, e o TSE proíbe enquetes durante a campanha.
