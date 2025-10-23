# Proyecto: Comparativa de Servidores (Versión Sanitizada)

## 📘 Descripción General
Análisis técnico de distintos servidores físicos y virtuales para definir la mejor alternativa de consolidación y virtualización de servicios internos.

El objetivo principal fue **evaluar rendimiento, consumo, mantenimiento y escalabilidad**, manteniendo un enfoque en eficiencia energética y disponibilidad.

## 🧠 Alcance del Proyecto
- Evaluación de servidores tipo rack y tower.
- Medición de consumo energético, ruido y disipación térmica.
- Comparación de rendimiento con herramientas de benchmarking estandarizadas.
- Análisis de compatibilidad con sistemas de virtualización (VMware ESXi, Hyper-V, Proxmox VE).

## ⚙️ Tecnologías Evaluadas
- **Hypervisores:** VMware ESXi, Microsoft Hyper-V, Proxmox VE.
- **Sistemas Operativos:** Windows Server, Ubuntu Server, Debian.
- **Hardware:** CPU Intel Xeon / AMD EPYC, RAID SAS / SSD, 32-128 GB RAM.
- **Monitoreo:** Observium, PRTG, Zabbix para pruebas de carga.

## 🧩 Criterios de Comparación
| Parámetro                  | Opción A | Opción B | Opción C |
|----------------------------|----------|----------|----------|
| Consumo promedio (W)       | Bajo     | Medio    | Alto     |
| Rendimiento multicore      | Medio    | Alto     | Muy alto |
| Compatibilidad virtualización | Alta | Alta | Media |
| Costo operativo anual      | Bajo     | Medio    | Alto |

## 🔒 Seguridad y Gestión
- Configuración de entornos aislados para pruebas.
- Auditoría y revisión de logs antes y después de los test.
- Eliminación de datos sensibles, direcciones IP y números de serie.

## ⚙️ Resultado Final
Se seleccionó una plataforma híbrida basada en **Proxmox VE** por su balance entre flexibilidad, costo, rendimiento y mantenimiento.  
La documentación técnica se adaptó para uso interno y se mantuvo una versión pública sin información crítica.
