# Colégio Futuro · Versão 2 (scroll dinâmico)

Site institucional do Colégio Futuro (Educação Infantil ao 9º ano, Recife – PE).
Projeto estático (HTML + CSS + JS), sem build. Animações com GSAP + ScrollTrigger via CDN (cdnjs).

## Estrutura
```
index.html      página única
img/            fotos da escola (Instagram @colegiofuturope)
favicon.svg
vercel.json     cache das imagens e cabeçalhos
robots.txt / sitemap.xml
```

## Rodar localmente
Abra o `index.html` no navegador ou rode `npx serve .`

## Publicar na Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Na Vercel: **Add New → Project → Import** o repositório.
3. Framework Preset: **Other**. Build Command: vazio. Output Directory: `./` (raiz).
4. Deploy. Depois, em **Settings → Domains**, aponte `colegiofuturope.com.br`.

## Antes de publicar
- Trocar o símbolo SVG do topo pelo logo oficial da escola.
- Conferir telefones, e-mail e o prazo da campanha de matrículas.
- Se o domínio for outro, ajustar `robots.txt` e `sitemap.xml`.
