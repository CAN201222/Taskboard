Taskboard 



Taskboard es una agenda colaborativa tipo SCRUM que permite organizar tareas, equipos y flujos de trabajo de forma visual y eficiente. Está construida como un monorepo con frontend en Angular y backend en Django + PostgreSQL.





Estructura del proyecto

taskboard/ ├── frontend/        Aplicación Angular (mi-app) ├── backend/         API REST en Django └── .gitignore  Ignora archivos innecesarios





Tecnologías utilizadas



Frontend: Angular, TypeScript, SCSS

Backend\*\*: Django, Django REST Framework

Base de datos: PostgreSQL

Otros: PowerShell (automatización), Git (versionado)



---



Instalación



1\. Clonar el repositorio

```bash

git clone https://github.com/CAN201222/Taskboard.git

cd Taskboard



2\. Instalar dependencias del frontend



cd frontend/mi-app

npm install

ng serve



3.configurar el backend 

cd ../../backend

python -m venv .venv

source .venv/Scripts/activate  # En Windows

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver



Modelo entidad-relación

El backend está diseñado con un modelo ER normalizado para tareas, usuarios, etiquetas y estados SCRUM. Ideal para escalar y mantener integridad de datos.



Licencia

MIT © Felipe CAN201222





