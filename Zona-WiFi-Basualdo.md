# Proyecto: Zona WiFi Basualdo (Versión Sanitizada)

## 📘 Descripción General
Implementación de una red WiFi en zona abierta para uso interno y controlado de usuarios.  
El objetivo fue **garantizar conectividad estable** en un entorno de trabajo mixto, integrando equipos TP-Link y MikroTik con monitoreo remoto.

## 🧠 Objetivos Técnicos
- Asegurar cobertura continua en áreas abiertas y semicubiertas.
- Mantener aislamiento entre la red interna y la de usuarios visitantes.
- Optimizar el uso de recursos y ancho de banda disponible.
- Configurar monitoreo remoto y alertas automáticas.

## 🧩 Tecnologías y Soluciones
- Equipos TP-Link de largo alcance y routers MikroTik RB.
- Configuración de VLANs para tráfico interno y externo.
- Monitoreo mediante Observium y SNMPv3.
- Control de ancho de banda por colas simples y limiters.
- Portal de acceso controlado para autenticación de usuarios.

## 🔒 Seguridad
- Segmentación total entre usuarios internos y externos.
- Filtrado de direcciones MAC y protección contra reenvío de ARP.
- Autenticación WPA2-Enterprise con credenciales rotativas.
- Sin publicación de IPs, nombres de host ni contraseñas.

## ⚙️ Resultados
- Cobertura inalámbrica estable y segura en toda la zona operativa.
- Red escalable con monitoreo activo y mantenimiento remoto.
- Reducción de tiempos de desconexión y mejor control del ancho de banda.
