# Centro-De-Informaci-n
Elaboración de una aplicación para la administración de entrada/salida de usuarios, inventario de libros, reportes de residencias, prestamos y búsqueda de material bibliográfico 

## ✨ Características

- 🔐 **Sistema de login** con roles (Admin, Bibliotecario, Usuario)
- 👥 **Gestión de usuarios** por número de control y carrera
- 📖 **Catálogo de libros** con portada, ubicación y disponibilidad
- 📋 **Préstamos inteligentes** (valida morosos y límites)
- 🚪 **Registro de entrada/salida** por sala (cómputo/común)
- 📊 **Reportes avanzados** (por fecha, hora, carrera, sala)
- 🎨 **Interfaz moderna** con ttkbootstrap
- ** Creador del sistema: Carlos Gatica Osorio Ingeniero en Sistemas Computacionales

## 🛠️ Tecnologías

- Python 3.10+
- Tkinter / ttkbootstrap (GUI)
- MySQL (Base de datos)
- ReportLab (Generación de PDFs)
- Pillow (Manejo de imágenes)

## 📦 Instalación

```bash
# 1. Clonar repositorio
git clone https://github.com/carlos0716c/Centro-De-Informaci-n.git

# 2. Instalar dependencias
pip install -r requirements.txt

# 3. Configurar base de datos (MySQL)
# Ejecutar el script SQL que está en database/schema.sql

# 4. Ejecutar aplicación
python main.py
