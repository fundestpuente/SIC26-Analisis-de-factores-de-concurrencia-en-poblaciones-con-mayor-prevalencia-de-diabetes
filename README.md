# R²D2-253K 
**Análisis de factores de concurrencia en poblaciones con mayor prevalencia de diabetes**

**Curso:** Samsung Innovation Campus – Módulo de Python (Ecuador 2026)  
**Sección:** EC-A


---

## 👥 Integrantes del Grupo
-Daniela Fernández
-David Díaz
-Pablo Macías
-Roger Zambrano
-Leonel Coronel


---

## 📝 Descripción del Proyecto
Los programas de salud públicos de prevención y tamizaje tienen presupuesto limitado, por lo que no es posible llegar a toda la población de igual forma. Especialmente importante para una enfermedad como la diabetes tipo 2, crónica, costosa y muchas veces asintomática. Al desconocer los grupos demográficos con más riesgo, los recursos pueden terminar destinandose a grupos que no tienen mucho riesgo mientras los de alto riesgo quedan desatendidos. El objetivo del proyecto es identificar los perfiles de riesgo asociados con una mayor prevalencia de diabetes, para recomendar a las entidades responsables de la salud pública qué grupos priorizar en sus campañas de tamizaje y prevención.

---

## ⚙️ Instrucciones de Instalación y Ejecución

### Requisitos
- **Python 3.13+**
- **Librerías:** incluidas en `requirements.txt`
- **Jupyter Notebook** o **VS Code** con la extensión de Jupyter

---

### 🪜 Pasos de Ejecución

1. **Clonar el repositorio o ubicarte en la carpeta del proyecto:**
   ```bash
   git clone 
   ```

2. **Instalar dependencias:**
   ```bash
   pip install -r requirements.txt
      ```

3. **Abrir el notebook principal:**
   ```bash
   jupyter notebook main.ipynb
      ```
   o directamente desde VS Code con la extensión de Jupyter.

---

## 📂 Estructura del Código (sugerida)
```
ANÁLISIS Y VISUALIZACIÓN DE LA CALIDAD DEL AIRE/
│
├── data/                       # Archivos de datos
│   └── .csv
│
├── graphs/                     # Gráficos generados automáticamente
│   ├── .png
│
├── src/                        # Código fuente de los módulos
│   ├── .py
│
├── main.ipynb                  # Notebook principal del proyecto
├── requirements.txt            # Dependencias del entorno
├── .gitignore
└── README.md

```

---

## ✅ Herramientas Implementadas
- **Lenguaje:** Python 3.13+
- **Librerías principales:** `pandas, numpy, matplotlib, seaborn`
- **Otras herramientas:** `Jupyter Notebook / VS Code, Git + GitHub`

---

## 🌱 Impacto del Proyecto
Este análisis puede ayudar a las autoridades de salud pública a orientar sus programas de tamizaje y prevención de diabetes hacia los perfiles de mayor riesgo, en lugar de distribuir los recursos de forma uniforme. Al identificar qué combinaciones de factores (indicadores de salud, hábitos de vida y nivel socioeconómico) concentran la mayor prevalencia de prediabetes y diabetes, el proyecto aporta criterios concretos para decidir a quién llegar primero.

Además, la metodología es replicable: el mismo proceso de limpieza, análisis y comparación de grupos podría aplicarse a encuestas de salud de otros países, incluido Ecuador, para obtener conclusiones adaptadas a su propia población.

El impacto debe entenderse dentro de sus límites: los resultados son descriptivos y corresponden a datos autorreportados de adultos de Estados Unidos en 2015. Identifican grupos prioritarios, pero no demuestran causalidad ni reemplazan estudios clínicos o datos locales actualizados.



