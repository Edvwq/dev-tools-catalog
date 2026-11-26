# Git Tips

## Comandos esenciales

- `git switch -c feat/nueva-rama`: crear y cambiar de rama.
- `git status`: ver el estado del arbol de trabajo.
- `git log --oneline --graph --all`: visualizar el historial.
- `git fetch upstream`: traer cambios sin fusionar.
- `git merge upstream/main`: integrar cambios.
- `git branch -d rama`: eliminar una rama ya fusionada.

## Buenas practicas

1. Nunca trabajar directamente en `main`.
2. Usar mensajes de commit semanticos.
3. Mantener commits pequenos y atomicos.
