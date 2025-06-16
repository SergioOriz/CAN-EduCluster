# 🚗 CAN-EduCluster  
**Clúster de instrumentos automotriz educativo con ESP32 y CAN bus**  

## 📌 Descripción  
Proyecto que implementa una **interfaz gráfica (GUI)** para emular un dashboard vehicular, conectado a una red CAN con nodos ESP32 y sensores (RPM, temperatura, combustible).  

## 🛠️ Estructura del Repositorio  
- `/hardware`: Diseños de circuitos y PCBs.  
- `/firmware`: Código para ESP32 (MCP2515/TJA1050).  
- `/gui`: Interfaz en Python/MATLAB.  
- `/3d_models`: Piezas imprimibles en 3D.  

## 🔌 Hardware Utilizado  
- **Microcontroladores**: ESP32.  
- **Transceptor CAN**: TJA1050.  
- **Sensores**: Efecto Hall (RPM), Termistor (temperatura), Sensor de combustible.  

## 📡 Protocolos  
- **CAN Bus** (500 kbps, formato de trama estándar).  
- **Comunicación Serial** (UART a 115200 bps).  

## 📸 Vista Previa  
![Foto del prototipo](https://github.com/SergioOriz/CAN-EduCluster/blob/main/Diagrama%20prototipo.png)  

## 📚 Documentación Adicional  
Consulta los [docs](/docs/) para guías detalladas.  
