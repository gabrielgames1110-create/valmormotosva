# Site Valmor Motos — como publicar no GitHub Pages

Esta pasta tem menos de 100 arquivos, então dá para enviar tudo de uma vez pelo site do GitHub.

## O que tem aqui

- `index.html`: o site.
- `Logo Valmor.dc.html`: a logo animada do topo.
- `support.js`: o código que monta a página no navegador.
- `ds/`: estilos do site.
- `assets/`: partes da logo, fotos dos veículos e logos das marcas.

Não renomeie nem mova nada. O GitHub diferencia maiúsculas de minúsculas nos nomes.

## Passo a passo

1. Crie um repositório público no GitHub, por exemplo `valmor-motos`.
2. Na página do repositório, clique em **uploading an existing file** (ou **Add file → Upload files**).
3. Abra esta pasta no computador, selecione **tudo o que está dentro dela** e **arraste** para a área de upload. O botão "choose your files" não envia pastas.
4. Espere a lista terminar de carregar e confira se aparecem as pastas `assets` e `ds`. Clique em **Commit changes**.
5. Vá em **Settings → Pages**. Em **Source**, escolha **Deploy from a branch**; em **Branch**, escolha `main` e `/ (root)`. Clique em **Save**.
6. Em 1 a 3 minutos o endereço aparece nessa mesma tela: `https://SEU-USUARIO.github.io/valmor-motos/`.

## Atualizar depois

Envie os arquivos novos pelo mesmo caminho. Arquivos com o mesmo nome são substituídos e o site atualiza em alguns minutos.
