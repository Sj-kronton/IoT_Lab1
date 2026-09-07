Laboratorio 1 – Azure IoT Central

Autor: Juan Alejandro Sierra Rincón — U00178520

Descripción del escenario

Aplicación personalizada en Azure IoT Central para el monitoreo de calidad de aire en salones de clase, usando como base la plantilla del dispositivo Hobo MX-100. El objetivo fue modelar el dispositivo, definir su telemetría, configurar vistas orientadas al operador y validar el comportamiento mediante un dispositivo simulado.

A partir de la plantilla base Hobo MX-100 se configuró un dispositivo sensor con las siguientes telemetrías:

Temperature:	Variable crítica para calidad de aire; se le dedicó una vista con rangos establecidos para análisis en mayor detalle
Battery Level:	Permite monitorear la autonomía del sensor
Alarms:	Indica eventos anómalos en el dispositivo
RSSI:	Mide la calidad de la señal de conexión

Sobre las vistas: se aprovechó la configuración automática que ofrece Azure IoT Central para visualizar la lectura de datos del sensor, sin necesidad de construirlas manualmente desde cero.

Sobre el dispositivo simulado: se activó el modo de simulación para generar lecturas de telemetría y validar el dashboard con datos en tiempo real.
