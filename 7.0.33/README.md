## Webserver apache/php-7.0.33 as aplicações desenvolvidas com o ScriptCase 9

Esse projeto contém um webserver leve e robusto para para rodar as aplicações desenvolvidas com o [ScriptCase 9](https://www.dokuwiki.org/dokuwiki).

## Subindo o contêiner:

    docker run -d --name='lamp-scriptcase' \
	    --hostname='lamp-scriptcase' \
	    -v lamp-scriptcase:/var/www/html \
	    -p 80:80 \
	--restart=always aprendendolinux/lamp-scriptcase9:7.0.33

Caso prefira, você pode usar o Docker Composer com o arquivo [docker-compose.yml](https://github.com/AprendendoLinux/lamp-scriptcase9/blob/main/7.0.33/docker-compose.yml).

Se tiver qualquer dúvida, acesse meu site:

[https://www.henrique.tec.br](https://www.henrique.tec.br)

Atenciosamente,

**Henrique Fagundes** \
Analista de Suporte Gnu/Linux
