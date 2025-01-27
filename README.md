# Data Digger

## Descripción
**Data Digger** es una aplicación de escritorio diseñada para facilitar la extracción de datos de sitios web estáticos y dinámicos. Su principal objetivo es proporcionar herramientas eficientes para procesar información y entregarla en formatos organizados, como PDF o Excel. La aplicación es completamente portable, ya que está empaquetada como un archivo ejecutable (.exe) que no requiere instalación.

---

## Funcionalidades

### 1. Wiki Scraper
Este módulo permite a los usuarios:
- Extraer información relevante de páginas de Wikipedia.
- Generar un archivo PDF con el contenido seleccionado.
- Identificar palabras clave con enlaces a otros artículos relacionados y mostrarlas como recomendaciones.

**Flujo de trabajo:**
1. Introducir la URL de la página de Wikipedia.
2. Procesar el contenido para extraer texto relevante y enlaces.
3. Generar un archivo PDF con los resultados.

### 2. Real State Scraper
Este módulo se enfoca en páginas de bienes raíces y permite:
- Extraer publicaciones según los filtros proporcionados (ciudad, barrio, tipo de inmueble, etc.).
- Generar un archivo Excel con los datos estructurados.
- Buscar automáticamente la mejor opción según los criterios del usuario.

**Flujo de trabajo:**
1. Introducir la URL del sitio de bienes raíces.
2. Configurar los filtros deseados.
3. Generar un archivo Excel con los resultados y resaltar la mejor opción.

---

## Requisitos Técnicos

### Lenguaje de programación:
- **Python**

### Bibliotecas utilizadas:
- `customtkinter` para la interfaz gráfica.
- `Pillow` para la manipulación de imágenes.
- `requests` y `beautifulsoup4` para scraping web.
- `pandas` y `openpyxl` para manipulación de datos en Excel.
- `reportlab` para generación de PDFs.
- `PyInstaller` para empaquetar la aplicación como archivo ejecutable.

---

## Estructura de la Aplicación

1. **Interfaz Gráfica:**
   - Diseñada con `customtkinter` para una navegación intuitiva.

2. **Módulos Funcionales:**
   - **Wiki Scraper:** Extrae texto y enlaces de Wikipedia.
   - **Real State Scraper:** Procesa publicaciones de bienes raíces y organiza los resultados.

3. **Generación de Archivos:**
   - PDF para Wiki Scraper.
   - Excel para Real State Scraper.

4. **Empaquetado:**
   - La aplicación está empaquetada como un archivo ejecutable (.exe) utilizando PyInstaller, asegurando portabilidad.

---

## Instalación y Uso

1. Descargar el archivo ejecutable (.exe) desde el repositorio.
2. Ejecutar el archivo en cualquier computador con Windows (no requiere instalación).
3. Seguir las instrucciones de la interfaz para seleccionar el módulo deseado y realizar el scraping.

---

## Capturas de Pantalla

### Pantalla Principal
*(Agregar imagen aquí)*

### Wiki Scraper
*(Agregar imagen aquí)*

### Real State Scraper
*(Agregar imagen aquí)*

---

## Contribuciones
Si deseas contribuir a este proyecto, puedes realizar un fork del repositorio y enviar un pull request con tus mejoras.

---

## Licencia
Este proyecto está licenciado bajo los términos de la licencia MIT.
