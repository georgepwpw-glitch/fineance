# Cofre — App de Finanças Pessoais

App offline e privado. Todos os dados ficam no seu aparelho (localStorage).

## Como hospedar no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `cofre`). Pode ser público.
2. Faça upload de TODOS estes arquivos na raiz do repositório:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. No repositório, vá em **Settings → Pages**.
4. Em "Source", escolha a branch `main` e a pasta `/ (root)`. Salve.
5. Aguarde ~1 minuto. O GitHub mostra o endereço (algo como `https://seu-usuario.github.io/cofre/`).
6. Abra esse endereço no celular.

## Como instalar no celular (tela inicial)

- **iPhone (Safari):** abra o site → botão Compartilhar → "Adicionar à Tela de Início".
- **Android (Chrome):** abra o site → menu (⋮) → "Adicionar à tela inicial" / "Instalar app".

Depois de instalado, funciona offline e abre como um app normal.

## Importante sobre seus dados

- Os dados ficam SÓ no navegador/app daquele aparelho. Não sincroniza entre dispositivos.
- Para backup: use "Mais → Exportar para o Claude" e guarde o texto.
- A entrada por voz precisa de internet (usa o reconhecimento do próprio celular).
- O resto funciona 100% offline.

## Arquivos

- `index.html` — o app inteiro (HTML+CSS+JS embutidos)
- `manifest.json` — define nome, ícone e comportamento de PWA
- `sw.js` — service worker (cache offline)
- `icon-192.png` / `icon-512.png` — ícones do app
