# Publicar o Diário de Treino no GitHub Pages

1. Crie uma conta gratuita em github.com (se ainda não tiver).
2. Clique em **+ → New repository**. Nome: `diario-de-treino`. Marque **Public**. Clique em **Create repository**.
3. Na página do repositório, clique em **uploading an existing file** (ou **Add file → Upload files**).
4. Descompacte o zip e arraste os 6 arquivos (não a pasta) para a página: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` e `icon-maskable-512.png`. Clique em **Commit changes**.
5. Vá em **Settings → Pages**. Em *Build and deployment*, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)**, e clique em **Save**.
6. Aguarde 1 a 2 minutos e recarregue a página. O endereço aparece no topo: `https://SEU-USUARIO.github.io/diario-de-treino/`.
7. No Chrome do Android, abra o endereço, toque em ⋮ e escolha **Instalar app** (ou **Adicionar à tela inicial**).

## Atualizar depois
Envie os arquivos novos pelo mesmo caminho (Add file → Upload files, substituindo os antigos). Se mudar o `index.html`, troque `diario-v1` por `diario-v2` no `sw.js`, para o celular baixar a versão nova.

## Dados
Ficam salvos no aparelho, no navegador onde o app foi instalado. Limpar os dados do Chrome ou desinstalar o app apaga o histórico. Use o campo de backup na aba Ano de vez em quando.
