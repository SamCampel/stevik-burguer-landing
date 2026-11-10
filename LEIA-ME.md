# Stevik Burger – site estático (Vercel)

Sem build. Basta publicar esta pasta.

## Publicar
1. Painel: vercel.com/new → importar o repositório (ou arrastar a pasta) → Framework Preset: **Other**, Build Command e Output Directory em branco.
2. CLI: `npm i -g vercel && vercel --prod` dentro desta pasta.

## Antes de publicar de verdade
- Trocar `DOMINIO-A-DEFINIR` em `index.html` (canonical, og:url, og:image, JSON-LD) pelo domínio final. Ex.: `sed -i 's/DOMINIO-A-DEFINIR/stevikburger.com.br/g' index.html`
- Depois do domínio: adicionar `Sitemap: https://SEU-DOMINIO/sitemap.xml` ao robots.txt (opcional, é uma página só).
- Itens pendentes marcados no HTML: endereço completo, descrição do Velho Oeste e do Cabra do Rancho, logo/fotos originais.
