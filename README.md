# Más Docentes, Menos Escuelas: Radiografía Educativa de Buenos Aires (2015–2025)

Análisis exploratorio de datos (EDA), ingeniería de características y visualización interactiva sobre la evolución de la matrícula estudiantil, los cargos docentes y las unidades de servicio en los 135 municipios de la Provincia de Buenos Aires durante la década 2015–2025.

---

## Enlaces del Proyecto

* **Notebook Integrada (Google Colab):** [Ver análisis completo en Colab](https://colab.research.google.com/drive/1P3Xetq4YXDYVQnNkkhjJ8klc-pG0-xUB?usp=sharing)
* **Dashboard Interactivo (Looker Studio):** [Explorar tablero en vivo](https://datastudio.google.com/reporting/56c800d3-c364-4048-a042-527d85fbfa00)
* **Fuente de Datos Oficial:** [Portal de Datos Abiertos PBA - DGCyE](https://catalogo.datos.gba.gob.ar/dataset/unidades-de-servicio-y-matricula)

---

## Estructura del Repositorio

```text
├── evolucion-unidades-servicio-y-matricula-municipios-2015_2025.csv  # Dataset crudo original (1.485 registros)
├── dataset_limpio.csv                                                # Dataset procesado con métricas derivadas
├── dataset_dashboard.cvs                                             # Dataset procesado para el dashboard (Beautificación)
├── Mas_docentes_menos_escuelas.ipynb                                 # Notebook unificada (Limpieza, EDA y Validación)
└── README.md                                                         # Documentación del proyecto
