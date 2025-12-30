# TheWiz-Switch-CFW-Pack-Manager

### 🚀 ¿Qué es?

App desarrollada en C#, diseñada para actualizar automaticamente mis packs de CFW para Switch AIO o Básico.

![Alt-payload](https://i.imgur.com/fCuwQuE.png)

-----

### ✅ Compatibilidad

Funciona en cualquier firmware hasta 21.1.0

# 🎮 Guía de Usuario: Actualizador CFW Switch

Esta herramienta te permite actualizar el software de tu consola de forma segura y sencilla. Sigue estos pasos para una instalación exitosa:

---

### 1. Preparación de la SD
* **Conexión:** Extrae la tarjeta microSD de tu Switch y conéctala a tu PC.
* **Selección:** Abre el programa y en el desplegable **"Seleccionar Unidad SD"**, elige la letra que corresponda a tu tarjeta.
* > **Nota:** El programa detectará automáticamente si tu SD está en formato **FAT32** (Recomendado) o **exFAT** (Menos estable para CFW).

### 2. Selección del Pack
* En el menú **"Pack a Instalar"**, elige la versión del software que desees.
* Revisa la **Descripción** para conocer las novedades y la **Versión detectada** para asegurarte de que es la más reciente.

### 3. Opciones de Instalación (Importante) 🛠️
Antes de pulsar instalar, configura tus preferencias:

* **Hacer Backup previo:** El programa copiará automáticamente tu carpeta `/Nintendo` (juegos, fotos y capturas) a una carpeta en tu Escritorio. **¡Es la opción más segura!**
* **Instalación Limpia:** Borra las carpetas del sistema antiguas (`/atmosphere`, `/bootloader`, etc.) antes de copiar las nuevas. Esto evita errores de compatibilidad y "pantallazos azules". *No borra tus juegos.*

### 4. Proceso de Actualización
Haz clic en **"Instalar Pack"**. El programa seguirá este flujo:
1.  **Backup** (si se seleccionó)
2.  **Descarga** (directa desde el servidor)
3.  **Limpieza**
4.  **Extracción**

*No desconectes la SD mientras la barra de progreso esté activa.*

### 5. Finalización ✅
* Cuando escuches el sonido de confirmación y veas el mensaje de **"Actualización Exitosa"**, la unidad de la SD se abrirá automáticamente.
* Expulsa la tarjeta de forma segura, ponla en tu Switch y enciéndela.

---

### ⚠️ Solución de Problemas Comunes
* **No aparece mi SD:** Pulsa el botón **"Refrescar"** al lado del selector de unidades.
* **Error de Espacio:** Si vas a hacer un backup, asegúrate de tener suficiente espacio libre en el disco duro de tu PC.
* **Error de Red:** Verifica tu conexión a internet, ya que los packs se descargan en tiempo real.





