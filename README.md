# Assistente Virtual de Saúde — UBS (site estático)

Este é um site **single-page** que implementa um fluxo de triagem simples (baseado no PDF fornecido) para:
- Problemas nos rins (litíase)
- Diabetes (hipoglicemia)
- Acidentes com animais peçonhentos

Principais características:
- 100% cliente — não requer servidor, Node.js ou VPS.
- Botão **📞 Ligar 192 (SAMU)** aparece automaticamente em casos classificados como emergência e também há um botão flutuante para ligar rapidamente.
- Pronto para deploy em **GitHub Pages / Netlify / Cloudflare Pages**.

## Como usar
1. Baixe e extraia os arquivos.
2. Coloque os arquivos em um repositório GitHub ou suba para Netlify/Cloudflare Pages.
3. Para GitHub Pages: crie um repositório, adicione `index.html` no branch `main` e ative Pages.

## Observações e melhorias
- Adicionar gravação de conversas (Google Sheets / Airtable) caso deseje armazenar históricos.
- Substituir os textos por versões oficiais / revisar conteúdo médico com equipe responsável.
