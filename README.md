# ISO Auto-XML Builder

**ISO Auto-XML Builder** es una herramienta gráfica en Python diseñada para modificar imágenes ISO de Windows automatizando el proceso de inyección de archivos `autounattend.xml` y, opcionalmente, la inclusión de controladores SSD/NVMe (Intel IRST) de forma transparente para el usuario.

## 🧩 Características principales

- 🖼️ Interfaz gráfica simple y amigable (Tkinter)
- 🔄 Monta automáticamente ISOs de Windows
- 📂 Copia todo el contenido de la ISO original a una carpeta temporal
- 📄 Inserta el archivo `autounattend.xml` (local o descargado desde GitHub)
- 💽 Permite incluir drivers SSD/NVMe descargables (Intel IRST)
- 🛠️ Genera una nueva ISO booteable con `oscdimg.exe`
- ⏱️ Muestra el progreso dinámico del proceso de creación ISO
- 🧹 Limpieza automática de archivos y carpetas temporales

## 🧰 Requisitos

- Windows 10 u 11
- Python 3.9 o superior
- Dependencias Python:
  - `requests`
  - `tkinter` (incluido en la mayoría de instalaciones de Python en Windows)

## 📥 Instalación

1. Asegúrate de tener Python instalado.
2. Descarga o clona este repositorio.
3. Ejecuta el script principal:

