primer-repo
===========

repositorio de prácticas

Comandos para configurar  Git:

	git config --global user.name "nipsarm"
 	git config --global user.email "nip2712@gmail.com"

Generar la Public Key, colocar nombre y guardar en carpeta /home/user/.ssh

 	ssh-keygen

Leyendo la Public Key para copiarla a GitHub:

 	cat ~/.ssh/X552E.pub  //copiar Key a sección añadir SSH-key en github.com

Arrancando el repo Local:

	git init

	git status //verifica estado actual del repositorio local

	touch README2

	git add README2

	git commit -m "comentario"

	git push origin master  //enviar a carpeta de origen - master

Añadir repositorio remoto

	git remote add origin git@github.com:nipsarm/primer-repo.git
	
Descargando archivos de repos remotos, mover a carpeta donde se guardarán y usar:

	git pull origin master
	origin, puede ser cualquier nombre asignado para la URL
	master, solicita la descarga de los archivos en la rama master

Para remover un server remoto:

	git remote remove [nombre asignado para server]
