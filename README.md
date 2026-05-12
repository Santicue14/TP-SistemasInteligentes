# TP individual — Machine Learning

![Logo UNPAZ](https://unpaz.edu.ar/sites/default/files/Logo%20Unpaz.png)

| | |
|---|---|
| **Carrera** | Licenciatura en Gestión de Tecnologías de la Información |
| **Materia** | Sistemas Inteligentes |
| **Año** | 2026 |
| **Alumno** | Santiago Baldini Cuevas |
| **Docente** | Ernesto Aguaysol |

---

## Trabajo

**Implementación de algoritmos de aprendizaje automático supervisado** para regresión y clasificación, experimentando con distintos modelos.

### Objetivo

Aplicar algoritmos fundamentales de Machine Learning (regresión y clasificación) y evaluar su rendimiento mediante métricas estándar.

### Instrucciones generales

- Para cada parte, crear un nuevo notebook de Jupyter o Colab.
- Se pueden usar como base los códigos provistos en la cátedra (archivos 001 al 009) y los de las presentaciones de clase.
- El trabajo debe incluir no solo el código funcional, sino también celdas de texto (Markdown) que expliquen qué hace el código, analicen los resultados y respondan a las preguntas planteadas.

---

## Consignas y entregas (revisión docente)

**Enunciado completo:** [PDF del TP](./01_machine_learning/UNPAZ%20-%20LGTI%20-%20Sistemas%20Inteligentes%202026%20-%20TP%20INDIVIDUAL%20-%20ML.pdf) (Partes 1 y 2).

**Carpeta del trabajo:** `01_machine_learning/` (datasets CSV y notebooks).

### Parte 1 — Regresión

- **Notebook:** [`1)_RLM_metricas_error.ipynb`](./01_machine_learning/1%29_RLM_metricas_error.ipynb)
- **Qué se hace:** regresión lineal múltiple para predecir el **costo del seguro médico** a partir de edad, género, IMC, cantidad de hijos y tabaquismo; preparación de datos, división train/test, escalado cuando corresponde y evaluación con **métricas de error** (por ejemplo MAE y MSE).

### Parte 2 — Clasificación

- **Notebook:** [`2)_KNN_Trees_metricas.ipynb`](./01_machine_learning/2%29_KNN_Trees_metricas.ipynb)
- **Qué se hace:** clasificación binaria de **presencia de enfermedad cardíaca**; entrenamiento y comparación de **KNN** y **árboles de decisión** (varias profundidades), con **exactitud**, **matrices de confusión** y análisis de resultados acorde a la consigna.

---

## Recursos

- [Repositorio de guía del docente](https://github.com/ernestoaguaysol-unpaz/sistemas-inteligentes-2026/tree/main/01_aprendizaje_supervizado) (`01_aprendizaje_supervizado`).
- [Consignas del trabajo práctico (PDF)](./01_machine_learning/UNPAZ%20-%20LGTI%20-%20Sistemas%20Inteligentes%202026%20-%20TP%20INDIVIDUAL%20-%20ML.pdf).
