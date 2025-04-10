# 🧼 Proyecto de Limpieza de Datos Minoristas  
![Status](https://img.shields.io/badge/estado-en%20desarrollo-blue)  
![License](https://img.shields.io/badge/license-educational-lightgrey)  
![Python](https://img.shields.io/badge/Python-3.10+-yellow)

Este proyecto forma parte de un portafolio académico-profesional y está dirigido a estudiantes y profesionales en formación en el campo del análisis de datos. Utilizando un conjunto de datos simulado del sector minorista (*retail*), se aborda el proceso completo de **limpieza, validación y preparación de datos**, una de las fases más críticas del ciclo analítico.

---

## 🌟 Objetivos de aprendizaje

- Aplicar técnicas estándar de preprocesamiento de datos.
- Identificar y resolver valores nulos, registros duplicados y errores de tipo.
- Preparar conjuntos de datos adecuados para el análisis exploratorio y la visualización.
- Documentar el flujo de trabajo siguiendo principios de reproducibilidad científica.

---

## 🗂️ Estructura del repositorio

```
01_limpieza-datos-minoristas/
│
├── data/
│   ├── raw/                # Datos sin procesar (CSV original)
│   └── processed/          # Datos limpios listos para análisis
│
├── notebooks/
│   └── limpieza_datos.ipynb  # Notebook interactivo con todo el flujo de trabajo
│
├── scripts/
│   └── limpieza_datos.py     # Script en Python (opcional)
│
├── docs/
│   └── notas_metodologia.md  # Comentarios metodológicos (si aplica)
│
└── README.md
```

---

## 📊 Descripción del dataset

- **Ubicación**: 📁 `data/raw/ventas_minoristas.csv`
- **Contenido**:
  - ID de transacción
  - Fecha
  - Producto
  - Categoría
  - Cantidad
  - Precio unitario
  - Total de venta
  - Ciudad
  - Canal de venta

**Aspectos intencionados**:
- Registros duplicados
- Celdas con valores faltantes
- Tipos de datos inconsistentes

👉 Estos elementos se introducen para simular desafíos reales a los que se enfrentan los analistas de datos en proyectos reales.

---

## 🧪 Metodología aplicada

1. Carga y exploración preliminar del dataset.
2. Identificación y eliminación de duplicados.
3. Tratamiento de valores faltantes.
4. Normalización de nombres y formatos.
5. Conversión de tipos de datos.
6. Exportación del conjunto limpio para análisis posterior.

> Todos los pasos están documentados de forma estructurada y comentada en el notebook: `notebooks/limpieza_datos.ipynb`.

---

## 🛠️ Herramientas utilizadas

- Lenguaje de programación: `Python`
- Librerías principales: `Pandas`
- Entornos de desarrollo: `Jupyter Notebook`, `Visual Studio Code`
- Herramienta auxiliar: `OpenRefine` *(opcional)*

---

## 📈 Resultado esperado

Se obtiene un conjunto de datos limpio, coherente y listo para ser utilizado en:

- Análisis exploratorios
- Desarrollo de indicadores clave de rendimiento (KPIs)
- Visualizaciones dinámicas mediante dashboards

📁 **Archivo exportado**: `data/processed/ventas_limpias.csv`

---

## 🤝 Autoría y contacto

Este proyecto ha sido desarrollado con fines educativos y demostrativos.

- **Autora**: [Naiara Rodríguez – Nailytic](https://github.com/Nailytic)  
- **Áreas de interés**: analítica de datos aplicada a la educación, sostenibilidad y tecnologías emergentes.  
- **Contacto**: disponible para colaboración profesional, revisión académica o intercambio de ideas constructivas.

---

