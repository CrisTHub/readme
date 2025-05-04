# ERP Dunder Mifflin App

Aplicación desarrollada en **Power Apps** utilizando listas de **SharePoint** como base de datos. Esta solución permite la gestión de empleados, departamentos y jefaturas, cumpliendo con el modelo CRUD (Crear, Leer, Actualizar y Eliminar).

---

## 📌 Funcionalidades

- Registro de nuevos empleados con validación de datos.
- Visualización de listas de empleados, departamentos y jefes.
- Actualización de datos desde formularios editables.
- Eliminación de registros directamente desde la interfaz.
- Validaciones para asegurar la integridad de la información.

---

## 🧰 Tecnologías Utilizadas

- **Microsoft Power Apps**
- **SharePoint Online**
- **GitHub** (para control de versiones y respaldo)

---

## 🗃️ Estructura de Listas (SharePoint)

### Lista: Departamento
- `id_Departamento` (Número, PK)
- `NombreDepartamento` (Texto)
- `UbicacionDepartamento` (Texto)
- `PresupuestoDepartamento` (Texto)
- `idJefe` (FK)

### Lista: Jefe
- `id_Jefe` (Número, PK)
- `NombreJefe` (Texto)
- `TelefonoJefe` (Texto)

### Lista: Empleado
- `ID_Empleado` (Número, PK)
- `NombreEmpleado` (Texto)
- `ApellidoEmpleado` (Texto)
- `Correo` (Texto)
- `Teléfono` (Texto)
- `id_Departamento` (FK)

---

## 💾 Archivos incluidos

- `ERP-DunderMifflin.msapp`: archivo exportado desde Power Apps.
- `estructura_listas.md`: documento con el modelo de datos.
- `conclusion.txt`: análisis final del proyecto.

---

## 🔗 Autor
Estudiantes Ingenieria Ejecucion Informatica Mension Desarrollo de sistemas

- Cristian Ñanco
- Yobany La Cruz
- AIEP – Año 2025

---

