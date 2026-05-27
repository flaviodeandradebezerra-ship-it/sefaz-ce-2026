# SEFAZ/CE 2026 – Deploy Guide

## Opção 1: Vercel (Recomendado – 2 minutos)
1. Acesse https://vercel.com e crie conta gratuita
2. Clique em "Add New Project" → "Deploy without Git"
3. Arraste a pasta `dist/` ou o arquivo `.zip` para a área de upload
4. Clique "Deploy" → URL pública gerada automaticamente

## Opção 2: Netlify Drop (Mais rápido – sem conta)
1. Acesse https://app.netlify.com/drop
2. Arraste a pasta `dist/` diretamente para a página
3. URL pública gerada em segundos (ex: https://abc123.netlify.app)

## Opção 3: GitHub Pages (Permanente – gratuito)
1. Crie repositório no GitHub (pode ser privado ou público)
2. Faça upload de todos os arquivos desta pasta
3. Em Settings → Pages → Source: "Deploy from branch: main"
4. URL: https://seu-usuario.github.io/nome-do-repo

## Opção 4: Arquivo Local (Offline)
- Abra o arquivo `sefaz-ce-2026-standalone.html` diretamente no navegador
- Funciona 100% offline, sem servidor
