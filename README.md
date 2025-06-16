# 🏙️ UrbanRisk – Predicción de zonas de riesgo urbano en Valencia

**UrbanRisk** es una aplicación interactiva desarrollada con Streamlit que identifica y predice zonas de riesgo urbano en la ciudad de Valencia. Utiliza datos abiertos y modelos de machine learning para evaluar la probabilidad de incidentes como accidentes de tráfico, altos niveles de contaminación o situaciones que afectan al bienestar urbano.

---

## 🚀 Funcionalidades principales

- Visualización de mapas con niveles de contaminación, ruido, tráfico y accidentes.
- Predicción del riesgo urbano según ubicación, hora y condiciones ambientales.
- Recomendaciones personalizadas para evitar zonas peligrosas.
- Modelos explicables con indicadores de importancia de variables.

---

## 📊 Fuentes de datos utilizadas

- Contaminación atmosférica: [Open Data Valencia](https://valencia.opendatasoft.com/explore/dataset/qualitat-de-laire)
- Tráfico y accidentes: [Open Data Valencia](https://valencia.opendatasoft.com/explore/dataset/dades-trafic)
- Zonas verdes y servicios de salud
- Meteorología: [AEMET API](https://opendata.aemet.es/)
- Datos sintéticos de criminalidad (simulados)

---

## 🧠 Metodología

- Limpieza y unificación de datos multifuente.
- Análisis exploratorio y generación de variables.
- Entrenamiento de modelos de clasificación (Random Forest).
- Visualización geoespacial con Folium y Streamlit.
- Interpretabilidad con SHAP y gráficos de importancia.

---

## 📦 Estructura

urbanrisk-valencia/
├── data/
├── notebooks/
├── app/
├── models/
├── media/
└── README.md


---

## ▶️ Demo en vídeo

👉 [Enlace al vídeo explicativo (próximamente)](#)

---

## 🌐 Link a la app

👉 [App online (próximamente)](#)

---

## 👥 Autores

- Luminita Ciobanu – [@lumixcb](https://github.com/lumixcb)
- *(Aquí puedes añadir más miembros si es trabajo en grupo)*

---

## 📋 Requisitos

Instala las dependencias con:

```bash
pip install -r requirements.txt
