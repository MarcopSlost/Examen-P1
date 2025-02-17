# Examen-P1

Descripción del Proyecto

Este proyecto consiste en una estación meteorológica inteligente basada en ESP32, capaz de medir y registrar temperatura, humedad y presión atmosférica. Los datos obtenidos se envían a la plataforma ThingSpeak para su almacenamiento y análisis en la nube. Además, se muestra la información en una pantalla OLED y se activa una alarma sonora si las mediciones superan ciertos umbrales.
🛠️ Hardware Utilizado

    ESP32: Microcontrolador con conectividad Wi-Fi para la transmisión de datos.
    DHT22: Sensor de temperatura y humedad.
    BMP180: Sensor de presión atmosférica.
    OLED: Pantalla para visualizar mediciones.
    Buzzer: Alarma sonora.

🖥️ Software Utilizado

    Arduino IDE: Para programar el ESP32.
    ThingSpeak: Plataforma en la nube para almacenar y visualizar los datos en tiempo real.

🔌 Esquema de Conexión
Componente	Pin de Conexión
DHT22	D4 (Digital)
BMP180	I2C (SDA a GPIO21, SCL a GPIO22)
Pantalla OLED	I2C
Buzzer	D5 (Digital)
💻 Desarrollo del Código

El código en Arduino realiza las siguientes funciones:

    Lectura de Sensores: Captura valores de DHT22 y BMP180.
    Visualización de Datos: Muestra las mediciones en la pantalla OLED.
    Envío a la Nube: Transmite la información a ThingSpeak mediante la librería correspondiente.
    Control de la Alarma: Activa el buzzer si los valores de temperatura o humedad superan los umbrales definidos.

🌐 Configuración en ThingSpeak

    Crear una cuenta en ThingSpeak.
    Generar un nuevo canal con los siguientes campos:
        Temperatura
        Humedad
        Presión atmosférica
    Obtener la clave de API para escribir datos en el canal.

📑 Requisitos de Evaluación

Para la evaluación del proyecto, se deben entregar los siguientes elementos en GitHub:

    📜 Código fuente: Organizado y comentado.
    📡 Esquema de conexión: Diagrama detallado de conexiones.
    🖼️ Capturas de pantalla de ThingSpeak: Configuración del canal.
    📝 Explicación: Funcionamiento, problemas encontrados y soluciones implementadas.

![Sin título](https://github.com/user-attachments/assets/e3c842f7-35a5-49f2-b87e-9a77d732ea19)

![WhatsApp Image 2025-02-17 at 10 02 13 AM](https://github.com/user-attachments/assets/70617c14-d7f7-4a7a-bc71-43350a0b728b)




