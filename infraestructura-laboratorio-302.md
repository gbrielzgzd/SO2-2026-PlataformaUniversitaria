# Infraestructura del Laboratorio 302

## Propósito

Este documento organiza la información de infraestructura disponible en el informe del Laboratorio 302 para dejar constancia de los datos reportados y de los puntos que aún requieren verificación. No representa una prueba de funcionamiento de la plataforma universitaria.

## Servidor y virtualización

- **Servidor reportado:** HP Z820.
- **Procesadores reportados:** 2 × Intel Xeon E5-2630 v2.
- **Plataforma de virtualización reportada:** Proxmox VE 9.2.
- **Memoria RAM reportada:** 16 GB instalados.
- **Ampliación de RAM propuesta en el informe:** 128 GB y posteriormente 256 GB. Estas cifras son propuestas, no capacidad instalada confirmada.

## Almacenamiento

La capacidad, el modelo, el tipo y el estado de los discos deben verificarse en el servidor. No se registran aquí valores no confirmados.

## Red

- Se menciona el bridge `vmbr0`.
- Se menciona el uso de DHCP.
- Se propone evaluar segmentación mediante VLAN o bridges con NAT.

La configuración efectiva debe confirmarse en Proxmox y en las máquinas virtuales.

## Máquinas virtuales y contenedores

El informe menciona los siguientes identificadores:

- CT 100
- VM 101
- VM 102
- VM 103
- VM 112

Los nombres, funciones, recursos asignados, direcciones IP y estado de ejecución de cada instancia deben verificarse directamente en el entorno.

## Pendientes de verificación y trabajo

1. Confirmar el inventario real de discos: cantidad, capacidad, modelo, tipo y estado.
2. Verificar la RAM instalada y la memoria asignada a cada máquina virtual o contenedor.
3. Registrar las métricas de CPU, RAM, disco y disponibilidad con mediciones reales.
4. Instalar y probar las herramientas de monitorización previstas por el equipo.
5. Documentar configuración de red, conectividad y acceso a las máquinas.
6. Definir y comprobar el procedimiento de respaldos.
7. Adjuntar evidencias de pruebas realizadas y sus resultados.

## Alcance y limitaciones

Este archivo resume los datos identificados en el informe disponible. Los elementos descritos como propuestas o pendientes no deben interpretarse como configuraciones ya aplicadas ni como pruebas completadas. La relación entre esta infraestructura y la plataforma universitaria del repositorio debe confirmarse por el equipo.
