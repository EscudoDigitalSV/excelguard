# <img src="https://i.servimg.com/u/f34/20/32/08/60/eg10.png" width="32" height="32"> Excel Guard

> ## 🔓 Desbloqueo Rápido y Eliminación de Protección de Hojas y Libros de Excel
>
> **Excel Guard** es una herramienta ligera para Windows diseñada para eliminar la protección de hojas y libros de Excel (`.xlsx`, `.xlsm`) en segundos, sin modificar los datos ni el contenido del archivo original.
>
> Ideal para usuarios que necesitan recuperar el acceso de edición a sus hojas de cálculo protegidas sin complicaciones ni pérdida de información.

---

<div align="center">
  <h2>📸 Captura de Pantalla</h2>
  <img src="https://i.servimg.com/u/f34/20/32/08/60/egf13.png" alt="Excel Guard Interface" width="400">
</div>

---

# ✨ Características Principales

Excel Guard incluye las funciones esenciales para el análisis y eliminación de protecciones en hojas de cálculo:

* 🔓 **Eliminación Instantánea de Protecciones:** Elimina la protección de hojas (`sheetProtection`) y del libro (`workbookProtection`) en segundos.
* 🛡️ **Preservación Integrada de Datos:** Remueve las restricciones de estructura y edición sin alterar el contenido, fórmulas ni formatos originales.
* 📄 **Soporte para Formatos Modernos de Excel:** Compatible con archivos `.xlsx` y `.xlsm` (libros habilitados para macros).
* 🔍 **Detección Automática de Protección:** Analiza la estructura interna del archivo ZIP/XML para verificar la existencia de protecciones activas antes de procesar.
* 🖱️ **Soporte Drag & Drop:** Arrastra y suelta archivos de Excel directamente en la interfaz para un procesamiento rápido.
* 🧵 **Procesamiento Asíncrono (Worker Thread):** Ejecución en segundo plano que mantiene la interfaz ágil y fluida durante el análisis.
* 📂 **Creación Segura de Copias:** Genera una copia desbloqueada con el sufijo `_unlocked` para preservar siempre el archivo original intacto.
* 🎨 **Interfaz Moderna en Dark Mode:** Diseño elegante optimizado en PySide6/PyQt6 con animaciones fluidas, bordes interactivos y soporte de arrastrar y soltar.
* 📊 **Badge de Estado Dinámico:** Indicador visual en tiempo real para el estado de análisis, éxito, advertencias y errores.
* ✂️ **Ajuste Inteligente de Rutas de Archivo:** Truncado automático de texto largo con elidedText y tooltip contextual para visualizar rutas completas.
* 🛡️ **Defensa Visual Multi-pantalla:** Control automático de reajuste de interfaz contra variaciones de escalado DPI en Windows.
* 🇪🇸 **Interfaz en Español:** Diseñada para ser clara, intuitiva y fácil de usar.

---

# 🆕 Actualización — Versión 1.0.0

### Lanzamiento Oficial de Excel Guard

Se presenta la versión inicial de Excel Guard, orientada a la remoción directa y segura de restricciones en hojas de cálculo de Microsoft Excel.

* ⚡ **Motor de eliminación ultra rápido:** Descompresión y modificación directa del marcado XML interno de los libros.
* 🖱️ **Experiencia de usuario optimizada:** Zona de arrastre interactiva con animaciones de opacidad y bordes punteados.
* 🔍 **Verificación previa:** Identificación de archivos sin protección para evitar duplicación o procesamiento innecesario.
* 💡 **Información de productos Pro:** Integración con diálogos orientados a funciones avanzadas de cifrado y restauración.
* 🛠️ **Base sólida y ligera:** Arquitectura optimizada para ejecuciones en sistemas Windows de 64 bits.

**Versión actual: `1.0.0`**

---

# 🔒 ¿Cómo funciona?

### 📥 Proceso de Desbloqueo
Archivo protegido (.xlsx / .xlsm) ➔ Análisis XML ➔ Remoción de `<sheetProtection>` y `<workbookProtection>` ➔ Guardado como `_unlocked`

---

# 🛡️ Formato Interno y Estructura XML

Los archivos de Excel (`.xlsx` / `.xlsm`) son contenedores comprimidos en formato ZIP que almacenan la estructura de la hoja de cálculo en código XML:

`xl/worksheets/sheet*.xml` + `xl/workbook.xml`

* **sheetProtection**: Etiqueta XML que bloquea la edición de celdas, formatos y filas/columnas en hojas individuales.
* **workbookProtection**: Etiqueta XML que restringe la modificación de la estructura del libro (añadir, mover o eliminar hojas).
* **Excel Guard** elimina de forma limpia estas etiquetas internas sin alterar el resto del esquema de datos.

---

# 💎 Comparativa y Descarga

<table>
<tr>
<th>Funciones</th>
<th>Gratis (Excel Guard)</th>
<th>Licencia Vitalicia (Excel Guard Pro)</th>
</tr>

