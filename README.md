# <img src="https://i.servimg.com/u/f34/20/32/08/60/eg10.png" width="32" height="32"> ExcelGuard 1.0.0

> ## 🔓 Eliminación Instantánea de Protecciones y Desbloqueo de Hojas y Libros de Excel para Windows 10 & 11
>
> ExcelGuard 1.0.0 es una herramienta de utilidad y seguridad para Windows diseñada para desbloquear y remover restricciones de edición, protección de hojas (`sheetProtection`) y libros (`workbookProtection`) de Microsoft Excel (`.xlsx`, `.xlsm`) de forma 100% local, ultra rápida y sin depender de servicios web ni de la nube.
>
> Permite remover contraseñas y bloqueos en archivos de Excel en cuestión de milisegundos sin alterar los datos, fórmulas, formatos ni macros del documento original. Funciona mediante el análisis estructurado del formato OpenXML y la limpieza segura de directivas de protección.
>
> Ideal para profesionales, contadores, administradores de sistemas, analistas de datos, docentes y usuarios que hayan olvidado la clave de una hoja de trabajo o necesiten editar plantillas protegidas sin perder tiempo.

---

<div align="center">
  <h2>📸 Captura de Pantalla</h2>
  <img src="https://i.servimg.com/u/f34/20/32/08/60/egafe10.png" alt="ExcelGuard Interface" width="550">
</div>

---

# ✨ Funciones incluidas en esta versión

ExcelGuard 1.0.0 Free Edition es la primera versión oficial del proyecto e incorpora un motor optimizado de desprotección local y procesamiento multihilo para Windows.

### 🛡️ Desbloqueo Directo de Protecciones OpenXML (`sheetProtection` & `workbookProtection`)

Permite remover instantáneamente la protección contra escritura e inspección de hojas individuales y la estructura completa de libros de Microsoft Excel.

El sistema procesa la estructura comprimida del archivo en memoria sin requerir la clave original, limpiando de forma precisa las etiquetas XML de seguridad (`<sheetProtection>` y `<workbookProtection>`).

Cada archivo procesado genera una copia desprotegida etiquetada como `_unlocked` para garantizar la integridad del archivo original y evitar sobreescrituras accidentales.

### 🔄 Almacenamiento 100% Local y Privacidad Garantizada

Incluye un motor autónomo desarrollado en Python/PyQt6 que no requiere conexión a Internet, servidores remotos ni librerías externas de Office.

Tus archivos financieros, reportes corporativos y datos confidenciales nunca salen de tu computadora, ofreciendo total cumplimiento con normas de seguridad de la información.

Esta función es ideal para:

* 🏢 Contadores, auditores y departamentos de finanzas
* ⚖️ Abogados, administradores y consultores de empresas
* 🎓 Estudiantes y docentes que trabajan con plantillas de cálculo
* 🎒 Usuarios que gestionan presupuestos familiares o archivos personales restringidos

### ⚡ Interfaz Intuitiva con Soporte Drag & Drop y Ejecución Multihilo

Incorpora una zona interactiva para arrastrar y soltar archivos (`Drag & Drop`) con animaciones fluidas, indicador de estado dinámico y alertas visuales.

Gracias a su arquitectura con procesamiento multihilo (`QThread`), la desprotección no congela la interfaz gráfica incluso al trabajar con libros de Excel de gran tamaño.

---

# 💎 Comparativa de Licencias y Descarga

<table>
<tr>
<th>Funciones</th>
<th>Gratis (Free Edition)</th>
<th>Licencia Pro (Vitalicia)</th>
</tr>

<tr>
<td>Desbloqueo de hojas protegidas (sheetProtection)</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Desbloqueo de libros protegidos (workbookProtection)</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Procesamiento 100% local (sin nube ni telemetría)</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Interfaz moderna con Drag & Drop y tema oscuro</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Generación de copia segura (_unlocked)</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Procesamiento asíncrono multihilo (QThread)</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Protección con clave real (SHA-512 + Salt Excel 2013+)</td>
<td align="center">❌</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Restaurar protección original sin contraseña</td>
<td align="center">❌</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Respaldo automático cifrado pre-desbloqueo</td>
<td align="center">❌</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Soporte técnico prioritario y actualizaciones</td>
<td align="center">❌</td>
<td align="center">✅</td>
</tr>

<tr>
<td><b>Duración</b></td>
<td align="center"><b>GRATIS</b></td>
<td align="center"><b>PARA SIEMPRE</b></td>
</tr>

<tr>
<td><b>Acción</b></td>

<td align="center">
<a href="https://github.com/escudodigitalsv/excelguard/releases/download/v1.0.0/ExcelGuard.exe">
<img src="https://img.shields.io/badge/DESCARGAR_GRATIS-blue?style=for-the-badge&logo=windows11&logoColor=white">
</a>
</td>

<td align="center">
<a href="https://www.escudodigitalsv.com/excelguard">
<img src="https://img.shields.io/badge/🛒_COMPRAR_PRO-escudodigitalsv.com-blue?style=for-the-badge">
</a>
</td>

</tr>

</table>

---

<p align="center">
  <a href="https://github.com/escudodigitalsv/excelguard/releases">
    <img src="https://img.shields.io/github/downloads/escudodigitalsv/excelguard/total?style=for-the-badge&color=28a745&logo=github" alt="Descargas">
  </a>
</p>

---

# 🚀 ¿Por qué elegir ExcelGuard?

