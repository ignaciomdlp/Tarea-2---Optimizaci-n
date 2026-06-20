# Tarea 2 - Metaheurísticas: Job Shop Problem (JSP)

Este repositorio contiene el código de nuestra implementación para la Tarea 2. Aquí resolvemos el problema de Job Shop utilizando la metaheurística de Simulated Annealing (Recocido Simulado). 

El objetivo principal del algoritmo es encontrar la mejor secuencia de operaciones para minimizar el Makespan total.

## Integrantes:
- Felipe Chavez Gonzalez | 21.637.345-6
- Kamila Leiva Morales | 21.619.863-8
- Ignacio Matus de la Parra Rodriguez | 21.780.939-8
- Sofía Mena Cortés | 21.313.821-9

## Sobre el código
- El algoritmo está programado en Python utilizando un Jupyter Notebook.
- Utilizamos una representación basada en operaciones y un movimiento de intercambio (Swap) para explorar el vecindario.
- El enfriamiento de la temperatura se maneja de forma geométrica.
- El código está preparado para realizar 10 ejecuciones independientes por instancia. Al finalizar, calcula automáticamente la media, la desviación estándar y dibuja gráficos de convergencia y de cajas (boxplots) usando `numpy` y `matplotlib`.

## Instrucciones para ejecutar

La forma más rápida y recomendada de revisar este proyecto es utilizando **Google Colab**, ya que evita tener que instalar librerías manualmente.

### Opción 1: Google Colab (Recomendada)
1. Entra a Google Colab y sube el archivo `Tarea2_Optimizacion.ipynb`.
2. Sube también los archivos de las instancias (`instancia01_facil.txt`, `instancia02_media.txt`, `instancia03_dificil.txt`) al entorno de Colab.
3. Ejecuta todas las celdas del cuaderno en orden.

### Opción 2: Entorno Local
1. Descarga todos los archivos en una misma carpeta.
2. Asegúrate de tener instaladas las librerías necesarias en tu Python:
   ```bash
   pip install numpy matplotlib
   ```
3. Abre el archivo `Tarea2_Opti.ipynb` usando Jupyter Notebook o VS Code y ejecuta las celdas.

El código procesará cada archivo automáticamente y mostrará los resultados estadísticos junto con los gráficos al terminar.****
