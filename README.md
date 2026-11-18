# mimi-media

Mídia da loja MAISON de MiMi (fabiana.eu.org), servida pelo jsDelivr (grátis).

- `upload_images/` — fotos dos produtos (bc-*.webp, af-*.webp, ...).
- `covers/` — capas dos cursos da Meggy + `cover-manifest.json`.
- `products/<id>/` — fotos e vídeos novos enviados pelo admin da loja.
- `hero/` — imagens e vídeos do hero da página inicial.

Os ficheiros são enviados pela API do GitHub (Contents API) e servidos em
https://cdn.jsdelivr.net/gh/esaaraujo-lab/mimi-media@main/<caminho>.
Nunca apagar os originais do `gdi_server` sem confirmar.
