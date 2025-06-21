# Lanzador de Moneda con Streamlit

Esta es una aplicación interactiva construida con **Streamlit** que simula el lanzamiento de una moneda tantas veces como el usuario lo decida. El objetivo es observar cómo varía la frecuencia relativa de un resultado (por ejemplo, "cara") con más repeticiones, ilustrando así el concepto de **ley de los grandes números**.

## 🎯 Funcionalidades

- Selecciona el número de lanzamientos usando un slider (de 1 a 1000).
- Ejecuta la simulación con un botón.
- Visualiza en tiempo real cómo evoluciona la media de resultados.
- Guarda el historial de experimentos dentro de la sesión.
- Presenta los resultados en una tabla interactiva.

## 📦 Requisitos

- Python 3.7 o superior
- Streamlit
- pandas
- scipy

Puedes instalarlos con:

pip install streamlit pandas scipy

## 🚀 Cómo ejecutar la app
1. Clona este repositorio:

git clone https://https://github.com/Eme48/streamlit_test/
cd streamlit_test

2. Ejecuta la aplicación con:

streamlit run app.py

Si tienes problemas con el comando, puedes usar:

python -m streamlit run app.py

3. Se abrirá una ventana en tu navegador en http://localhost:8501.

## 📊 Ejemplo visual
La app genera un gráfico en tiempo real como este:

| iteración | media acumulada |
|-----------|------------------|
|    1      |       1.0        |
|    2      |       0.5        |
|    3      |       0.66       |

## 💡 Futuras mejoras
- Botón para reiniciar el historial de experimentos.
- Descarga de resultados como archivo .csv.
- Histograma de distribución final.

## Licencia
MIT License. Uso libre para fines educativos y experimentales.

Desarrollado por Emerson Ríos ✨
