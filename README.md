Proyecto Web - Gestión con Git
Este proyecto consiste en una página web estática desarrollada con HTML y CSS. Su objetivo es practicar la gestión de versiones utilizando Git y GitHub.
Tecnologías Utilizadas
HTML
CSS
Git & GitHub
Pasos para la Instalación y Uso
Clonar el repositorio desde GitHub:
git clone https://github.com/TU_USUARIO/mi_proyecto_web.git
Acceder a la carpeta del proyecto:
cd mi_proyecto_web
Abrir el archivo index.html en un navegador web para visualizar la página.
Control de Versiones con Git
1. Inicializar el repositorio
git init
2. Agregar archivos al área de preparación
git add .
3. Guardar los cambios en el repositorio
git commit -m "Primer commit: Estructura base del proyecto"
4. Subir el proyecto a GitHub
git remote add origin https://github.com/TU_USUARIO/mi_proyecto_web.git
git branch -M main
git push -u origin main
5. Crear una nueva rama para estilos CSS
git checkout -b css
6. Fusionar los cambios de la rama css a la rama principal
git checkout main
git merge css



