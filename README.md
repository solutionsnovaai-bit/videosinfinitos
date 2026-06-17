# V.I.A. — Vídeos Infinitos com IA

## 🚀 Deploy no GitHub Pages

1. Crie um repositório no GitHub (pode ser público ou privado)
2. Faça upload de **todos os arquivos** mantendo a estrutura de pastas
3. Vá em **Settings → Pages**
4. Em **Source**: branch `main`, pasta `/ (root)`
5. Clique em **Save** — o site fica live em ~30 segundos

## 📁 Estrutura

```
index.html          ← página principal (CSS e JS embutidos)
assets/
  hero-bg.png       ← imagem de fundo do hero
  whatsapp.svg      ← ícone WhatsApp (referência / uso futuro)
```

> **Nota sobre os ícones SVG:** Os ícones de WhatsApp da página já estão embutidos inline no HTML (`<svg>...</svg>`). O arquivo `assets/whatsapp.svg` está disponível caso queira usar em outros lugares.

## ⚡ Dependências externas

- Google Fonts (Barlow Condensed, Oswald, Barlow, Inter)
- GSAP 3.12.5 + ScrollTrigger

Carregadas via CDN — precisam de internet para funcionar.
Para versão 100% offline, use o arquivo `via-bundle.html`.