| 💡 Beneficios Clave                           | ⚙️ Especificaciones                |
| :-------------------------------------------- | :--------------------------------- |
| 🔓 Desbloqueo instantáneo en tu PC o USB.     | 🖥️ Compatible con Windows 10 y 11 |
| 🛡️ 100% offline, sin subir archivos a la nube. | ⚡ Análisis y limpieza OpenXML XML |
| 💾 Conserva datos, fórmulas, tablas y macros. | 🌐 Funciona completamente offline  |
| ⚡ Interfaz rápida con arrastrar y soltar.     | 🚀 Ejecutable portable sin inst.   |
| ⚠️ Detección automática de protección real.   | 🛡️ Preserva el archivo original    |
| 📂 Generación automática de archivo _unlocked | 🔏 Formato .xlsx y .xlsm soportado |

---

# ⭐ Características Principales

### 🔐 Desbloqueo y Remoción de Protecciones Excel

* Desbloqueo automático de protecciones de hojas individuales (`sheetProtection`).
* Eliminación de bloqueos a nivel de estructura de libro (`workbookProtection`).
* Preservación intacta del contenido de celdas, gráficos, fórmulas, formatos y código VBA/macros.
* Generación de un nuevo archivo desprotegido (`nombre_unlocked.xlsx`) sin modificar el archivo origen.

### 💾 Privacidad, Portabilidad y Rendimiento

* Ejecución totalmente fuera de línea (offline) sin recolección de telemetría.
* Operaciones de limpieza en memoria mediante lectura y escritura Zip/XML de alto desempeño.
* Arquitectura basada en hilos secundarios para mantener la UI 100% responsiva durante el procesamiento.

### ⚙️ Interfaz Gráfica y Experiencia de Usuario

* Diseño profesional en Dark Mode optimizado para evitar fatiga visual.
* Zona reactiva de arrastre (`DropZone`) con retroalimentación cromática y cambio de opacidad.
* Indicador dinámico de estado (`StatusBadge`) que informa éxito, ausencia de protección o errores de lectura.
* Manejo automático de escalas DPI en pantallas de alta resolución en Windows.

### 🔑 Gestión de Errores e Inspección de Archivos

* Verificación previa de existencia de marcas de protección antes de aplicar el proceso.
* Mensajes informativos detallados si el archivo no requiere desbloqueo o si posee formato incompatible.

---

# 🛡️ Casos de Uso

✅ Recuperar el acceso de edición a hojas de Excel con contraseña olvidada o perdida

✅ Editar celdas, tablas dinámicas o fórmulas bloqueadas en plantillas corporativas

✅ Modificar estructuras de libros protegidos sin afectar las macros existentes

✅ Automatizar la limpieza de protecciones antes de integrar reportes a sistemas de datos

✅ Trabajar de manera segura con documentos confidenciales en entornos sin conexión a Internet

✅ Mantener intacto el documento original como copia de seguridad previa al desbloqueo

---

# ⚠️ Nota de Seguridad

> [!CAUTION]
> ExcelGuard interactúa directamente con la estructura de archivos ZIP/XML de documentos Microsoft Excel mediante operaciones de bajo nivel de archivos temporales y compresión.
>
> Debido a este comportamiento técnico y al empaquetado autónomo del ejecutable, algunos antivirus o soluciones de seguridad pueden mostrar alertas preventivas o falsos positivos.

> [!NOTE]
> ExcelGuard es un proyecto independiente en constante evolución desarrollado por EscudoDigitalSV.
>
> Esta primera versión oficial aún no cuenta con una firma digital de código (Code Signing Certificate), por lo que Windows SmartScreen puede mostrar advertencias preventivas al ejecutar el archivo descargado.
>
> Estas advertencias forman parte de las medidas de seguridad estándar de Windows y no indican la presencia de software malicioso.
>
> La incorporación de firma digital se encuentra prevista para futuras versiones del proyecto.

---

# 📥 Instalación y Advertencia de Windows SmartScreen

> [!IMPORTANT]
> Al descargar ExcelGuard, Windows puede mostrar la advertencia **"Windows protegió tu PC"**.
>
> Este comportamiento es normal cuando una aplicación descargada desde Internet aún no dispone de una firma digital reconocida por Microsoft.

### Pasos para continuar

1. Haz clic en **Más información**.
2. Haz clic en **Ejecutar de todas formas**.
3. Continúa con la ejecución del programa normalmente.

<div align="center">

<img src="https://github.com/escudodigitalsv/applockerpro/blob/aea72c6f141e471c3751d2afb4370da7f3b25cf3/img/SmartScreen.gif" alt="Cómo ejecutar ExcelGuard" width="250">

</div>

> [!TIP]
> Este procedimiento generalmente solo es necesario la primera vez que se ejecuta el ejecutable.

---

# 📦 Requisitos del Sistema

| Requisito         | Mínimo          |
| :---------------- | :-------------- |
| Sistema Operativo | Windows 10 / 11 |
| Arquitectura      | x64             |
| RAM               | 2 GB            |
| Espacio en Disco  | 30 MB           |
| Almacenamiento    | Disco local / Memoria USB |
| Internet          | No requerido    |

---

# 🐛 Reportar un Problema

Si encuentras un error o comportamiento inesperado, puedes enviarnos un correo a **info@escudodigitalsv.com** indicando:
* Versión de ExcelGuard (v1.0.0)
* Versión de Windows
* Pasos para reproducir el problema
* Captura de pantalla o mensaje de error, si es necesario

También puedes visitar nuestro foro en [https://foro.escudodigitalsv.com/](https://foro.escudodigitalsv.com/) o nuestra organización en GitHub en [https://github.com/EscudoDigitalSV](https://github.com/EscudoDigitalSV).

> [!IMPORTANT]
> Nunca envíes archivos de Excel que contengan información confidencial o financiera personal.

---

<div align="center">

## ❤️ ExcelGuard v1.0.0 © 2026

Primera versión oficial (Free Edition).

Desbloqueo instantáneo, almacenamiento local y eliminación segura de protecciones para Microsoft Excel.

</div>
