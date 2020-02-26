# Repositorio de prueba
Este es un repositorio de prueba para realizar commits simples.

## Instrucciones básicas de uso
Todos los comandos de [Git](https://git-scm.com) son antecedidos por el comando `git` escrito en la consola o terminal.

### Comandos básicos
#### Inicializar u obtener repositorios
- `clone`: Descarga un repositorio remoto en el equipo local. Útil para descargar un proyecto que ha sido inciado (y probablemente trabajado).
- `init`: Inicializa un nuevo repositorio en el equipo local. Útil para iniciar un proyecto de manera local que después puede ser subido a un repositorio remoto.

#### Operación con repositorios
- `status`: Visualiza los archivos que han sido cambiados, tanto los que se encuentran fuera como dentro del índice.
- `add`: Agrega los archivos que han sufrido cambios al índice.
- `commit`: Registra los cambios que fueron agregados al índice. Crea marcas en el tiempo.
- `log`: Visualiza el historial de los cambios registrados.
- `branch`: Utilizado para ver y administrar las ramas del repositorio.
- `checkout`: El primer uso es realizar el cambio entre las ramas del repositorio. El segundo uso es para poder regresar el repositorio an un estado (commit) anterior; el regreso no significa la pérdida de cambios posteriores al punto al que se regresó.
- `merge`: Mezcla los cambios (cuando es posible) entre ramas.
- `push`: Sube los cambios a un repositorio remoto.
- `pull`: Este comando es la mezcla de los comandos `fetch` y `merge`. Es utilizado para descargar los cambios de un repositorio remoto, y mezclarlos (si es posible) con los cambios registrados de manera local.
