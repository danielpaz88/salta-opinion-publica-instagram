# 🇦🇷 Análisis de Opinión Pública en Salta (Instagram)

[![Python 3.12](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Selenium](https://img.shields.io/badge/Selenium-4.0-green.svg)](https://www.selenium.dev/)
[![spaCy](https://img.shields.io/badge/spaCy-3.0-blueviolet.svg)](https://spacy.io/)

**¿Qué piensan los salteños?** Este proyecto responde a esa pregunta mediante el análisis de **más de 2.700 comentarios** extraídos de Instagram de los principales portales de noticias de Salta. Utiliza técnicas de **scraping, procesamiento de lenguaje natural (NLP) y visualización** para identificar sentimientos, emociones, temas y entidades de la conversación pública.

---

## 📊 Vista rápida

| Métrica | Valor |
|---------|-------|
| Comentarios analizados | 2.731 |
| Perfiles de Instagram | 8 |
| Período de análisis | 1 al 15 de septiembre de 2026 |
| Temas detectados | 8 (Religión, Política, Economía, Seguridad, Salud, Educación, Infraestructura, Familia) |

### Nube de palabras general
![Nube general](https://raw.githubusercontent.com/tu-usuario/salta-opinion-publica-instagram/main/docs/wordcloud_general.png)

---

## 🎯 Objetivos

- Capturar la **voz ciudadana** sin filtros a partir de comentarios espontáneos.
- Identificar **preocupaciones clave** (seguridad, economía, política, etc.).
- Medir **sentimiento y emociones** asociadas a cada tema.
- Detectar **entidades** mencionadas (Milei, Malvinas, Trump, etc.).
- Visualizar patrones mediante **nubes de palabras** y evolución temporal.

---

## 🧰 Tecnologías utilizadas

| Herramienta | Uso |
|-------------|-----|
| **Python 3.12** | Lenguaje principal |
| **Selenium** | Automatización del navegador para scraping |
| **BeautifulSoup** | Extracción de comentarios desde HTML |
| **PySentimiento** | Análisis de sentimiento y emociones (BERT) |
| **spaCy** | Extracción de entidades (NER) y lematización |
| **WordCloud** | Generación de nubes de palabras |
| **Pandas** | Manipulación y análisis de datos |
| **Matplotlib** | Visualización |

---

## 📂 Estructura del proyecto
