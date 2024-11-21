Videovigilancia con ESP32
¡Bienvenido al proyecto Videovigilancia con ESP32! Este proyecto está diseñado para implementar un sistema de videovigilancia simple y eficiente utilizando el microcontrolador ESP32 y su módulo de cámara (ESP32-CAM). Aquí encontrarás la guía para configurar, ejecutar y personalizar el sistema.

🚀 Características
Captura de video en tiempo real.
Servidor web integrado para transmisión en vivo.
Detección de movimiento mediante software (opcional).
Integración con notificaciones por correo o Telegram (opcional).
Fácil personalización y ampliación.

🛠️ Requisitos
Hardware
ESP32-CAM o ESP32 con módulo de cámara compatible.
Fuente de alimentación de 5V (ej. adaptador USB).
Módulo FTDI o similar para cargar el firmware.
Tarjeta microSD (opcional, para almacenamiento local de imágenes).
Software
Arduino IDE o PlatformIO.
Biblioteca ESP32 en Arduino IDE.
Dependencias adicionales (detalladas en el archivo src/README_dependencies.md).

📡 Uso del Sistema
Conecta el ESP32-CAM a la alimentación.
En el monitor serie del IDE, busca la dirección IP asignada.
Accede a la interfaz web escribiendo la dirección IP en tu navegador.
