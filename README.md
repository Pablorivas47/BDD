# 📚 Trabajo Práctico Especial - Bases de Datos 2

Este repositorio contiene el desarrollo del **Trabajo Práctico Especial (TPE)** para la materia **Bases de Datos 2**, de la carrera de Ingeniería en Sistemas en la Facultad de Ciencias Exactas - UNCPBA.  

El objetivo del proyecto es diseñar y desarrollar un sistema de base de datos para un **proveedor de servicios de internet**, cumpliendo con los requerimientos indicados en el enunciado.

---

## 📖 Descripción del Sistema

El sistema modela la gestión de clientes y servicios de un proveedor de internet, permitiendo el control de la facturación, registro de equipos, tipos de conexión y comprobantes.  

### Funcionalidades clave:

- **Clientes:** Registro de datos personales, fecha de alta/baja y estado de actividad.
- **Equipos:** Gestión de dispositivos con información sobre tipo de conexión y asignación de IP.
- **Facturación:** Generación de facturas para servicios periódicos y únicos.
- **Comprobantes:** Manejo de facturas, recibos y remitos.
- **Reglas de negocio:** Restricciones y validaciones para garantizar la integridad de los datos.

---

## 🛠️ Tecnologías utilizadas

- **PostgreSQL:** Base de datos relacional utilizada para la implementación de restricciones y consultas.
- **MongoDB:** Base de datos NoSQL para consultas específicas.
- **SQL:** Implementación de restricciones, vistas y procedimientos almacenados.
- **Triggers y Procedimientos:** Automatización de la generación de facturas y gestión de reglas del negocio.

---

## 📋 Contenidos del Proyecto

### 1. 🛡️ Reglas del Negocio  
   Implementación de restricciones para asegurar la coherencia de los datos, utilizando:  
   - Restricciones declarativas en SQL.  
   - Triggers en PostgreSQL cuando no sea posible declararlas directamente.  

### 2. 🔄 Servicios y Actualización de Información  
   Desarrollo de procedimientos almacenados para automatizar:  
   - Generación mensual de facturas.  
   - Generación de informes de empleados y clientes atendidos.  

### 3. 👁️ Definición de Vistas  
   Creación de vistas en PostgreSQL para obtener información relevante del sistema:  
   - Saldo de clientes menores de 30 años con más de 3 servicios.  
   - Clientes activos dados de alta en el año actual.  
   - Servicios periódicos facturados en los últimos 5 años.  

### 4. 🌐 NoSQL (MongoDB)  
   Consultas específicas utilizando MongoDB para obtener:  
   - Tipos de intervalos y cantidad de servicios.  
   - Clientes con facturación superior a 250 unidades.  

---

## ⚙️ Instalación y Configuración

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/tpe-bases-datos.git
   cd tpe-bases-datos
