# Nexus Marketing Estratégico

Site institucional da **Nexus Marketing Estratégico** — marketing estratégico e CRM com IA (FlakeDesk) para médicos e clínicas.

Site estático (HTML + CSS + JavaScript), sem etapa de build.

## Estrutura

```
.
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos
├── js/
│   └── main.js         # Animações e interações
└── images/
    ├── flakedesk-print.jpg
    └── solucoes/       # Imagens da seção "Soluções"
```

## Bibliotecas (via CDN)

- [GSAP 3.12.5](https://gsap.com/) + ScrollTrigger — animações
- [Lenis 1.1.13](https://lenis.darkroom.engineering/) — rolagem suave
- [Lucide 0.469.0](https://lucide.dev/) — ícones
- Google Fonts: Inter, Instrument Serif, Plus Jakarta Sans

Se alguma biblioteca não carregar, o conteúdo continua visível e funcional.

## Rodar localmente

Abra o `index.html` no navegador, ou use um servidor local:

```bash
npx serve .
# ou
python -m http.server 8000
```

## Publicar no GitHub Pages

1. Envie os arquivos para um repositório no GitHub (o `index.html` precisa ficar na raiz).
2. No repositório, vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
4. Salve. Em alguns minutos o site estará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Contato

WhatsApp: [(31) 9135-1242](https://wa.me/553191351242)

---

© 2026 Nexus Marketing Estratégico Ltda. Todos os direitos reservados.
FlakeDesk™ é uma marca da VentureCode.
