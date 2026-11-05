# Meu Projeto Fitness 2026 — como instalar no celular

Arquivos: index.html, manifest.json, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png (todos na MESMA pasta).

## 1. Publicar grátis (obrigatório para instalar como app)
O instalador de app (PWA) só funciona em endereço https. Escolha UMA opção:

**Opção mais fácil — Netlify Drop (sem cadastro de código)**
1. Acesse app.netlify.com/drop pelo computador.
2. Arraste a pasta `meu-projeto-fitness` inteira para a tela.
3. Ele gera um link https (ex.: https://nome-aleatorio.netlify.app). Guarde esse link.

**Alternativa — GitHub Pages**
1. Crie conta em github.com e um repositório público novo.
2. Envie todos os arquivos (Add file > Upload files).
3. Settings > Pages > Branch: main > Save. O link aparece em 1–2 minutos.

## 2. Instalar no iPhone (use o Safari)
1. Abra o link no **Safari** (não funciona pelo Chrome do iPhone).
2. Toque em **Compartilhar** (quadrado com seta).
3. Role e toque em **Adicionar à Tela de Início** > **Adicionar**.
4. Abra pelo ícone: abre em tela cheia e funciona offline.

## 3. Instalar no Android (Chrome)
1. Abra o link no **Chrome**.
2. Toque nos três pontinhos (⋮) > **Instalar app** (ou "Adicionar à tela inicial").
3. Confirme. O ícone aparece na tela inicial.

## Dicas
- Abra o app uma vez com internet; depois funciona offline.
- Os dados ficam salvos no aparelho (não vão para a nuvem). Não limpe os dados do navegador.
- Para trocar treinos: edite o bloco `W` no começo do script do index.html. Para trocar dias: edite `P` (0=dom ... 6=sáb).
- Depois de atualizar arquivos, mude `fitness2026-v1` para `v2` no sw.js para o celular baixar a versão nova.
