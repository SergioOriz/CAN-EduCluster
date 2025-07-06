# CAN-EduCluster

Este repositorio contiene los recursos para el proyecto CAN-EduCluster, una red CAN automotriz educativa con sensores y conexión a una GUI, diseñada para estudiantes de Ingeniería en Sistemas Automotrices.

## Diagrama del Sistema

El siguiente diagrama ilustra la arquitectura general del sistema, mostrando los subsistemas para la lectura de temperatura, medición de velocidad, monitoreo del nivel de gasolina, y un gateway central que recopila los datos y se conecta a la GUI del cuadro de instrumentos.

![Diagrama del Sistema](images/system_diagram.png "Diagrama del sistema CAN-EduCluster que muestra los subsistemas interconectados para temperatura, velocidad, nivel de gasolina, y un gateway central conectado a una GUI de cuadro de instrumentos.")

## Estructura del Repositorio

- **Hardware**: Archivos STL para impresión 3D.
  - `Pedal/pedal.stl`
  - `Motor_Base/motor_base.stl`
- **Documentation**: Documentación técnica y manuales.
  - `Datasheets/`
    - `motor_datasheet.pdf`
    - `thermistor_1kOhm_datasheet.pdf`
    - `hall_effect_sensor_44E_datasheet.pdf`
  - `Manuals/`
    - `User_Manual_GUI_Cuadro_de_Instrumentos.pdf`
    - `Lab_Manual.pdf`
- **Code**: Códigos organizados por prácticas.
  - `Practice_2/`
    - `CAN_Autonomous/` (Arduino con MCP2515)
    - `CAN_Integrated/` (ESP32 con SN65HVD230)
  - `Practice_3/`: Sensor RPM
  - `Practice_4/`: Sensor de temperatura
  - `Practice_5/`: Sensor de nivel de combustible
  - `Practice_6/`
    - `Transmitter_Node/`
    - `Receiver_Node/`
- **GUI_Installer**: Instalador de la interfaz gráfica.
  - `Setup_GUI_Cuadro_Instrumentos.exe`

## Instrucciones de Uso

1. **Hardware**: Imprime los componentes usando los STL.
2. **Documentación**: Consulta los datasheets y manuales para detalles técnicos.
3. **Código**: Selecciona la práctica y plataforma, carga el código en el microcontrolador. Instala las bibliotecas necesarias (ej., MCP_CAN, CAN) vía el IDE.
4. **GUI**: Instala la interfaz gráfica con el instalador y sigue el `User_Manual_GUI_Cuadro_de_Instrumentos.pdf`.

Para más detalles, revisa el `Lab_Manual.pdf` en `Documentation/Manuals/`.
