## 👥 Sensor de Movimiento Saludable

## 👥 Descripción

Este proyecto integra tecnologías de Arduino, React, Node.js y Vite para construir un sensor de movimiento orientado a generar un impacto social positivo. La solución está diseñada para promover la vida saludable y fomentar pausas activas, combatiendo el sedentarismo en personas que pasan largas horas trabajando o estudiando, utilizando tecnología accesible y fácil de implementar.

## Características principales

Monitorización en tiempo real: El sensor de movimiento detecta la inactividad y envía alertas al usuario.

Notificaciones dinámicas: Interfaz web en React que muestra recordatorios para realizar pausas activas.

Back-end escalable: Servidor en Node.js con endpoints REST que gestionan la configuración y el histórico de pausas.

Desarrollo rápido: Bundler Vite para optimizar la experiencia de desarrollo y el despliegue.

Social y accesible: Diseñado con el objetivo de mejorar la salud y productividad de comunidades académicas y laborales.

## 👥 Tecnologías

Hardware: Arduino (sensor de movimiento PIR, LED)

Front-end: React, Vite

Back-end: Node.js, Express

Comunicación: WebSockets o HTTP para transmisión de datos en tiempo real

Control de versiones: Git & GitHub

## 👥 Instalación

Clonar el repositorio:

git clone https://github.com/tu-usuario/sensor-movimiento-saludable.git
cd sensor-movimiento-saludable

Configurar Arduino:

Conecta el sensor PIR y el LED al Arduino.

Sube el sketch arduino/sensor.ino usando el IDE de Arduino.

Back-end:

cd server
npm install
npm run dev

Front-end:

cd client
npm install
npm run dev

Abrir la aplicación:

Front-end: http://localhost:5173

Back-end API: http://localhost:3000

## 👥 Uso

Inicia el servidor de Node.js.

Inicia la aplicación React con Vite.

Coloca el dispositivo Arduino en tu espacio de trabajo.

Cuando detecte inactividad prolongada, la interfaz web mostrará una alerta para realizar una pausa activa.

Realiza ejercicios breves o estiramientos, y confirma en la aplicación que completaste la pausa.

## 👥 Impacto Social

Este proyecto busca:

Reducir sedentarismo: Incentiva movimientos regulares durante la jornada de estudio o trabajo.

Mejorar salud mental y física: Promover pausas activas ayuda a disminuir el estrés y mejorar la concentración.

Fomentar comunidades saludables: Facilita la implementación en espacios educativos y corporativos para crear hábitos sostenibles.

## 👥 Equipo de Desarrollo

- **Mathias Villena** –  Desarrollar Backend (Node.js)
- **Carlos Asparrin** – Desarrollar Frontend(React)
- **Angela Lopez** –  Diseño UX/UI
- **Erick Campos** –  Desarrollo en Arduino 

