# Proyecto: Red Sanatorio Argentino (Versión Sanitizada)

## 📘 Descripción General
Diseño, despliegue y documentación técnica de la infraestructura de red de un entorno sanitario de mediana escala, priorizando la **confiabilidad, redundancia y segmentación del tráfico** entre áreas críticas.

## 🧠 Objetivos Técnicos
- Asegurar conectividad estable entre pisos y sectores administrativos.
- Separar redes de diagnóstico, administración y atención médica mediante VLANs.
- Implementar monitoreo y alertas proactivas de dispositivos de red.
- Establecer un esquema de backup de configuración de switches y routers.

## 🧩 Tecnologías y Equipos
- Switches administrables capa 2/3 con soporte PoE.
- Enlaces troncales de fibra multimodo.
- Router central con políticas de firewall segmentadas.
- Observium CE + SNMPv3 para monitoreo.
- Scripts automatizados para respaldo de configuraciones.

## 🔒 Seguridad y Cumplimiento
- Segmentación por VLAN con aislamiento interdepartamental.
- Acceso administrativo autenticado mediante SSH y claves rotativas.
- Políticas de contraseñas y registros de auditoría.
- No se incluyen direcciones IP, subredes ni topologías físicas por motivos de seguridad.

## ⚙️ Resultado
Infraestructura de red estable, escalable y documentada, con capacidad de ampliación y redundancia para nuevas áreas médicas y servicios de laboratorio.
