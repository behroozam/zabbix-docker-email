# docker-compose zabbix email notification container setting 
i use this image [catatnight/postfix](https://hub.docker.com/r/catatnight/postfix/) for postfix as mailserver
you need just change `maildomain` and `smtp_user` and in mediatype settings zabbix set smtp server `postfix`
and in authentication type your username and password .
i use mysql ubuntu version you can just copy and paste postfix section on your `docker-compose.yml` file
