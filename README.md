# Generador Automático de CV en Python
Este proyecto implementa un generador automatizado de currículum vitae tipo Harvard en formato Word (.docx) utilizando Python 
El script construye un CV completo desde cero aplicando un diseño profesional: encabezados estilizados, bordes inferiores, viñetas, alineación mediante tabuladores, hipervínculos, márgenes optimizados y espaciados coherentes.
El objetivo es automatizar la creación de CVs personalizados y facilitar la reutilización del formato para actualizaciones o nuevas versiones.

**Características principales**

- Generación automática de un CV profesional en .docx
- Encabezados con formato personalizado y borde inferior
- Alineación precisa de fechas mediante tabuladores
- Viñetas y espaciado optimizado para una sola página
- Hipervínculos funcionales (LinkedIn, portfolio, etc.)
- Márgenes configurados programáticamente (1.7 cm)
- Fuente Times New Roman tamaño 11 (estándar corporativo)
- Organización modular del código con funciones reutilizables
- Facilidad para modificar secciones, roles o descripciones

**Requisitos**

Instalar las dependencias ejecutando:
_pip install -r requirements.txt_
Contenido recomendado de requirements.txt:
_python-docx_

**Cómo ejecutar el generador**

Ejecuta el script desde tu terminal:
_python cv_generator.py_
Tras la ejecución, se generará automáticamente el archivo

Puedes editar dentro del script:
- Nombre y datos personales
- Secciones (Perfil, Skills, Experiencia, Educación)
- Roles, fechas y responsabilidades
- Enlaces
- Estilo de cada bloque

**¿Por qué este proyecto es relevante?**

Este generador demuestra habilidades clave en:
- Automatización con Python
- Manipulación avanzada de documentos Word
- Estilo y maquetación mediante XML (OxmlElement)
- Diseño programático de plantillas
- Uso de librerías orientadas a negocio
Es un ejemplo real de cómo Python puede mejorar procesos repetitivos como la generación de CVs, informes o plantillas corporativas.

**Contribuciones**

Este proyecto puede ampliarse fácilmente con:
- Template para CVs en español
- Plantillas múltiples por industria
- Versión en PDF
- Interfaz en Streamlit para generar CVs sin escribir código
Sugerencias o mejoras son bienvenidas.
