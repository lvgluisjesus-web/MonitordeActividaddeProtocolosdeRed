# MonitordeActividaddeProtocolosdeRed

Este proyecto tiene como objetivo monitorear el uso de protocolos de red en equipos de cualquier sistema operativo, capturando información del sistema, actividad de puertos y validando direcciones en la red. La solución incluye cliente local, servicio en segundo plano, base de datos MySQL y una interfaz web para visualización.
## 🧩 Componentes del proyecto
- **Captura de sistema**: Script en PowerShell que obtiene OS, hostname, MAC, IP, fabricante y puertos activos.
- **Validación de red**: Verifica que MAC/IP no estén duplicadas en otros hostnames.
- **Base de datos MySQL**: Modelo con tablas `Equipo`, `Fabricante`, `Protocolo`, `ProtocoloUsado`.
- **Aplicación cliente**: App en Visual Basic o C# con ícono en System Tray.
- **Servicio Windows**: Se ejecuta al inicio y envía datos periódicamente.
- **Interfaz web**: Dashboard responsivo con gráficas y reportes.
- **Clasificación de protocolos**: Colores según nivel de seguridad (Verde, Amarillo, Naranja, Rojo).

## 🎯 Objetivo
Automatizar la supervisión de protocolos en la red, detectar actividad sospechosa y generar reportes visuales para el área de sistemas.

## 📦 Estado actual
✅ Repositorio creado  
✅ Archivo `readme.txt` subido  

## 📅 Autor
Luis Jesús Vázquez Osuna  


