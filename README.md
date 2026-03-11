# VidYou IPTV - Painel de Controle

Este é o emissor central do ecossistema **VidYou IPTV**. Através deste painel, o administrador pode atualizar a grade de canais de todos os usuários conectados em tempo real.

## 🛠 Como Funciona
O painel utiliza a API REST do GitHub para sobrescrever o arquivo `lista.txt` no repositório principal do aplicativo. 

1. O administrador cola a lista M3U no campo de texto.
2. O sistema solicita o **Token de Acesso** e o **Caminho do Repositório**.
3. Ao clicar em atualizar, o arquivo é enviado e a mudança é propagada para todos os usuários do app automaticamente.

## ⚙️ Configuração Necessária

Para utilizar este painel, você precisará de:

1. **GitHub Personal Access Token (PAT):**
   - Vá em `Settings > Developer Settings > Personal Access Tokens > Tokens (classic)`.
   - Gere um novo token com a permissão **'repo'** marcada.
   - *Importante: Nunca compartilhe este token com ninguém.*

2. **Caminho do Repositório:**
   - O formato deve ser `seu-usuario/nome-do-repositorio-do-app`.
   - Exemplo: `roneiltonsouza/vidyou-iptv`.

## 🔐 Segurança
- O painel não armazena o seu Token de forma permanente por questões de segurança.
- A comunicação é feita diretamente entre o seu navegador e os servidores do GitHub via HTTPS.
- Recomendamos manter este repositório privado ou não divulgar a URL pública do painel.

## 🚀 Fluxo de Sincronização
Painel (Browser) ➔ GitHub API ➔ Repositório (lista.txt) ➔ Usuários (VidYou App)

---
*Gerenciador exclusivo para a plataforma VidYou IPTV.*
