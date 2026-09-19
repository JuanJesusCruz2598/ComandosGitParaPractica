git init = initialize project to use git - inicializa un proyecto git
git add [filename || . (all)] = add changes "." is all changes - Con "." añade todo el contenido con los cambios realizados, si hay varios archivos y hay alguno que no es necesario se especifica , ej: git add [archivo1] [archivo2]
git commit -m "message" = save changes with a message / guarda los cambios con un mensaje.
git pull [origin] [branchname] = get latest changes - Obtiene los últimos cambios del branch
git push [origin] [branchname] = publish changes to repo - Publica los cambios al repositorio
git checkout -b new_branch = create a new Branch - Crea una nueva rama del Branch principal
git checkout branch_name / git switch "branchname"= change active Branch - Cambias de Branch.
git status = check status of changes - Te dice los cambios a aplicar al branch
git log = see all previous saved changes - Te dice el historial de cambios del Branch en este caso todo el proyecto.
git checkout commit id = travel back to old commit - Te lleva al commit anterior.
git merge "nombre del branch" = junta el contenido del Branch con el Branch activo actualmente. 
git rebase = aplica los cambios echos del branch secundario al branch principal y empieza desde el ultimo commit del branch principal
git fetch = te trae los cambios del branch pero no los aplica ,para aplicarlos ,usa git merge

========COSAS UTILES========

git stash -u = hace un guardado sucio de lo que tienes sin terminar para empezar otra modificación.
git diff = enseña las diferencias entre archivo
git stash pop recuperas el stash anterior

=============================
mirar luego como vincular git con github
<<<<<<< HEAD
patata.
=======
mirar luego como vincular git con gitlab
>>>>>>> ramasecundaria
