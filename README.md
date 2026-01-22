# Curriculum Vitae | Jose Luis Churo Vicente

![YAML](https://img.shields.io/badge/format-YAML-cb171e?style=flat-square&logo=yaml)
![RenderCV](https://img.shields.io/badge/compatible-RenderCV-blueviolet?style=flat-square)
[![Render CV](https://github.com/josheluis96/curriculum-vitae/actions/workflows/render_cv.yml/badge.svg)](https://github.com/josheluis96/curriculum-vitae/actions/workflows/render_cv.yml)
![Status](https://img.shields.io/badge/status-Open%20to%20offers-green?style=flat-square)


Este repositorio contiene mi trayectoria profesional, habilidades técnicas y certificaciones estructuradas en formato **YAML**.

El objetivo de este proyecto es mantener una "fuente de la verdad" de mi experiencia laboral, aplicando principios de versionamiento y datos estructurados a mi perfil profesional.

## 📄 Sobre el CV

El archivo principal `cv.yaml` contiene la siguiente información estructurada:

- **Perfil Profesional:** Resumen de experiencia en desarrollo Full Stack, Microservicios y Data Engineering.
- **Experiencia Laboral:** Historial detallado en empresas como Banco Pichincha, Global Hitss y Sudamericana de Software.
- **Stack Tecnológico:**
    - **Backend:** NestJS, Java (Spring Boot/Quarkus), Node.js.
    - **Frontend & Mobile:** React Native, Angular.
    - **Data & Cloud:** AWS, Kafka, Hadoop, Docker/Kubernetes.
- **Educación y Certificaciones:** Títulos académicos y cursos relevantes validados.

## 🎨 Generación de PDF (RenderCV)

Este archivo `cv.yaml` ha sido estructurado para ser compatible con **RenderCV**. Puedes generar una versión en PDF profesional y basada en LaTeX directamente desde el navegador:

1. Visita **[RenderCV App](https://app.rendercv.com/)**.
2. Sube o pega el contenido del archivo `cv.yaml`.
3. Selecciona tu plantilla preferida (Classic, Modern, Sb2nov, etc.).
4. Descarga el PDF compilado automáticamente.

## 🛠 Estructura del YAML

El esquema de datos sigue la siguiente estructura básica:

```yaml
cv:
  name: String
  contact: Object
  sections:
    summary: String
    experience: Array<Job>
    education: Array<School>
    skills: Array<Category>