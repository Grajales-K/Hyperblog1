# Hyperblog



# Helpful Commands for Collaborating on Large GitHub Projects

Below are some Git commands that can prove useful when collaborating on GitHub projects of significant size:

| Command                            | Description                                                                   |
| ---------------------------------- | ----------------------------------------------------------------------------- |
| `git log --oneline`                | Displays the commit ID and commit title.                                    |
| `git log --decorate`               | Shows where the HEAD pointer is located in the log.                         |
| `git log --stat`                   | Provides a brief explanation of the number of changed lines.                |
| `git log -p`                       | Shows the number of changed lines and the content of the changes.           |
| `git shortlog`                     | Lists commits made by users with their names and commit titles.             |
| `git log --graph --oneline --decorate` | Visualizes the log graphically with decorations.                      |
| `git log --pretty=format:"%cn made a commit %h on %cd"` | Allows custom formatting of commit messages.         |
| `git log -3`                       | Limits the output to the last 3 commits.                                     |
| `git log --after="2018-01-02"`     | `git log --after="today"` and `git log --after="2018-01-02" --before="today"` | Filters commits by dates.               |
| `git log --author="Author Name"`    | Shows commits made by a specific author.                                    |
| `git log --grep="KEYWORD"`         | Searches for commits with an exact match to the provided message.          |
| `git log --grep="KEYWORD" -i`      | Searches for commits regardless of case sensitivity in the message.         |
| `git log file.html`                | Searches for commits related to a specific file.                            |
| `git log -S "By content"`          | Searches for commits with specific content within files.                   |
| `git log > log.txt`                | Saves the log output to a text file named `log.txt`.                        |


---

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







