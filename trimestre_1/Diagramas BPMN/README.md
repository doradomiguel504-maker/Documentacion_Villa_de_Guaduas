
<div align="center">
  <img src="https://raw.githubusercontent.com/doradomiguel504-maker/Documentacion_Villa_de_Guaduas/main/LOGO%20VILLA%20DE%20GUADUAS.jpg" alt="Logo Villa de Guaduas" width="80" height="80" style="border-radius: 50%; object-fit: cover;" /><br><br>
  <h2>Documentación — Diagramas de Procesos BPMN</h2>
  <p><b>Proyecto Formativo Villa de Guaduas | Análisis y Desarrollo de Software (SENA)</b></p>
  <p>
    <img src="https://img.shields.io/badge/ESTADO-EN%20DESARROLLO-0088cc?style=for-the-badge" alt="Estado" />
    <img src="https://img.shields.io/badge/FICHA-3411004-e67e22?style=for-the-badge" alt="Ficha" />
    <img src="https://img.shields.io/badge/DOCUMENTACIÓN-OFICIAL-5ea813?style=for-the-badge" alt="Documentación" />
  </p>
</div>

---

## 📌 Presentación del Módulo

Esta carpeta contiene el modelado de procesos de negocio en estándar **BPMN 2.0** (*Business Process Model and Notation*) para el Sistema de Información de Inventario de Materias Primas de la microempresa **Villa de Guaduas**.

Su objetivo es graficar de forma estandarizada los flujos operacionales del negocio, identificando los carriles por rol (*Swimlanes*), compuertas de decisión (*Gateways*), eventos y subprocesos para la gestión de insumos.

---

## 🎯 Componente Metodológico

### 1. Alcance de los Procesos Modelados

Los diagramas BPMN archivados en esta carpeta representan el flujo de trabajo operacional dividido en sus subprocesos clave:

* **Gestión de Materias Primas (Proceso General):** Definición de necesidades, autorizaciones de compra y seguimiento al inventario por parte de administración.
* **Subproceso 1 — Recepción y Almacenamiento:** Recepción de insumos, verificación de cantidad/estado, cotejo con facturas/remisiones, clasificación, ubicación física y registro de ingreso.
* **Subproceso 2 — Solicitud y Entrega para Producción:** Solicitud de materia prima por parte de cocina, verificación de disponibilidad de stock, entrega de insumos, registro de salida y reporte de consumos o faltantes.

---

## 👥 Roles Modelados (*Swimlanes*)

| Rol en BPMN | Responsabilidades en el Flujo |
| :--- | :--- |
| **Administrador** | Definición de necesidades, autorización de reposición y toma de decisiones periódicas. |
| **Auxiliar de Bodega** | Control físico de existencias, recepción, almacenamiento, clasificación y entrega a producción. |
| **Operario de Producción** | Solicitud de insumos, uso en proceso de fabricación de galletas/repostería y reporte de consumos. |

---

## 📐 Estándar de Archivos y Herramientas

Los diagramas han sido diseñados utilizando herramientas de modelado estándar (como Visual Paradigm) y se almacenan tanto en formato de imagen exportada (`.png`, `.svg`) como en archivos fuente para su control de versiones.
