<p align="center">
  <img src="https://raw.githubusercontent.com/abdoulrl2028-cloud-Dev/abdoulrl2028-cloud-Dev/main/assets/projects/portfolio.jpg" alt="Landing page de portfólio" width="100%">
</p>

# Landing Page + Deploy na Vercel 🌍

Projeto estático simples (HTML + CSS) pronto para deploy automático com GitHub e Vercel.

Inclui:
- imagem da seção principal em `assets/images/hero-image.svg`
- ícone do site (favicon) em `assets/images/favicon.svg`

## Estrutura

```txt
landing-page/
├── index.html
├── css/
│   └── style.css
├── assets/
│   └── images/
└── README.md
```

## 1) Subir para o GitHub

No terminal, dentro da pasta `landing-page`:

```bash
git init
git add .
git commit -m "feat: landing page inicial"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPO.git
git push -u origin main
```

## 2) Conectar na Vercel

1. Acesse [https://vercel.com](https://vercel.com)
2. Faça login com sua conta `abdoulrl2028@gmail.com`.
3. Clique em **Add New...** → **Project**.
4. Selecione o repositório da landing page.
5. Framework Preset: **Other** (ou deixe auto).
6. Build Command: vazio.
7. Output Directory: vazio.
8. Clique em **Deploy**.

## 3) Deploy automático

Depois que o projeto estiver importado:

- Cada `git push` na branch principal gera novo deploy automático.
- Pull Requests também podem gerar Preview Deploys.

## 4) Ativar domínio gratuito

A Vercel já fornece um domínio gratuito no formato:

```txt
seu-projeto.vercel.app
```

Para ajustar:

1. Projeto na Vercel → **Settings** → **Domains**.
2. Confirme ou personalize o subdomínio `*.vercel.app`.
3. Salve e aguarde propagação (normalmente rápida).

Exemplo de domínio final:

```txt
seu-repo-ou-projeto.vercel.app
```

Se quiser trocar para um nome específico, use **Domains** e edite o subdomínio disponível.

## Publicação concluída ✅

Com isso você terá:
- Código versionado no GitHub
- Integração com Vercel
- Deploy automático ativo
- Domínio gratuito `vercel.app` funcionando

# Developer-Portfolio-Landing-Page
