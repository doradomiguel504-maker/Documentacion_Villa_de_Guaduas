<div align="center">
  <img src="https://raw.githubusercontent.com/doradomiguel504-maker/Documentacion_Villa_de_Guaduas/main/LOGO%20VILLA%20DE%20GUADUAS.jpg" alt="Logo Villa de Guaduas" width="80" height="80" style="border-radius: 50%; object-fit: cover;" /><br><br>
  <h2>Documentación — Casos de Uso Extendidos</h2>
  <p><b>Proyecto Formativo Villa de Guaduas | Análisis y Desarrollo de Software (SENA)</b></p>
  <p>
    <img src="https://img.shields.io/badge/ESTADO-EN%20DESARROLLO-0088cc?style=for-the-badge" alt="Estado" />
    <img src="https://img.shields.io/badge/FICHA-3411004-e67e22?style=for-the-badge" alt="Ficha" />
    <img src="https://img.shields.io/badge/DOCUMENTACIÓN-OFICIAL-5ea813?style=for-the-badge" alt="Documentación" />
  </p>
</div>

---

## 📌 Presentación del Módulo

Esta carpeta contiene la documentación técnica formal de los **Casos de Uso Extendidos (CUE)** del Sistema de Información para la Gestión de Inventario de Materias Primas de la microempresa **Villa de Guaduas**.

Su propósito es especificar en detalle la interacción paso a paso entre los usuarios y la plataforma, traduciendo los requerimientos funcionales en flujos de trabajo claros, validaciones del sistema y reglas de negocio ejecutables.

---

## 🎯 Componente Metodológico

### 1. Enfoque de la Especificación

Cada caso de uso extendido dentro de esta sección ha sido diseñado para estructurar la lógica del sistema antes de su fase de desarrollo, abarcando:

* **Secuencia de Pasos (Camino Feliz):** Descripción detallada de las acciones de entrada, procesamiento y respuesta esperada.
* **Manejo de Excepciones:** Flujos alternativos ante errores de digitación, falta de stock o fallos de validación.
* **Reglas de Negocio:** Aplicación estricta de políticas como alertas de stock mínimo, control de rotación (FEFO), costos promedio y aprobaciones.
* **Seguridad y Accesos:** Delimitación clara de permisos para los roles de *Administrador*, *Auxiliar de Almacén* y *Operario de Producción*.

---

## 👥 Actores del Sistema

| Rol | Alcance en los Casos de Uso |
| :--- | :--- |
| **Administrador** | Gestión global del sistema, parametrización, aprobación de mermas/ajustes y auditoría. |
| **Auxiliar de Almacén** | Operación diaria de bodega, recepción de insumos, despacho y lectura de códigos QR. |
| **Operario de Producción** | Consulta de existencias en cocina, reserva de insumos y reporte de consumo o desperdicios. |

---

## 📐 Estándar de Documentación

Todos los archivos contenidos en esta carpeta cumplen con una estructura UML extendida unificada que garantiza la coherencia técnica entre la fase de análisis y la arquitectura de software del proyecto formativo.
