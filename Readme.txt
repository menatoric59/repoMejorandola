Hola mundo

Esta es una documentación mas amplia, y avance.

Principales comandos de Git

********************************************************************
/*  Configurando Git en tu PC
********************************************************************
git config --global 



********************************************************************
/*  Inicializar repositorios y uso general
********************************************************************
git init (inicia el rastreo de cambios en la carpeta donde estes posisionado)
git add -A (agrega todos los archivos en el área de )
git commit -m (sube los cambios a git y permite agregar comentarios)
git commit -am (resumes git add -A y git commit -m)
git log (permite ver el log de commits hechos, el último arriba)
git log > archivo.txt (exporta el log de commits a un txt)


********************************************************************
/* Uso de ramas (BRANCHES)
********************************************************************
git branch (lista las ramas existentes)
git branch - a (muestra todas las ramas, incluyendo la oculta origin-mater)
git merge [ramaExterna](fusionamos la rama externa a la rama activa)


********************************************************************
/* Comandos para REMOTO
********************************************************************
git remote add origin https://github.com/menatoric59/repoMejorandola.git

* origin = se configura que origin sea  https://github... 

git remote -v (listando enlaces de repositorios)

git push origin master (empujar los commits locales al repositorio remoto
los parámetros son: origin y rama a empujar)

git fetch origin (sincroniza la informacion del origin a la rama oculta origin-master)