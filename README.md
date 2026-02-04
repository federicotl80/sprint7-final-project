# sprint7-final-project
Análisis de una empresa de telecomunicaciones

# 📊 Proyecto 6 – Análisis de una Empresa de Telecomunicaciones (ConnectaTel)

## 🎯 Objetivo del Proyecto

El objetivo de este proyecto es analizar el comportamiento real de uso de los servicios móviles (llamadas y mensajes) de los clientes de **ConnectaTel**, una empresa de telecomunicaciones con operaciones en México y Colombia.

El análisis busca:
- Identificar **patrones de uso** de los clientes.
- Detectar **comportamientos atípicos (outliers)**.
- Crear **segmentos de clientes** por edad y nivel de uso.
- Generar **insights accionables** que ayuden a optimizar la oferta de planes y mejorar la experiencia del usuario.

---

## 🗂️ Datasets Utilizados

El proyecto utiliza tres archivos CSV:

- **`plans.csv`**  
  Contiene el catálogo de planes móviles (precio, minutos incluidos, GB incluidos y costos por consumo extra).

- **`users_latam.csv`**  
  Información de los usuarios: edad, ciudad, país, fecha de registro y plan contratado.

- **`usage.csv`**  
  Registro del uso real de los servicios: llamadas realizadas, duración de llamadas y mensajes enviados.

Estos datasets se integran para analizar el comportamiento de uso por cliente y por segmento.

---

## 🔄 Etapas del Análisis

El proyecto sigue un flujo estructurado de análisis de datos:

1. **Carga y exploración inicial de los datos**  
   Revisión de estructura, tamaño y tipos de datos.

2. **Identificación de problemas de calidad**  
   Detección de valores nulos, fechas fuera de rango y datos inconsistentes.

3. **Limpieza y preparación de datos**  
   Conversión de tipos, estandarización de fechas y manejo de valores inválidos.

4. **Estadísticas descriptivas**  
   Cálculo de medidas clave para entender el comportamiento típico y extremo.

5. **Visualización y detección de outliers**  
   Uso de histogramas y boxplots para identificar patrones y valores atípicos.

6. **Segmentación de clientes**  
   - Segmentación por edad (Joven, Adulto, Adulto Mayor)  
   - Segmentación por nivel de uso (Uso medio, Alto uso)

7. **Visualización de segmentos**  
   Gráficos para analizar la distribución de usuarios por grupo.

8. **Insight ejecutivo**  
   Interpretación de resultados y recomendaciones comerciales.

---

## ▶️ Cómo Ejecutar el Notebook

### Opción recomendada: Google Colab

1. Abre este repositorio en GitHub.
2. Da clic en el archivo del notebook (`.ipynb`).
3. Presiona el botón **“Open in Colab”** (o copia la URL y ábrela en https://colab.research.google.com).
4. Sube los archivos `plans.csv`, `users_latam.csv` y `usage.csv` al entorno de Colab.
5. Ejecuta las celdas **en orden**, de arriba hacia abajo.

---

## 🔁 Guía de Reproducción

Para reproducir correctamente el análisis:

1. Asegúrate de que los archivos CSV estén cargados en el mismo entorno que el notebook.
2. Ejecuta todas las celdas en el orden original.
3. No modifiques los nombres de columnas ni los archivos.
4. Verifica que las visualizaciones y conteos coincidan con los resultados mostrados.
5. Revisa la sección final de **Insight Ejecutivo** para entender las conclusiones del negocio.

---

## 🧠 Resultados Clave

- El **93% de los usuarios** presenta un nivel de **uso medio**.
- El **6.98%** corresponde a usuarios de **alto uso**, clave para ingresos.
- El segmento **Adulto (30–59 años)** representa más del **50%** de los clientes.
- Se detectaron **usuarios con uso extremo**, relevantes para planes premium o monitoreo.
- La segmentación permite diseñar **planes y campañas más eficientes**.

---

## 🛠️ Herramientas Utilizadas

- Python  
- Jupyter Notebook  
- pandas  
- numpy  
- seaborn  
- matplotlib  

---

## 👤 Autor

Proyecto realizado como parte del **Bootcamp de Data Analytics – TripleTen**.
