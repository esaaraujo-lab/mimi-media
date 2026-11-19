# MAISON de MiMi — Mídia da Loja

Mídia oficial da **MAISON de MiMi**, perfumaria online — [fabiana.eu.org](https://fabiana.eu.org). Fotos e vídeos dos produtos, servidos gratuitamente pelo [jsDelivr](https://www.jsdelivr.com/).

## A loja

A MAISON de MiMi é uma perfumaria que vende **perfumes árabes**, **Brand Collection** (inspirados nas grandes grifes), **miniaturas** e o **kit com 3 decantes à escolha**.

- **Perfumes árabes** — [Lattafa](https://fabiana.eu.org/marcas/lattafa), Al Wataniah, Afnan e outras casas orientais. Oud, âmbar, almíscar e especiarias: [ver perfumes árabes](https://fabiana.eu.org/catalogo).
- **Brand Collection 25ml** — inspirados nos clássicos das grifes (Chanel, Dior, Carolina Herrera, Paco Rabanne, Lancôme, Versace e mais), com o mesmo DNA olfativo por uma fracção do preço.
- **Miniaturas árabes** — Afeer e Arabic Collection, para conhecer sem compromisso.
- **Kit 3 decantes à escolha** — R$100, qualquer decante menos os Tharwahh; e **presente decante** a partir de R$199 em Brand Collection.
- **Frete grátis** — a partir de R$399 em árabes e R$199 em Brand Collection e miniaturas.

## Guias e artigos

- [Perfumaria de nicho chinesa](https://fabiana.eu.org/guias/perfumaria-de-nicho-chinesa) — as casas chinesas que estão a reinventar o nicho.
- [Perfumaria autoral](https://fabiana.eu.org/guias/perfumaria-autoral) — o que é um perfume autoral e como o reconhecer.
- [Descobrir o teu nicho](https://fabiana.eu.org/guias/descobrir-o-teu-nicho) — como encontrar o teu perfume de nicho.
- [Artigos e guias](https://fabiana.eu.org/artigos) — famílias olfativas, guias de compra e alertas de segurança.

## Catálogo e marcas

- [Catálogo completo](https://fabiana.eu.org/catalogo) — todos os perfumes da loja.
- [Marcas](https://fabiana.eu.org/marcas/lattafa) — Lattafa, Chanel, Dior, Carolina Herrera, Paco Rabanne e mais.
- [A minha conta](https://fabiana.eu.org/conta) — pedidos e morada.

## Este repositório

Os ficheiros são enviados pela API do GitHub (Contents API) e servidos em `https://cdn.jsdelivr.net/gh/esaaraujo-lab/mimi-media@main/<caminho>`.

- `upload_images/` — fotos dos produtos (bc-\*.webp, af-\*.webp, ...).
- `products/<id>/` — fotos e vídeos novos enviados pelo admin da loja.
- `products/pending/` — fotos de produtos novos (antes de terem id).
- `avatars/` — avatares dos avaliadores (SVG).
- `hero/` — imagens e vídeos do hero da página inicial.

Nunca apagar os originais do `gdi_server` sem confirmar.
