# 🐍 Python, SQL, Ciencia de Datos y Análisis de Negocios

Repositorio de aprendizaje estructurado con un programa de **24 semanas** que va desde los fundamentos de Python hasta proyectos avanzados de Machine Learning, Business Analytics y aplicaciones empresariales reales.

---

## 📁 Estructura del repositorio

```
├── 00-fundamentos/
│   ├── 01_Semana_1-2.ipynb
│   ├── 02_Semana_3-4.ipynb
│   └── ... (12 notebooks semanales)
│
├── 01-proyectos_integradores/
│   └── ejercicios integrados de Python, SQL y Data Science
│
├── 02-casos_empresariales/
│   └── análisis de negocios y aplicaciones complejas
│
├── Guia.pdf
└── README.md
```

---

## 📚 Contenido por carpeta

### `00-fundamentos/` — Programa semanal de 24 semanas

Notebooks progresivos organizados por semana. Cada uno incluye teoría, ejemplos resueltos, ejercicios guiados y ejercicios libres.

| Semana | Temas principales |
|--------|------------------|
| 1-2    | Python básico, estructuras de control, SQLite, NoSQL |
| 3-4    | SQL avanzado, JOINs, índices, normalización, CTEs |
| 5-6    | Backend, APIs REST, Flask, Pandas, NumPy |
| 7-8    | Algoritmos, estructuras de datos, Big O, grafos |
| 9-10   | Proyectos prácticos: app web, pipeline de datos, API REST |
| 11-12  | Flask Blueprints, SQLAlchemy ORM, bibliotecas estándar avanzadas |
| 13-14  | Testing con unittest y pytest, coverage, transacciones en BD |
| 15-16  | Rendimiento, caché LRU, seguridad web, RBAC, auditoría |
| 17-18  | Patrones de diseño (MVC, Observer, Strategy), EDA, ML básico |
| 19-20  | Pandas y NumPy avanzados, Matplotlib, Seaborn, dashboards |
| 21-22  | Regresión lineal, Random Forest, SQL window functions |
| 23-24  | TensorFlow, redes neuronales, proyectos finales de Data Science |

### `01-proyectos_integradores/` — Aplicación integrada de habilidades

Proyectos que combinan Python, SQL y Ciencia de Datos para resolver problemas reales. Indicados para después de completar las primeras semanas del programa base.

**Contenido:**
- Ejercicios integradores de Python (POO, archivos, NumPy, pandas)
- Análisis de datos con pandas y visualizaciones con matplotlib/seaborn
- Machine Learning básico con scikit-learn (regresión, clasificación)
- SQL completo: consultas, relaciones, optimización e integración con Python
- Pipeline completo: BD → `pd.read_sql()` → análisis → predicciones

### `02-casos_empresariales/` — Análisis de negocios y proyectos avanzados

Casos de aplicación compleja orientados a empresas. Requieren dominio sólido de Python, SQL y Ciencia de Datos.

**Casos incluidos:**

| Caso | Descripción |
|------|-------------|
| Benchmarking de mercado | Análisis de industria, modelo de negocio, informe financiero completo |
| Optimización de e-commerce | Análisis descriptivo → diagnóstico → predictivo → prescriptivo |
| Estrategia de marketing | Caída de ventas, análisis de causas, roadmap de acción |
| Evaluación de empresa tech | Balanced Scorecard, FODA, KPIs, cadena de valor |

**Metodologías trabajadas:** análisis FODA, KPIs, Business Intelligence, experimentación A/B, roadmaps estratégicos, informes financieros.

---

## 🗺️ Cómo usar este repositorio

**Si estás empezando:**
```
00-fundamentos/ → Semana 1-2 → Semana 3-4 → ... → Semana 23-24
```

**Si ya tenés bases de Python y SQL:**
```
00-fundamentos/ → Semana 9-10 en adelante + 01-proyectos_integradores/
```

**Si querés aplicar a contextos de negocio:**
```
01-proyectos_integradores/ → 02-casos_empresariales/
```

---

## 🛠️ Tecnologías del curso

**Lenguajes y entornos**
- Python 3.10+ · Jupyter Notebooks · SQLite

**Backend y APIs**
- Flask · SQLAlchemy ORM · requests

**Datos y análisis**
- pandas · NumPy · matplotlib · seaborn · SciPy

**Machine Learning**
- scikit-learn · TensorFlow/Keras · XGBoost

**Bases de datos**
- SQLite · SQLAlchemy · MongoDB (conceptual)

**Buenas prácticas**
- unittest · pytest · coverage.py · patrones de diseño

---

## ⚙️ Instalación

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio

# Crear entorno virtual (recomendado)
python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows

# Instalar dependencias
pip install pandas numpy matplotlib seaborn scikit-learn \
            flask sqlalchemy requests jupyter
```

Para los módulos de Deep Learning (Semana 23-24):
```bash
pip install tensorflow
```

---

## 📋 Prerequisitos

- Python 3.10 o superior
- Conocimientos básicos de programación (no excluyente — el curso arranca desde cero)
- Jupyter Notebook o VS Code con extensión de notebooks

---

## 📖 Guía de referencia

El archivo `Guia.pdf` incluido en el repositorio contiene:
- Fundamentos de Ciencia de Datos y Machine Learning
- Librerías y frameworks recomendados
- Etapas de un análisis de negocios
- Metodología de análisis empresarial
- Itinerario semanal detallado con descripción de cada tema

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si encontrás un error, querés mejorar un ejercicio o agregar contenido:

1. Hacé un fork del repositorio
2. Creá una rama descriptiva: `git checkout -b fix/descripcion` o `feat/nueva-funcionalidad`
3. Commiteá tus cambios con un mensaje claro
4. Abrí un Pull Request explicando qué cambiaste y por qué

---

*Programa de 24 semanas — Python · SQL · Ciencia de Datos · Análisis de Negocios*
