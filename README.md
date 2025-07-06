# CAN-EduCluster

Este repositorio contiene los recursos para el proyecto CAN-EduCluster, una red CAN automotriz educativa con sensores y conexión a una GUI, diseñada para estudiantes de Ingeniería en Sistemas Automotrices.

## Diagrama del Sistema

El siguiente diagrama ilustra la arquitectura general del sistema, mostrando los subsistemas para la lectura de temperatura, medición de velocidad, monitoreo del nivel de gasolina, y un gateway central que recopila los datos y se conecta a la GUI del cuadro de instrumentos.

![Diagrama del Sistema](diagramaprototipo.png")

## Estructura del Repositorio

- **Hardware**: Archivos STL para impresión 3D.
  - `Pedal/base_pedal.stl`
  - `Motor_Base/base1(2).STL`
- **Documentation**: Documentación técnica y manuales.
  - `Datasheets/`
    - `RS-550.pdf`
    - `NTC (1).PDF`
    - `OH44E.PDF`
  - `Manuales/`
    - `Manual_de_Usuario_GUI_Cuadro_de_Instrumentos.pdf`
    - `Manual_de_Practicas.pdf`
- **Codigos**: Códigos organizados por prácticas.
  - `Practica_2/`
    - `CAN_Autonomous/` (Arduino con MCP2515)
    - `CAN_Integrated/` (ESP32 con SN65HVD230)
  - `Practica_3/`: Sensor RPM
  - `Practica_4/`: Sensor de temperatura
  - `Practica_5/`: Sensor de nivel de combustible
  - `Practica_6/`
    - `Transmitter_Node/`
    - `Receiver_Node/`
- **GUI_Installer**: Instalador de la interfaz gráfica.
  - `GUI Cuadro de Instrumentos.exe`

## Instrucciones de Uso

1. **Hardware**: Imprime los componentes usando los STL.
2. **Documentación**: Consulta los datasheets y manuales para detalles técnicos.
3. **Código**: Selecciona la práctica y plataforma, carga el código en el microcontrolador. Instala las bibliotecas necesarias (ej., MCP_CAN, CAN) vía el IDE.
4. **GUI**: Instala la interfaz gráfica con el instalador y sigue el `Manual_de_Usuario_GUI_Cuadro_de_Instrumentos.pdf`.

Para más detalles, revisa el `Manual_de_Practicas` en `Documentacion/Manuales/`.
