<img align="right" alt="RSS Logo" width="30%" height="auto" src="https://rss.com/blog/wp-content/uploads/2019/10/social_style_3_rss-512-1.png">

# RSS2inTG

Envio automático de feed RSS para pessoa, canal ou grupo no Telegram.

## Configuração:

Defina as variáveis abaixo na aba `Secrets` do repositório:

`BOT_TOKEN`: Insira o token do bot que enviará as mensagens ([@BotFather](https://t.me/BotFather));

`DESTINATION`: Destinos das mensagens separados por vírgulas e sem espaço após a vírgula (`@destino` ou ID);

`URL`: Endereços de feeds RSS separados por vírgulas e sem espaço após a vírgula;

## Uso

A ação irá buscar as atualizações a cada 15 minutos conforme definido no arquivo [cron.yml](.github/workflows/cron.yml).
