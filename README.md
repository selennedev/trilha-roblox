# Trilha Roblox Generalista

Trilha de estudo em 11 paradas para virar Roblox game developer generalista, com checklist de progresso. É uma página estática (um único `index.html`), sem build e sem dependências.

O progresso fica salvo no navegador de quem abre a página (localStorage).

## Como publicar no GitHub Pages

1. No GitHub, crie um repositório novo (por exemplo `trilha-roblox`).
2. Envie os arquivos desta pasta para a raiz do repositório.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
5. Aguarde cerca de um minuto. O site fica em `https://carolvilarinhodev.github.io/trilha-roblox/`.

## Editar o conteúdo

Os blocos, módulos e itens ficam nos arrays `STOPS` e `PARALLEL`, dentro do `<script>` no fim do `index.html`. Para adicionar um item, inclua o texto na lista `items` do módulo.

Se você mudar o nome de um item ou a ordem dos itens, o progresso já salvo no navegador pode apontar para o item errado, porque cada checkbox é identificado pela posição.
