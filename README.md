# Script para notificar a Slack si hay figuritas del Mundial

Sencillo script para notificar a Slack que hay **figuritas del Mundial** en la web de Panini. 

El script corre en [Google Apps Scripts](https://script.google.com/), la herramienta de Google para automatizar tareas de Google Sheets entre otras funciones, y busca si hay stock en la página del Pack x 25 sobres de figuritas.

Para utilizarlo, primero hay que **generar un webhook en Slack**: https://api.slack.com/messaging/webhooks

Para programarlo en Apps Script: ir a Activadores en la barra lateral, Añadir Activador, seleccionar la función y elegir "Según tiempo" y "Temporizador por horas" o por minutos.

![image](https://github.com/dtaubaso/hay_figuritas/assets/49786545/5adc4f1c-80af-4e55-8a8f-3802b70992a6)
