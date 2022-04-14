Este commit es origen.
Se puede realizar un commit con "git commit -m(mensaje) 'Texto'".

Se puede clonar con "git clone [url-del-repositorio]".

Se puede agregar un repositorio remoto con "git remote add [nombre] [url]".

Se puede traer informacion del repositorio remoto con "git fetch [nombre-del-remoto]"
Se puede traer información del repositorio remoto y combinarlo con lo local con "git pull [nombre-del-remoto]".

No se puede hacer push si se han hecho cambios al repositorio remoto, primero se debe hacer un fetch o pull y luego push.

Se puede añadir los cambios al repositorio remoto con "git push [nombre-remoto] [nombre-rama]" - git push origin master usualmente.

Si se realiza un cambio al repositorio remoto y se quiere hacer un push desde una máquina propia. Primero, realiza un git pull para poder traer los cambios hechos en el repositorio remoto y combinarlo con tus cambios. Luego hacer un 'git add .' para añadir los cambios del repo remoto a tu repo local. Finalmente, realizar el commit y push de manera normal.

Mensaje final
Prueba final