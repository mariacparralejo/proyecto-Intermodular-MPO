# Modelo Entidad–Relación para Rubio Logistics S.L.

Este repositorio contiene el diseño del **modelo Entidad–Relación (E/R)** correspondiente al sistema de gestión logística de la empresa *Rubio Logistics S.L.*. El objetivo del proyecto es representar de forma clara y estructurada cómo se gestionan los **clientes, envíos, paquetes, empleados, vehículos y almacenes** dentro de la organización.

## 📦 Contenido del repositorio
- Diagrama E/R en formato imagen.
- Documento con la descripción de entidades, atributos y relaciones.
- Tabla resumen de cardinalidades.
- Explicación del funcionamiento del sistema logístico representado.

## 🧩 Entidades principales
El modelo incluye las siguientes entidades:
- **Cliente**
- **Envío**
- **Paquete**
- **Empleado**
- **Vehículo**
- **Almacén**

Cada entidad contiene sus atributos clave e identificadores primarios.

## 🔗 Relaciones y cardinalidades
El sistema se estructura alrededor de la entidad **ENVÍO**, que actúa como núcleo del modelo.  
Las cardinalidades definidas son:

| Relación              | Cardinalidad | Descripción                                               |
|-----------------------|--------------|-----------------------------------------------------------|
| CLIENTE — ENVÍO       | 1 : N        | Un cliente puede tener muchos envíos.                    |
| ENVÍO — PAQUETE       | 1 : N        | Un envío puede contener varios paquetes.                 |
| EMPLEADO — ENVÍO      | 1 : N        | Un empleado gestiona muchos envíos.                      |
| VEHÍCULO — ENVÍO      | 1 : N        | Un vehículo realiza muchos envíos.                       |
| ALMACÉN — ENVÍO       | 1 : N        | Un almacén gestiona muchos envíos.                       |

## 🎯 Objetivo del modelo
El propósito del diseño es servir como base conceptual para:
- La creación del **modelo lógico** de la base de datos.
- La futura implementación del **modelo físico**.
- La comprensión del flujo de información dentro del sistema logístico.

## 📝 Autoría
Proyecto realizado como parte del módulo de **Bases de Datos** del ciclo formativo *Sistemas Microinformáticos y Redes (SMR)*.

