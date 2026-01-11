# Creando un nuevo repositorio

## Repositorio local (en mi computador)

1. `git init` para inicializar repositorio
2. `git add .` o `git add <nombre-archivo>` para agregar cambios al área de preparación
3. `git commit -m "mensaje descriptivo"` para guardar (confirmar) los cambios en el historial del repositorio

## Repositorio remoto (en GitHub)

1. `git push origin main` o `git push <repositorio-remoto> <rama-para-enviar>` envía los cambios desde el repositorio local al remoto

## Qué pasa si me arrepiento? Opción 1

1. `git checkout -- <nombre-archivo-a-restaurar>` Descarta los cambios hechos en un archivo del directorio de trabajo y lo dgit evuelve al estado extacto del último commit
2. `git log` muestra historial completo de commits
3. `git log --oneline` Entrega detalle compacto del historial de commits

## Qué pasa si me arrepiento? Opción 2

1. `git restore <nombre-archivo>`
