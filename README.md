# DDTech Scraper

## Descripción
Este script realiza web scraping en la tienda DDTech.mx para extraer información de productos como:
- Título
- Precio
- SKU
- Descripción
- Disponibilidad
- URL

Los datos se guardan automáticamente en un archivo CSV llamado `productos_ddtech.csv`.

## Requisitos
- Python 3.x
- Selenium
- BeautifulSoup
- WebDriver Manager para Python
- `chromedriver.exe` en la carpeta del proyecto

## Uso
1. Instala los requisitos:
   ```bash
   pip install selenium beautifulsoup4 webdriver-manager
   ```
2. Coloca `chromedriver.exe` en la carpeta del proyecto.
3. Ejecuta el script:
   ```bash
   python DDTech Scraper.py
   ```
4. El script buscará productos en la categoría de laptops de DDTech, extraerá los datos y los guardará en el archivo CSV.
5. Al finalizar, verás un resumen en la terminal y el archivo `productos_ddtech.csv` estará listo para usar.

## Personalización
- Puedes cambiar la URL de la categoría modificando la variable `categoria` en el script.

## Autor
Giovani Minutti Mazzocco

---
¿Necesitas ayuda para instalar los requisitos o adaptar el script a otra categoría?
