# Flora Bar — Site

Landing page do **Flora Bar**, speakeasy/bistrô escondido atrás de uma vitrine de flores nos Jardins, São Paulo. Site estático (HTML + CSS puro, sem build), em português, com efeito parallax leve e visual editorial (fontes Italiana + DM Mono + Manrope).

Repositório de deploy: [github.com/camilo-hikage/florabar](https://github.com/camilo-hikage/florabar)

## Páginas

| Arquivo | Conteúdo |
|---|---|
| [index.html](index.html) | Página inicial — hero, manifesto ("a casa"), cozinha, balcão, prévia do menu, localização/horários e reservas |
| [menu.html](menu.html) | Menu de comida: crudos, tapas, sanduíches, principais e sobremesas |
| [carta.html](carta.html) | Carta de vinhos: brancos, tintos, rosés/champagne e vinhos por taça |

## Estilos

- [styles.css](styles.css) — estilos globais/compartilhados (hero, header, footer, seções da home)
- [carta.css](carta.css) — estilos específicos das páginas de menu e carta de vinhos

## Assets

- `assets/flora-hero.png` — imagem de fundo do hero (usada em `index.html`, `menu.html`, `carta.html` via `styles.css`)

## Links externos usados no site

- Reservas: `https://r.odionisio.com/flora-bar`
- Instagram: [@florabar.sp](https://www.instagram.com/florabar.sp/)
- Linktree: `https://linktr.ee/florabarsp`
- Endereço: Rua Padre João Manuel, 795 — Jardim Paulista, São Paulo

## Rodando localmente

Não há build/dependências — basta abrir `index.html` no navegador, ou servir a pasta com um servidor estático simples:

```bash
python3 -m http.server 8000
```

## Observações

- Este repositório está aninhado dentro de `florabar-site/` (que por sua vez faz parte de um repositório git separado, `teste`, com histórico não relacionado — testes antigos de animações). O `florabar-publish/` é quem tem remote próprio no GitHub e é o site "de verdade".
- `florabar-site/index.html` (na pasta pai) é uma versão anterior/rascunho do `index.html` daqui — os links para menu/carta ainda apontam para um PDF no Google Drive em vez das páginas locais `menu.html`/`carta.html`.
