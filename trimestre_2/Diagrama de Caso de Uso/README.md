<div align="center">
  <img src="https://raw.githubusercontent.com/doradomiguel504-maker/Documentacion_Villa_de_Guaduas/main/LOGO%20VILLA%20DE%20GUADUAS.jpg" alt="Logo Villa de Guaduas" width="80" height="80" style="border-radius: 50%; object-fit: cover;" /><br><br>
  <h2>Documentación — Diagramas de Casos de Uso</h2>
  <p><b>Proyecto Formativo Villa de Guaduas | Análisis y Desarrollo de Software (SENA)</b></p>
  <p>
    <img src="https://img.shields.io/badge/ESTADO-EN%20DESARROLLO-0088cc?style=for-the-badge" alt="Estado" />
    <img src="https://img.shields.io/badge/FICHA-3411004-e67e22?style=for-the-badge" alt="Ficha" />
    <img src="https://img.shields.io/badge/DOCUMENTACIÓN-OFICIAL-5ea813?style=for-the-badge" alt="Documentación" />
  </p>
</div>

---

## 📌 Presentación del Módulo

Esta carpeta contiene el modelado gráfico y la representación formal de los **Diagramas de Casos de Uso UML** correspondientes al Sistema de Información de Gestión de Inventario de Materias Primas de la microempresa **Villa de Guaduas**.

Su objetivo es delimitar el límite del sistema (*System Boundary*), definir visualmente los actores clave del negocio y mapear las relaciones entre las funcionalidades requeridas (*Include*, *Extend* y *Generalizaciones*).

---

## 🎯 Componente Metodológico

### 1. Enfoque del Modelado UML

Los diagramas contenidos en esta sección estructuran la arquitectura funcional del sistema a partir de las siguientes pautas:

* **Límite del Sistema (System Boundary):** Encapsulamiento claro de las fronteras de software frente a actores externos y sistemas de terceros.
* **Mapeo de Actores:** Representación de los perfiles operativos (*Administrador*, *Auxiliar de Almacén* y *Operario de Producción*).
* **Relaciones Estructurales:**
  * **`«include»`:** Funcionalidades obligatorias requeridas para completar una acción (ej. *Autenticación de usuario* previa a cualquier registro).
  * **`«extend»`:** Comportamientos condicionales u opcionales (ej. *Generación de alertas* o *Lectura de código QR*).

---

## 👥 Actores Modelados

| Actor | Rol e Interacción en el Diagrama |
| :--- | :--- |
| **Administrador** | Actor principal en parametrización, aprobación de mermas, gestión de usuarios, valorización y reportes. |
| **Auxiliar de Almacén** | Actor principal en recepción de compras, movimientos de entrada/salida y conciliación de inventario físico. |
| **Operario de Producción** | Actor secundario/operativo en consulta de stock en tiempo real, reserva de lotes y consumo de insumos. |

---

## 📐 Estándar de Archivos y Versiones

Todos los diagramas archivados en este directorio se encuentran documentados tanto en formato vectorial/imagen (`.png`, `.svg`) como en sus respectivos archivos fuente (`.puml`, `.drawio` o `.vpp`), garantizando la trazabilidad de cambios en el historial de versiones del proyecto.
