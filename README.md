# mvp-dashboard-v02

Dashboard executivo mockado para Conatus (React + Tailwind via CDN, com componentes no estilo shadcn).

## Publicação no GitHub Pages

1. Faça push da branch `main` (ou `master`).
2. No GitHub, vá em **Settings → Pages** e deixe **Build and deployment = GitHub Actions**.
3. O workflow `.github/workflows/deploy-pages.yml` publica automaticamente.

> Se o repositório ainda não tiver Pages habilitado, o workflow já tenta habilitar com `enablement: true` no passo `actions/configure-pages`.

URL esperada (project pages):

- `https://<usuario-ou-org>.github.io/mvp-dashboard-v02/`
