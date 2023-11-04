# Hyperblog


# Comandos útiles para colaborar en proyectos grandes en GitHub

A continuación, se presentan algunos comandos de Git que pueden resultar útiles cuando colaboras en proyectos de GitHub de gran tamaño:

| Comando                            | Descripción                                                                |
| ---------------------------------- | -------------------------------------------------------------------------- |
| `git log --oneline`                | Muestra el ID del commit y el título del commit.                         |
| `git log --decorate`               | Muestra la ubicación del puntero HEAD en el registro.                   |
| `git log --stat`                   | Brinda una breve explicación del número de líneas cambiadas.             |
| `git log -p`                       | Muestra el número de líneas cambiadas y el contenido del cambio.        |
| `git shortlog`                     | Lista los commits realizados por los usuarios con su nombre y títulos.   |
| `git log --graph --oneline --decorate` | Visualiza el registro de forma gráfica con adornos.                   |
| `git log --pretty=format:"%cn hizo un commit %h el día %cd"` | Permite personalizar el formato de salida del registro. |
| `git log -3`                       | Limita la salida a los últimos 3 commits.                                |
| `git log --after="2018-01-02"`     | `git log --after="today"` y `git log --after="2018-01-02" --before="today"` | Filtra los commits por fechas.             |
| `git log --author="Nombre del Autor"` | Muestra los commits realizados por un autor específico.                 |
| `git log --grep="INVIE"`            | Busca commits que coincidan exactamente con el mensaje proporcionado.  |
| `git log --grep="INVIE" -i`         | Busca commits sin importar mayúsculas o minúsculas en el mensaje.        |
| `git log archivo.html`              | Busca commits relacionados con un archivo específico.                   |
| `git log -S "Por contenido"`        | Busca commits con un contenido específico dentro de los archivos.       |
| `git log > log.txt`                | Guarda la salida del registro en un archivo de texto llamado `log.txt`.  |




