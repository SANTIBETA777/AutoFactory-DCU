# AutoFactory - Diagrama de Casos de Uso (UML)

**Descripción:**  
El sistema **AutoFactory** está diseñado para optimizar la gestión de producción en una industria automotriz.  
Permite coordinar de forma eficiente las órdenes de producción, el control de calidad, el manejo de inventarios y la administración de usuarios.  
El siguiente diagrama de casos de uso representa las interacciones entre los actores del sistema y las principales funcionalidades del mismo.

---

## 👥 Actores principales
- **Supervisor de Producción:** gestiona las órdenes y supervisa los procesos.  
- **Operario de Planta:** ejecuta las tareas de ensamblaje y control de producción.  
- **Jefe de Calidad:** realiza inspecciones y valida los estándares de calidad.  
- **Administrador del Sistema:** controla usuarios, roles y reportes.  
- **Proveedor:** suministra componentes y materiales a la fábrica.  
- **Sistema de Inventario:** registra movimientos de existencias y actualizaciones automáticas.

---

## ⚙️ Módulos del sistema
1. **Producción:**  
   - Registro de órdenes de producción.  
   - Verificación de disponibilidad de componentes.  
   - Asignación de línea de ensamblaje.  
   - Control de progreso de producción.  
   - Generación de reportes de productividad.  

2. **Control de Calidad:**  
   - Registro de inspecciones de vehículos.  
   - Detección y registro de defectos.  
   - Aprobación de vehículos finales.  
   - Generación de reportes de calidad.  

3. **Inventario y Compras:**  
   - Actualización del stock de componentes.  
   - Creación de órdenes de compra.  
   - Registro de recepción de materiales.  
   - Control de proveedores y suministros.  

4. **Administración:**  
   - Registro y gestión de usuarios.  
   - Asignación de roles y permisos.  
   - Generación de reportes globales del sistema.  
   - Mantenimiento de seguridad y respaldo de datos.  

---

## 🧩 Casos de uso principales

### **Módulo de Producción**
- RF-01: Registrar orden de producción  
- RF-02: Verificar disponibilidad de componentes  
- RF-03: Asignar línea de ensamblaje  
- RF-04: Controlar progreso de producción  
- RF-05: Generar reporte de productividad  

### **Módulo de Control de Calidad**
- RF-06: Registrar inspección de vehículo  
- RF-07: Registrar defectos encontrados  
- RF-08: Aprobar vehículo final  
- RF-09: Generar reporte de calidad  
- RF-10: Registrar retrabajos o devoluciones  

### **Módulo de Inventario y Compras**
- RF-11: Actualizar stock de componentes  
- RF-12: Crear orden de compra  
- RF-13: Registrar recepción de materiales  
- RF-14: Gestionar proveedores  
- RF-15: Generar alertas por bajo inventario  

### **Módulo de Administración**
- RF-16: Registrar usuario del sistema  
- RF-17: Asignar roles y permisos  
- RF-18: Generar reportes globales  
- RF-19: Realizar copias de seguridad  
- RF-20: Configurar parámetros del sistema  

---

## 🧠 Relaciones UML
- `<<include>>` → Verificar disponibilidad de componentes.  
- `<<extend>>` → Registrar defectos encontrados.  
- `<<include>>` → Actualizar stock tras recepción de materiales.  
- `<<extend>>` → Supervisar orden de compra desde producción.  

---

## 📁 Archivos incluidos
- `AutoFactory_DCU.png` → Diagrama UML del_
