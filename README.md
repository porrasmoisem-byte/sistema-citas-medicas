 🏥 Sistema de Gestión de Citas Médicas

 Plataforma web integral desarrollada con Laravel para la automatización, control y seguimiento de citas médicas y pacientes.
 📋 Descripción del Proyecto
Este sistema fue diseñado para optimizar el flujo de trabajo en consultorios médicos. Permite a los administradores gestionar la disponibilidad, agendar citas de manera eficiente y mantener un registro detallado del historial de los pacientes. 

 🛠️ Stack Tecnológico
*Backend:** PHP / Laravel
*Base de Datos:** PostgreSQL
*Frontend:** Blade, Tailwind CSS, Vue.js, Vite
*Gestor de Paquetes:** Composer & NPM

 ⚙️ Características Principales
*Gestión Integral de Pacientes:** Registro, actualización y control de historial médico.
*Sistema de Agendamiento:** Creación de turnos, asignación de citas y control de disponibilidad.
*Interfaz Moderna y Responsiva:** Diseño rápido y optimizado gracias a Tailwind CSS y Vite.

🚀 Instalación Local
Si deseas probar este proyecto en tu entorno local, sigue estos pasos:

1. Clona el repositorio: `git clone https://github.com/porrasmoisem-byte/sistema-citas-medicas.git`
2. Instala las dependencias de PHP: `composer install`
3. Instala las dependencias de Node: `npm install`
4. Crea una copia del archivo de entorno: `cp .env.example .env` y configura tus credenciales de PostgreSQL.
5. Genera la clave de la aplicación: `php artisan key:generate`
6. Corre las migraciones de la base de datos: `php artisan migrate`
7. Inicia el servidor de desarrollo: `php artisan serve` y compila los assets con `npm run dev`.
