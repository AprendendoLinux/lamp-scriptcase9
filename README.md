## Webserver apache/php as aplicações desenvolvidas com o ScriptCase 9

Esse projeto contém um webserver leve e robusto para para rodar as aplicações desenvolvidas com o [ScriptCase 9](https://www.dokuwiki.org/dokuwiki).

## Subindo o contêiner:

    docker run -d --name='lamp-scriptcase' \
	    --hostname='lamp-scriptcase' \
	    -v lamp-scriptcase:/var/www/html \
	    -p 80:80 \
	--restart=always aprendendolinux/lamp-scriptcase9:tag

Se tiver qualquer dúvida, acesse meu site:

[https://www.henrique.tec.br](https://www.henrique.tec.br)

Atenciosamente,

**Henrique Fagundes** \
Analista de Suporte Gnu/Linux
