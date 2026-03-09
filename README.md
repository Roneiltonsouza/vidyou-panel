# Painel VidYou

O **Painel VidYou** é o gerenciador de listas IPTV para o player **VidYou**. Este painel permite que você salve, organize e envie links M3U diretamente para o seu player através de um botão de sincronização "mágico".

## Funcionalidades
- **Gerenciador de Listas:** Salve múltiplos links de listas M3U com nomes personalizados.
- **Sincronização Direta:** Botão de sincronização que envia a lista escolhida diretamente para o seu app VidYou.
- **Persistência:** As listas ficam salvas no seu navegador (via LocalStorage), garantindo que nada se perca ao fechar o app.
- **Interface Minimalista:** Design otimizado para facilitar o gerenciamento de conteúdo.

## Como utilizar
1. **Adicionar Lista:** Insira o nome da lista e o link da URL M3U nos campos indicados e clique em "Salvar no Painel".
2. **Sincronizar:** Clique no botão "SINCRONIZAR" ao lado da lista desejada para abrir o seu player VidYou já carregando o conteúdo.
3. **Gerenciar:** Você pode excluir qualquer lista salva clicando no botão "X" vermelho.

## Configuração
Para que a sincronização funcione corretamente, certifique-se de que o caminho `urlVidYou` dentro do script do Painel esteja apontando para o arquivo `index.html` do seu player VidYou.

---
*Projeto desenvolvido para otimizar o gerenciamento de conteúdo P2P.*
