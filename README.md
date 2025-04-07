# Actividad de Repaso: Uso de GitHub con Visual Studio Code y Git Bash
    Objetivo:
Repasar y reforzar el uso de Git y GitHub desde Visual Studio Code y la terminal Git Bash, para gestionar proyectos de forma colaborativa y profesional.

     Herramientas necesarias:
Visual Studio Code instalado

Git Bash instalado

Cuenta activa en GitHub

Acceso a internet

📝 Pasos de la actividad:
Clonar un repositorio existente desde GitHub:

Abre Git Bash.

Usa el comando:

bash
Copiar
Editar
git clone https://github.com/usuario/repo-ejemplo.git
Entra al directorio del repositorio:

bash
Copiar
Editar
cd repo-ejemplo
Abrir el proyecto en Visual Studio Code:

Desde Git Bash, escribe:

bash
Copiar
Editar
code .
Esto abrirá el repositorio en VS Code.

Realizar cambios en el código:

Edita uno o más archivos dentro del repositorio (puede ser un archivo README.md o un archivo .html/.js/.py, etc.).

Guarda los cambios.

Registrar los cambios con Git:

En Git Bash, verifica los archivos modificados:

bash
Copiar
Editar
git status
Añade los cambios al área de preparación:

bash
Copiar
Editar
git add .
Crea un commit describiendo el cambio:

bash
Copiar
Editar
git commit -m "Descripción clara del cambio realizado"
Enviar los cambios al repositorio remoto en GitHub:

Asegúrate de estar en la rama principal (por ejemplo, main):

bash
Copiar
Editar
git branch
Sube los cambios:

bash
Copiar
Editar
git push origin main
Verifica en GitHub:

Abre tu navegador y revisa que los cambios hayan sido actualizados en el repositorio remoto.