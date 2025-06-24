GUI Cuadro de Instrumentos
=========================

Descripción
-----------
GUI Cuadro de Instrumentos es un programa que simula el tablero de instrumentos de un Kia Sorento 2019, mostrando velocidad, RPM, nivel de combustible y temperatura. Se conecta a un dispositivo serial (por ejemplo, un Arduino o ESP32) para recibir datos en tiempo real y mostrarlos en una interfaz gráfica.

Requisitos
----------
- Sistema operativo: Windows (probado en Windows 10/11).
- Puerto serial: Un dispositivo compatible (por ejemplo, Arduino o ESP32) con el firmware adecuado.
- Controladores: Asegúrese de que los controladores del dispositivo serial estén instalados.
- Espacio en disco: Aproximadamente 20 MB.

Instrucciones de Instalación
---------------------------
1. Ejecute el instalador "Setup_GUI_Cuadro_Instrumentos.exe".
2. Siga las instrucciones para instalar en "C:\Program Files\GUI Cuadro de Instrumentos".
3. Conecte el dispositivo serial (por ejemplo, Arduino o ESP32) al puerto COM correspondiente.
4. Ejecute el programa desde el acceso directo en el escritorio o el menú de inicio.

Uso
---
1. Al iniciar, seleccione el puerto COM al que está conectado el dispositivo serial.
2. El programa mostrará:
   - Velocímetro (0-240 km/h).
   - Tacómetro (0-8000 RPM).
   - Indicador de combustible (0-100%).
   - Indicador de temperatura (0-130°C).
3. Los testigos de combustible y temperatura aparecerán en el velocímetro si:
   - El nivel de combustible es menor a 10%.
   - La temperatura es mayor a 110°C.

Notas
-----
- Asegúrese de que el dispositivo serial envíe datos en el formato: "101:temperatura,102:combustible,103:velocidad,104:rpm".
- Si las imágenes no se cargan, verifique que la carpeta "imagenes" esté en el directorio de instalación.

Licencia
--------
Este software está licenciado bajo la Licencia MIT. Consulte el archivo "license.txt" para más detalles.

Contacto
--------
Para soporte o reportar problemas, contacte a Ing. Sergio Josue Ortiz Hernandez en ortizjosue95@hotmail.com.

Créditos
--------
Desarrollado por Ing. Sergio Josue Ortiz Hernandez. Usa bibliotecas: Pillow, pyserial, tkinter.