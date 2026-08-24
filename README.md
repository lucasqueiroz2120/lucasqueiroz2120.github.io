# Portfólio — Lucas Queiroz

Portfólio pessoal de UX/UI Design. Site estático de arquivo único
(`index.html`), sem build e sem dependências.

## Rodar localmente

Basta abrir `index.html` no navegador. Para servir via HTTP:

```bash
npx serve .
```

## Estrutura

- `index.html` — página inteira (HTML + CSS + JS)
- `assets/` — screenshots dos projetos exportados do Figma
- `.nojekyll` — impede o GitHub Pages de processar o site com Jekyll

## Publicar no GitHub Pages

1. Suba este diretório para um repositório
2. Settings → Pages → Source: `Deploy from a branch` → `main` / `(root)`
3. O site fica em `https://<usuario>.github.io/<repo>/`
   (ou na raiz, se o repositório se chamar `<usuario>.github.io`)
