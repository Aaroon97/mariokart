# Mario Kart Championship — Instrucciones para Claude

## Deploy automático obligatorio

Al terminar **cualquier tarea** que modifique archivos del proyecto, ejecutar siempre estos tres comandos en orden, sin pedirle confirmación al usuario:

```
git add .
git commit -m "actualizacion automatica"
git push
```

Esto se aplica a toda modificación de código, contenido o configuración. Si `git commit` falla porque no hay cambios, no es un error — simplemente continuar.
