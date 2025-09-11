# Tarea Final: Aprendizaje Supervisado y No Supervisado

## Proyecto: Análisis de Default de Clientes de Tarjetas de Crédito

**Participantes:**
- Alexia Bornhorst
- Gustavo Martinez
- Emilio Ortega
- Jason Sepulveda
- German Vega

**Magíster en Ciencia de Datos**  
Pontificia Universidad Católica de Chile

---

## Descripción del Proyecto
Este proyecto aborda el problema de predicción de incumplimiento de pago de clientes de tarjetas de crédito en Taiwán, utilizando técnicas de aprendizaje supervisado y no supervisado. El objetivo es extraer información relevante y no evidente del conjunto de datos, comparando la precisión de diferentes métodos de minería de datos para estimar la probabilidad de default.

- **Instancias:** 30.000
- **Características:** 23
- **Tipo de tarea:** Clasificación
- **Tipo de variables:** Enteros, Reales
- **Fuente de datos:** [Default of Credit Card Clients](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

---

## Instrucciones de la Tarea
- **Objetivo:** Aplicar técnicas de aprendizaje supervisado y no supervisado en Python para extraer información del dataset.
- **Formato:** Notebook de Python siguiendo buenas prácticas, con comentarios y celdas markdown explicativas.
- **Informe:** Redactar un informe adicional con las secciones indicadas por el curso.
- **Entrega:** Subir el notebook y el informe con el nombre “TareaFinal_Apellidos_Integrantes” a la plataforma.
- **Licencia:** MIT

---

## Estructura del Proyecto
```
├── environment.yml         # Entorno Conda
├── LICENSE                # Licencia MIT
├── README.md              # Este documento
├── data/
│   ├── raw/               # Datos originales
│   └── processed/         # Datos procesados
├── models/                # Modelos entrenados
├── notebooks/             # Notebooks de análisis
├── references/            # Material de referencia
├── src/                   # Código fuente principal
├── tests/                 # Pruebas unitarias
├── utils/                 # Utilidades y scripts auxiliares
│   └── paths.py
```

---

## Colaboración y Buenas Prácticas
Para trabajar en equipo y mantener la calidad del código, sigue estos pasos:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/jasonssdev/mcd-ml-credit-card.git
   cd mcd-ml-credit-card
   ```
2. **Crear una rama por integrante:**
   ```bash
   git checkout -b nombre-usuario
   ```
3. **Realizar cambios y guardar avances:**
   ```bash
   git add {archivo}
   git commit -m "Descripción de los cambios"
   git push origin nombre-usuario
   ```
4. **Crear un Pull Request:**
   - Ingresa a GitHub y crea un Pull Request desde tu rama hacia `main`.
   - Espera la revisión y aprobación de tus compañeros.
5. **Actualizar tu rama local:**
   ```bash
   git checkout main
   git pull origin main
   git checkout nombre-usuario
   git merge main
   ```

---

## Entorno de Desarrollo
El proyecto utiliza **Conda** para la gestión de dependencias. Para instalar el entorno:

```bash
conda env create -f environment.yml
conda activate mcd-ml-py312
```

---

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

## Contacto
Para dudas o sugerencias, contacta a cualquiera de los integrantes del grupo.