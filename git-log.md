### Git log
Muestra el historial de commits.

`git log --pretty=format:"%h - %an, %ar : %s"`
Muestra el historial con el formato que indicamos.

### Limitar la salida del historial
`git log -n`: Cambiabos la n por un número, el cuál mostrará n commit más recientes.

`git log --after="2016-04-08 00:00:00"`:Muestra los commits realizados después de la fecha especificada.

`git log --before="2016-04-08 00:00:00`:Muestra los commits realizados antes de la fecha especificada.

Las banderas del comando `git log` se pueden usar juntas según nos convenga, por ejemplo: 
`git log --after="2016-04-07 12:00:00" --before="2016-04-07 12:30:00"`