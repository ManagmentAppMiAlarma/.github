# Documentación de Funciones de la Aplicación Web


## 1. Gestión de Órdenes de Servicio

Funcionalidades:
- Crear Órdenes de Servicio:
  - Campos:
    - Número de orden
    - Fecha a realizar el servicio
    - Descripción
    - Abonado (checkbox)
    - Número de cliente
    - Nombre de cliente
    - Dirección del cliente
    - Teléfono del cliente
    - Nombre del técnico
    - Fecha de creación de la orden de servicio
    - Nombre de quien creó la orden de servicio
    - Realizada (checkbox)

  - Flujo:
    - Si "Abonado" está marcado, buscar en la base de datos el número de abonado y completar los campos automáticamente.
    - Si "Abonado" no está marcado, los campos deben completarse manualmente.
- Actualizar Órdenes de Servicio:
  - Permitir la modificación de todos los campos excepto el número de orden y la fecha de creación.


## 2. Gestión de Clientes

Funcionalidades:
- Crear Clientes:
  - Campos:
    - Número de cliente
    - Nombre del cliente
    - Dirección del cliente
    - Teléfono del cliente
- Actualizar Clientes:
  - Permitir la modificación de todos los campos.
- Eliminar Clientes:
  - Permitir la eliminación de clientes existentes.


## 3. Gestión de Empleados

Funcionalidades:
- Crear Empleados:
  - Campos:
    - Nombre del empleado
    - Número de cédula
    - Teléfono del empleado
    - Role (Owner, Admin, Técnico)

- Actualizar Empleados:
  - Permitir la modificación de todos los campos.

- Eliminar Empleados:
  - Permitir la eliminación de empleados existentes.


## 4. Sistema de Login y Roles

Funcionalidades:
- Login:
  - Implementar un sistema de autenticación para el ingreso a la aplicación.

- Roles y Permisos:
  - Owner:
    - Acceso total a la aplicación.
    - Registrar empleados y asignarles roles.
  - Admin:
    - Realizar todas las acciones excepto eliminar o cambiar permisos y datos del Owner.
  - Técnico:
    - Visualizar sus propios datos (sin modificación).
    - Visualizar órdenes de servicio asignadas.
    - Marcar órdenes como realizadas.


MVP (Minimum Viable Product)
La versión mínima viable de esta aplicación incluirá todas las funcionalidades mencionadas anteriormente, permitiendo la gestión de órdenes de servicio, clientes y empleados, con un sistema de roles para la distribución de permisos.
