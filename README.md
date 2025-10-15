# 📊 Data Science - Análisis y Modelado de Datos

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Repositorio de prácticas y proyecto de aula para la asignatura de Ciencia de Datos. Contiene análisis exploratorios, visualizaciones y técnicas de modelado aplicadas a datasets reales.

---

## 📁 Estructura del Repositorio

```
data-sciense/
├── sesiones_practicas/          # Ejercicios y talleres de clase
│   ├── sc_1_*.ipynb            # Sesión práctica 1: Introducción a EDA
│   └── ...
├── proyecto_aula/              # Proyecto final aplicado
│   ├── EDA_WorldCup.ipynb     # Análisis exploratorio completo
│   ├── data/                   # Datasets del proyecto
│   │   ├── WorldCupMatches.csv
│   │   ├── WorldCupPlayers.csv
│   │   └── WorldCups.csv
│   └── results/                # Resultados y visualizaciones
└── README.md
```

---

## 🎯 Objetivos del Proyecto

### Proyecto de Aula: Análisis de Asistencia en la Copa del Mundo FIFA

**Pregunta de Investigación:**  
*¿Qué factores influyen en la asistencia de público a los partidos de la Copa del Mundo?*

#### Objetivos Específicos:

2. ✅ Identificar patrones en asistencia según fase del torneo, ciudad sede y evolución temporal
3. ✅ Detectar y analizar valores atípicos mediante técnicas estadísticas
4. ✅ Aplicar técnicas de visualización avanzada con Python
5. 🔄 Desarrollar modelos predictivos para estimar asistencia

---

## 📊 Variables de Estudio

### Variables Continuas (Cuantitativas)
| Variable | Descripción | Fuente |
|----------|-------------|--------|
| **Attendance** | Número de asistentes al partido | WorldCupMatches.csv |
| **AvgAttendanceByYear** | Promedio de asistencia por año | Derivada |
| **AvgAttendanceByStage** | Promedio de asistencia por fase | Derivada |

### Variables Discretas
| Variable | Descripción | Fuente |
|----------|-------------|--------|
| **Year** | Año de la Copa del Mundo (1930-2014) | WorldCupMatches.csv |
| **Stage** | Fase del torneo (grupos, octavos, final) | WorldCupMatches.csv |
| **City** | Ciudad sede del partido | WorldCupMatches.csv |

### Variables Contextuales
- **Stadium**: Estadio donde se jugó el partido
- **Home/Away Team Name**: Equipos participantes
- **Goals**: Goles anotados (local, visitante, tiempo completo)

---

## 🛠️ Tecnologías Utilizadas

### Lenguajes y Herramientas
- **Python 3.8+**: Lenguaje principal
- **Jupyter Notebook**: Entorno de desarrollo interactivo