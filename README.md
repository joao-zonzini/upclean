# upclean 

Nas linhas 14 e 16 do código você deve mudar onde você quer salvar o log das atualizações.

Sugiro colocar essa programa na pasta ```~/bin``` e configurar o crontab:

```shell 

$ crontab -e

```

e colocar o comando para rodar a cada meia hora assim:

```shell

*/30 * * * * /home/nome_do_usuario/bin/upclean

```

Alguns sistemas precisam que esse cron seja do usuário root pelos sudos no script.
