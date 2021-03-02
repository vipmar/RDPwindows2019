# VPS_RDP_Windows


- Especificações: CPU VPS 2 Core - 7 GB de RAM
- Duração: 6 horas
- SO: Windows 10 - Server 2019


# Etapa usando VPS:

- Faça login / crie sua conta Ngrok em https://dashboard.ngrok.com/
- Se você clicou em Configurações> Segredos> Novo segredo de repositório, crie-o com o nome NGROK_AUTH_TOKEN, para o valor cole seu token NGROK
- Clique em Adicionar segredos
- Em seguida, clique em Ação> CI> Executar fluxo de trabalho e, em seguida, clique em CI> construir
- Espere até que o processo de criação do VPS seja concluído, então o IP, nome de usuário e senha irão aparecer

# Observação

- Se o IP não sair, tente usar outro TOKEN ou não use um token ao mesmo tempo
- Se você deseja usar vários VPS, então use um TOKEN diferente, é recomendado criar uma conta NGROK com um e-mail temporário (https://emailfake.com/)