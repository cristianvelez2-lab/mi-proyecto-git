# Mi Proyecto
Proyecto de practica para aprender Git y GitHub.
## Instalacion
Clonar el repositorio con git clone.

## Comandos que usé

- `git init`: convierte una carpeta normal en un repositorio; crea la carpeta oculta .git donde se guarda todo el historial.
- `git status`: muestra en qué estado están los archivos: sin seguimiento, modificados o listos para el commit.
- `git add`: pasa los cambios al staging, que es la lista de lo que va a entrar en el próximo commit.
- `git commit`: guarda una "foto" de lo que hay en staging, con un mensaje que describe el cambio.
- `git push`: sube los commits de mi computador al repositorio en GitHub.
- `git diff`: muestra línea por línea qué cambió respecto al último commit.
- `git log`: muestra el historial de commits; con --oneline --graph sale resumido.
- `git restore`: descarta los cambios de un archivo que no tienen commit; con --staged solo lo saca del staging sin borrar el cambio.
- `git reset --soft HEAD~1`: deshace el último commit, pero deja los cambios listos para volver a confirmarlos.
- `git checkout <hash> -- archivo`: devuelve un archivo a como estaba en un commit anterior.
