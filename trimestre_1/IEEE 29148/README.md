<div align="center">
  <img src="https://raw.githubusercontent.com/doradomiguel504-maker/Documentacion_Villa_de_Guaduas/main/LOGO%20VILLA%20DE%20GUADUAS.jpg" alt="Logo Villa de Guaduas" width="80" height="80" style="border-radius: 50%; object-fit: cover;" /><br><br>
  <h2>Documentación — Especificación de Requisitos (IEEE 29148)</h2>
  <p><b>Proyecto Formativo Villa de Guaduas | Análisis y Desarrollo de Software (SENA)</b></p>
  <p>
    <img src="https://img.shields.io/badge/ESTADO-EN%20DESARROLLO-0088cc?style=for-the-badge" alt="Estado" />
    <img src="https://img.shields.io/badge/FICHA-3411004-e67e22?style=for-the-badge" alt="Ficha" />
    <img src="https://img.shields.io/badge/DOCUMENTACIÓN-OFICIAL-5ea813?style=for-the-badge" alt="Documentación" />
  </p>
</div>

---

## 📌 Presentación del Módulo

Esta carpeta contiene el documento formal de **Especificación de Requisitos de Software (SRS / ERS)** elaborado bajo el estándar internacional **ISO/IEC/IEEE 29148:2018** para la microempresa **Villa de Guaduas**.

Su propósito es proporcionar una descripción completa, precisa y estructurada del Sistema de Información de Inventario de Materias Primas, sirviendo como contrato técnico entre los desarrolladores, los instructores SENA y la microempresa.

---

## 🎯 Componente Metodológico

### 1. Estructura del Estándar IEEE 29148

El documento archivado en este módulo organiza la ingeniería de requisitos bajo las siguientes secciones normativas:

* **1. Introducción:** Propósito, alcance del sistema, definiciones, acrónimos y referencias del proyecto formativo.
* **2. Descripción General:** Perspectiva del producto, funciones del sistema, características de los usuarios (Administrador, Auxiliar, Operario), restricciones y suposiciones.
* **3. Requisitos Específicos:**
  * **Requisitos Funcionales (RF-01 al RF-26):** Definición detallada de entradas, procesamiento, salidas y reglas de negocio.
  * **Requisitos No Funcionales (RNF-01 al RNF-10):** Criterios de rendimiento, escalabilidad, disponibilidad (99.5%), seguridad y mantenibilidad.
  * **Requisitos de Interfaz Externa:** Interfaces de usuario (UI responsive/móvil), interfaces de hardware (lectores QR) y software.

---

## 👥 Roles y Actores Mapeados

| Perfil en IEEE 29148 | Nivel de Privilegios | Responsabilidades en la ERS |
| :--- | :---: | :--- |
| **Administrador** | Total (Lectura / Escritura / Borrado) | Parametrización, auditoría, aprobación de mermas y valorización. |
| **Auxiliar de Almacén** | Operativo (Entradas / Salidas / Conteo) | Registro de mercancía, despacho, lectura QR y concilación física. |
| **Operario de Producción** | Limitado (Consulta / Reserva / Reporte) | Consulta de existencias, reserva para recetas y reporte de daños. |

---

## 📐 Estándar de Archivos y Versiones

El documento formal de requisitos se mantiene en formatos de texto editable y exportaciones estandarizadas (`.docx`, `.pdf`) para el control de versiones y auditoría de cambios del proyecto.
