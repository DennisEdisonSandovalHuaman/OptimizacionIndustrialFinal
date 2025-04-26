# Optimización de Localizaciones de Supermercados

Proyecto final de curso enfocado en aplicar **algoritmos evolutivos** para resolver el problema de optimización de localizaciones de supermercados, abordando tanto un **enfoque monoobjetivo** como uno **multiobjetivo**.

## 📂 Estructura del Proyecto

- **01_PRESENTACIÓN**

  - `Informe Proyecto Final - Optimización de Localizaciones Supermercados.docx`: Informe detallado del proyecto.
  - `Proyecto_Final_OptimizCompEvolut_Grupo2_v1.pptx`: Presentación resumen.

- **02_DATOS**

  - `Candidatos_supermercados.xlsx`: Ubicaciones candidatas para instalar supermercados.
  
- **03_PROCESAMIENTO Y CODIGO**

  - `Proyecto_Final_Optimización_Evolutiva_PUCP_IA_MonoObjetivo.ipynb`: Implementación de la optimización monoobjetivo.
  - `Proyecto_Final_Optimización_Evolutiva_PUCP_IA_MultiObjetivo.ipynb`: Implementación de la optimización multiobjetivo.
  - `all_pareto_fronts_optimizado.pkl`: Archivo serializado con los frentes de Pareto óptimos encontrados.
  
- **04_RESULTADOS**
  - `Comparacion_Multiobjetivo_Monoobjetivo_vf.png`: Comparación gráfica entre soluciones multiobjetivo y monoobjetivo.
  - `Evolucion_Fitness_Monoobjetivo_vf.png`: Evolución de la función de fitness durante la optimización monoobjetivo.
  - `resultados_supermercados_mono_objetivo_v2.xlsx`: Resultados de la optimización monoobjetivo.

- `README.md`: Este documento.

---

## ⚙️ Instalación y Dependencias

Para ejecutar este proyecto, asegúrate de tener instalado Python 3.8+ y luego instala las siguientes librerías:

```bash
pip install -r requirements.txt
```

### Librerías principales utilizadas:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `deap`
- `pickle` (estándar en Python)
- `random` (estándar en Python)

> 🖌️ Puedes encontrar el archivo `requirements.txt` en la raíz del proyecto.

---

## 🚀 Ejecución

1. Clona el repositorio:

   ```bash
   git clone <URL-del-repositorio>
   cd <nombre-del-proyecto>
   ```

2. Instala los paquetes necesarios:

   ```bash
   pip install -r requirements.txt
   ```

3. Corre los notebooks:

   - `Proyecto_Final_Optimización_Evolutiva_PUCP_IA_MonoObjetivo.ipynb`
   - `Proyecto_Final_Optimización_Evolutiva_PUCP_IA_MultiObjetivo.ipynb`

4. Explora los resultados y gráficas generadas.

---

## 📊 Descripción Breve del Método

- **Monoobjetivo**
  Se optimiza un único objetivo: **minimizar la distancia promedio** entre supermercados y clientes.

- **Multiobjetivo**
  Se consideran múltiples objetivos de manera simultánea:

  - Minimizar la distancia promedio.
  - Maximizar la cobertura de clientes.

  Se utiliza el algoritmo **NSGA-II** (`deap`).

---

## 🏆 Resultados

- Mejoras significativas en la cobertura y reducción de distancia mediante estrategias evolutivas.
- Ventajas observadas en la solución multiobjetivo frente a la monoobjetivo.

---

# 🔹 requirements.txt sugerido:

```text
numpy
pandas
matplotlib
seaborn
deap
```

(Se asume que `pickle` y `random` ya están disponibles en cualquier instalación de Python).

El siguiente trabajo se ha generado bajo Google Colab y las versiones de los paquetes/librerias son las actuales a la fecha (04/2025)
