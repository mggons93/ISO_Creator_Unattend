# ISO Creator Autounattend + Drivers by Mggons93

**ISO Auto-XML Builder** es una herramienta gráfica en Python diseñada para modificar imágenes ISO de Windows automatizando el proceso de inyección de archivos `autounattend.xml` y, opcionalmente, la inclusión de controladores SSD/NVMe (Intel IRST) de forma transparente para el usuario.

## Imagen de Muestra / Sample Image
<p align="center">
<a href=></a><img src="https://github.com/mggons93/ISO_Creator_Unattend/blob/main/NuevaBuild.PNG"/>
</p>

## 🧩 Características principales

- 🖼️ Interfaz gráfica simple y amigable
- 🔄 Monta automáticamente ISOs de Windows
- 📂 Copia todo el contenido de la ISO original a una carpeta temporal
- 📄 Inserta el archivo `autounattend.xml` (local o descargado desde GitHub)
- 💽 Permite incluir drivers SSD/NVMe descargables (Intel IRST)
- 🛠️ Genera una nueva ISO booteable con `oscdimg.exe`
- ⏱️ Muestra el progreso dinámico del proceso de creación ISO
- 🧹 Limpieza automática de archivos y carpetas temporales

## 🧰 Requisitos
- Windows 10 u 11

##  🚀 ¿Cómo funciona?
- Al abrir la aplicación, se solicita seleccionar una imagen ISO de Windows.

Puedes marcar la opción "Incluir drivers SSD/NVMe" si deseas integrar los controladores Intel IRST.

## 🛠️La herramienta:
- Monta la ISO en segundo plano (usando PowerShell).
- Copia todos los archivos a una carpeta temporal.
- Descarga o usa el archivo autounattend.xml si no está presente.
- Si activaste los drivers, descargará y extraerá el archivo ZIP en drivers/ dentro de la ISO.
- Utiliza oscdimg.exe para generar una nueva ISO booteable.
- Muestra el progreso en tiempo real.
- La nueva ISO modificada se guarda en la carpeta ISOS_GENERADAS.
