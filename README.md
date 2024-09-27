# 🚀 Proyecto: Envío de Datos desde ESP32 a Google Sheets

Este proyecto permite enviar datos desde un ESP32 a una hoja de cálculo de Google Sheets mediante las APIs de Google Sheets y Google Drive. Es ideal para almacenar y analizar información generada desde un dispositivo IoT de forma automática y remota. 📊

## 📋 Requisitos

Antes de comenzar, asegúrate de contar con los siguientes elementos:

- ✅ Una cuenta de Google con acceso a Google Drive y Google Sheets.
- ✅ Un ESP32 (compatible con WiFi).
- ✅ Arduino IDE.
- ✅ Conexión a Internet.
- ✅ Librerías para ESP32 y HTTP en tu entorno de desarrollo.

## ⚙️ Configuración del Entorno de Google

1. **Hoja de cálculo en Google Sheets**: Crea una hoja de cálculo en Google Sheets para recibir los datos que serán enviados desde el ESP32. ✍️

2. **Activar APIs**:
   - Dirígete a la [Consola de APIs de Google](https://console.cloud.google.com/). 🖥️
   - Crea un proyecto y habilita las APIs de Google Sheets y Google Drive.
   - Genera credenciales OAuth 2.0 para acceso a la API y descarga el archivo `credentials.json`.

3. **Compartir la hoja de cálculo**: Asegúrate de compartir tu hoja de cálculo con el correo electrónico del cliente de servicio creado en la Consola de APIs para dar acceso de edición. 📑

## 🔧 Instalación y Configuración en ESP32

1. **Bibliotecas necesarias**: Asegúrate de tener instaladas las librerías necesarias para conectividad WiFi y envío de datos por HTTP en tu entorno de desarrollo.

2. **Conexión WiFi**: Configura tu ESP32 con las credenciales de tu red WiFi para permitir la transmisión de datos.

3. **Configurar un Script Web en Google Sheets**: Usa el editor de secuencia de comandos en Google Sheets para crear un script que reciba y almacene los datos enviados por el ESP32. 🌐

## 📐 Uso

1. **Configuración inicial**: Conecta el ESP32 a tu red WiFi y asegúrate de tener la URL del script web listo para recibir los datos. 🔗

2. **Monitoreo de Datos**: Una vez que el ESP32 esté conectado y enviando datos, puedes monitorear los datos en tiempo real directamente en Google Sheets. 📊

3. **Automatización**: Configura intervalos regulares para que el ESP32 envíe datos de manera automática a la hoja de cálculo. 🔄

## 👥 Créditos

Este proyecto fue desarrollado utilizando las APIs de Google y el microcontrolador ESP32 para simplificar el almacenamiento y análisis de datos en tiempo real.

## 📜 Licencia

El código lo puedes usar de manera libre
