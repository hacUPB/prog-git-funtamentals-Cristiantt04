## Archivo **.gitignore**

### Un .gitignore es un archivo de texto que le indica a Git qué archivos o directorios no deben rastrearse (no se añaden al índice ni se suben al repositorio). Se usa para mantener el repositorio limpio, seguro y ligero, evitando incluir artefactos generados, archivos temporales o credenciales.
##

### ¿Para qué se utiliza? ###


Evitar ruido en los commits
Excluye archivos que cambian con frecuencia o se generan automáticamente (por ejemplo, compilados, binarios, node_modules/, dist/, __pycache__/).


Reducir el tamaño del repo
No versionar dependencias descargables o artefactos pesados.


Proteger información sensible
Evitar que se suban claves, tokens, certificados o configuraciones locales como .env, *.pem, local.settings.json.


Facilitar la colaboración
Todos en el equipo comparten las mismas reglas de exclusión, con un comportamiento consistente.