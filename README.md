# KaMiZeta (KZ) • Tienda Web Oficial

Sitio web oficial de **KaMiZeta (KZ)** con catalogo interactivo de 34 camisetas, carrusel de banners 2:1 mobile-first, selector de color real, seleccion de telas (KZ Essential y Pesada Brutal) y pedidos directos a WhatsApp (+57 333 401 9149).

## 🚀 Despliegue en GitHub Pages (Paso a Paso)
1. Descomprime el archivo KaMiZeta_Web_GitHub.zip.
2. Sube todos los archivos a la raiz de tu repositorio de GitHub (en la rama main o gh-pages).
3. En tu repositorio de GitHub, entra a Settings -> Pages.
4. En Branch, selecciona main y guarda (Save).
5. En pocos segundos tu pagina web estara activa en tu enlace publico de GitHub Pages.

## 🔄 Como actualizar camisetas y banners sin tocar el codigo
La tienda esta vinculada con tu Google Sheet en Google Drive:
- Base de datos: KaMiZeta_Catalogo_Dinamico
(https://docs.google.com/spreadsheets/d/12nRUir1PK80L8eobuTx6wWHy8Ywii6mdn2DmmE9iJcY/edit)

### Para subir una camiseta nueva:
1. Sube la foto de la camiseta a tu carpeta de Google Drive (02_Colecciones_Disenos) y copia su enlace de compartir.
2. Abre tu hoja de Google Sheets en la pestana 'Productos'.
3. Anade una fila con el nombre, la coleccion, los colores y el enlace de la imagen.
4. Listo. La pagina web leera esa fila y la mostrara automaticamente en su coleccion.

### Para cambiar o agregar banners:
1. Sube el banner a tu carpeta de Google Drive '01_Banners_Web'.
2. En la pestana 'Banners' de Google Sheets, edita el enlace de la imagen o anade una fila nueva.
3. El carrusel rotara el nuevo banner de inmediato.