<tr>
<td>Eliminación de protección de hojas y libros</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Detección automática de protecciones activas</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Soporte para archivos .xlsx y .xlsm</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Preservación del archivo original intacto</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Soporte Drag & Drop e interfaz en español</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Bloqueo de libros con contraseña real (SHA-512 + salt)</td>
<td align="center">❌</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Restauración exacta de la protección original sin clave</td>
<td align="center">❌</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Respaldo automático cifrado previa modificación</td>
<td align="center">❌</td>
<td align="center">✅</td>
</tr>

<tr>
<td><b>Duración / Acceso</b></td>
<td align="center"><b>GRATIS</b></td>
<td align="center"><b>PARA SIEMPRE</b></td>
</tr>

<tr>
<td><b>Acción</b></td>

<td align="center">
<a href="https://escudodigitalsv.com">
<img src="https://img.shields.io/badge/PROBAR_GRATIS-blue?style=for-the-badge&logo=windows11&logoColor=white">
</a>
</td>

<td align="center">
<a href="https://escudodigitalsv.com/producto/excel-guard-pro">
<img src="https://img.shields.io/badge/🛒_COMPRAR_AHORA-escudodigitalsv.com-blue?style=for-the-badge">
</a>
</td>

</tr>

</table>

---

<p align="center">
  <a href="https://escudodigitalsv.com">
    <img src="https://img.shields.io/github/downloads/escudodigitalsv/excelguard/total?style=for-the-badge&color=28a745&logo=github" alt="Descargas">
  </a>
</p>

---

# 🚀 Modo de Uso

### Desbloquear un Archivo de Excel
1. Selecciona un archivo `.xlsx` o `.xlsm` en la aplicación (o arrástralo a la zona indicada).
2. Haz clic en el botón **🔓 Desbloquear Archivo**.
3. Excel Guard procesará el archivo en segundo plano.
4. El nuevo archivo desbloqueado se guardará en la misma carpeta con el sufijo `_unlocked` (ejemplo: `Reporte_unlocked.xlsx`).

---

# ⚠️ Nota de Seguridad

> [!CAUTION]
> Excel Guard interactúa directamente con la estructura de archivos ZIP/XML de Microsoft Excel para eliminar las marcas de protección de hojas y libros.
>
> Debido a este comportamiento técnico y al procesamiento directo sobre contenedores comprimidos, algunos antivirus o soluciones de seguridad pueden mostrar alertas preventivas o falsos positivos.

> [!NOTE]
> Excel Guard es un proyecto independiente desarrollado por Escudo Digital SV.
>
> Esta primera versión oficial aún no cuenta con una firma digital de código (Code Signing Certificate), por lo que Windows SmartScreen puede mostrar advertencias preventivas al ejecutar el archivo descargado.
>
> Estas advertencias forman parte de las medidas de seguridad estándar de Windows y no indican la presencia de software malicioso.
>
> La incorporación de firma digital se encuentra prevista para futuras versiones del proyecto.

---

# 📥 Instalación y Advertencia de Windows SmartScreen

> [!IMPORTANT]
> Al descargar Excel Guard, Windows puede mostrar la advertencia **"Windows protegió tu PC"**.
>
> Este comportamiento es normal cuando una aplicación descargada desde Internet aún no dispone de una firma digital reconocida por Microsoft.

### Pasos para continuar

1. Haz clic en **Más información**.
2. Haz clic en **Ejecutar de todas formas**.
3. Continúa con la instalación normalmente.

<div align="center">

<img src="https://github.com/escudodigitalsv/applockerpro/blob/aea72c6f141e471c3751d2afb4370da7f3b25cf3/img/SmartScreen.gif" alt="Cómo ejecutar Excel Guard" width="250">

</div>

> [!TIP]
> Este procedimiento generalmente solo es necesario la primera vez que se ejecuta el instalador.

---

# 📦 Requisitos del Sistema

| Requisito         | Mínimo          |
| :---------------- | :-------------- |
| Sistema Operativo | Windows 10 / 11 |
| Arquitectura      | x64             |
| RAM               | 2 GB            |
| Espacio en Disco  | 100 MB          |
| Almacenamiento    | Unidad Local (NTFS / FAT32) |
| Internet          | No requerido    |

---

# 🐛 Reportar un Problema

Si encuentras un error o comportamiento inesperado, puedes enviarnos un correo a **soporte@escudodigitalsv.com** indicando:
* Versión de Excel Guard (versión gratuita)
* Versión de Windows
* Pasos para reproducir el problema
* Mensaje de error
* Captura de pantalla, si es necesario

> [!IMPORTANT]
> Nunca publiques contraseñas ni libros de Excel que contengan información confidencial o personal.

---

<div align="center">

## 🌐 Escudo Digital SV

Desarrollado por **Escudo Digital SV**  
🌐 Sitio web oficial: [escudodigitalsv.com](https://escudodigitalsv.com)

© 2026 Escudo Digital SV. Todos los derechos reservados.

</div>
