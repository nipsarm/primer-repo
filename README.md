primer-repo
===========

repositorio de prácticas

Comandos para configurar  Git:
 git config --global user.name "nipsarm"
 git config --global user.email "nip2712@gmail.com"

Generar la Public Key:
 ssh-keygen

Leyendo la Public Key para copiarla a GitHub:
 cat ~/.ssh/X552E.pub

Arrancando el repo Local:
	git init
	touch README2
	git add README2
	git commit -m "comentario"
	git push origin master  //enviar a carpeta de origen - master
