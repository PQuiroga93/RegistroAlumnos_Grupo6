📚 Registro Académico — CodeIgniter 4 + MySQL
Proyecto académico de la Tecnicatura en Ciencia de Datos e Inteligencia Artificial (ISFDyT N°57).
El objetivo es migrar una aplicación front-end a un stack CodeIgniter 4 + MySQL, aplicando prácticas ágiles, control de versiones con GitHub y documentación profesional.

🚀 Objetivo del proyecto
Implementar un CRUD completo de Carreras, Alumnos, Cursos e Inscripciones.
Integrar la base de datos universidad en MySQL.
Garantizar seguridad básica (CSRF, validaciones, sesiones).
Aplicar Scrum/Kanban en la organización del equipo.
Entregar un MVP funcional con demo al cliente (docente).
👥 Equipo
Project Manager (PM): Marcelo Pérez
QA/Tester: Pamela Quiroga
Frontend Developer: Tiago Maidana
Backend Developers: Gladys González & Juan Lacoumette
🛠️ Tecnologías
Backend: PHP 8.x — CodeIgniter 4 (MVC)
Base de datos: MySQL / MariaDB
Frontend: HTML, CSS, JS (migrado a vistas CI4)
Control de versiones: GitHub (Issues, Projects, CI/CD con GitHub Actions)
Testing: PHPUnit + QA manual
📂 Estructura del repositorio
Code
/
├── api/                 # Lógica de la API y backend (CodeIgniter 4)
├── front/               # Vistas y archivos del frontend (HTML, CSS, JS)
├── .vs/                 # Archivos de configuración de Visual Studio (opcional)
├── CODE_OF_CONDUCT.md   # Código de conducta del proyecto
├── LICENSE              # Licencia del repositorio
├── readme.md            # Documentación principal del proyecto
├── readmetp1            # Documentación adicional de la práctica profesional
⚙️ Instalación y ejecución
Clona el repositorio

bash
git clone https://github.com/PQuiroga93/registroalumnos_Gladys.git
Instala dependencias

Asegúrate de tener PHP 8.x y Composer instalados.
Instala dependencias de CodeIgniter:
bash
composer install
Configura la base de datos

Crea una base de datos universidad en MySQL.
Actualiza el archivo .env con tus credenciales de conexión.
Migraciones y seeders

Ejecuta las migraciones para crear las tablas necesarias:
bash
php spark migrate
(Opcional) Ejecuta seeders para datos iniciales:
bash
php spark db:seed
Ejecuta el servidor

bash
php spark serve
Accede a la app en http://localhost:8080

📝 Consignas del trabajo
Este proyecto responde a las consignas de la materia Prácticas Profesionales del ISFDyT N°57.
Por requerimiento institucional, el documento original no se publica aquí.
Para más información, consultar la plataforma institucional o contactar al docente responsable.

📢 Contacto
Para dudas o sugerencias, crear un Issue en el repositorio.
Consultas académicas: ISFDyT N°57.
