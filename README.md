# Tremor e Bronze — Página de Vendas

Landing page do devocional **Tremor e Bronze**, de Pr Francisco Gomes (Editora Graça).

Site estático (HTML/CSS/JS puro, sem build), pronto para deploy direto na Vercel.

## Estrutura

- `index.html` — página única com todas as seções (hero, dor, virada, sumário, recursos, autor, garantia, FAQ, CTA final).
- `assets/book-cover.png` — capa do livro.
- `assets/favicon.svg` — ícone do site.
- `vercel.json` — cache dos assets e URLs limpas.

## Checkout

Todos os botões de compra apontam para `https://pay.hotmart.com/T106610001N`. Todo o processo de pagamento, entrega e reembolso é feito pela Hotmart.

## Antes de publicar

Ajuste `og:image` e `canonical` em `index.html` para o domínio final, se for diferente de `tremorebronze.com.br`.

## Deploy na Vercel

1. Acesse [vercel.com](https://vercel.com) e clique em **Add New → Project**.
2. Importe este repositório do GitHub (`FranciscoDGA/pv-tremor-e-bronze`).
3. Framework preset: **Other** (site estático) — nenhuma configuração de build é necessária.
4. Clique em **Deploy**.

Qualquer novo push na branch `main` atualiza o site automaticamente.
