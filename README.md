# Curriculum Vitae | Jose Luis Churo Vicente

[![Render CV](https://github.com/josheluis96/curriculum-vitae/actions/workflows/render_cv.yml/badge.svg)](https://github.com/josheluis96/curriculum-vitae/actions/workflows/render_cv.yml)
![YAML](https://img.shields.io/badge/format-YAML-cb171e?style=flat-square&logo=yaml)
![RenderCV](https://img.shields.io/badge/built%20with-RenderCV-blueviolet?style=flat-square)

Este repositorio contiene mi trayectoria profesional y habilidades técnicas estructuradas como **código (YAML)**.

El objetivo es mantener una "fuente de la verdad" versionada de mi perfil, aplicando principios de **CI/CD** para generar automáticamente el documento final.

## 📥 Descarga Rápida (PDF)

No es necesario clonar el repositorio. El sistema genera una nueva versión automáticamente con cada actualización.

👉 **[Descargar Último CV Actualizado (PDF)](https://github.com/josheluis96/curriculum-vitae/releases/latest)**

## ⚙️ Automatización (CI/CD)

Este proyecto utiliza **GitHub Actions** para compilar el CV.
Cada vez que se realiza un `push` a la rama `main` con cambios en el archivo `curriculum.yaml`:

1.  Se activa un workflow de integración continua.
2.  **RenderCV** convierte el YAML a LaTeX y genera el PDF.
3.  El PDF resultante se publica automáticamente en los **Releases** del repositorio.

Puedes ver el archivo de configuración aquí: [render_cv.yml](.github/workflows/render_cv.yml).

## 📄 Contenido del CV

El archivo principal [`curriculum.yaml`](curriculum.yaml) incluye:

-   **Perfil:** Arquitectura de Microservicios, Data Engineering y Desarrollo Móvil.
-   **Experiencia:** Banco Pichincha, Global Hitss, Sudamericana de Software.
-   **Tecnologías:** NestJS, Kafka, AWS, React Native, Hadoop, etc.
-   **Certificaciones:** Scrum Master, Quarkus, Spring Boot, etc.

## 🛠 Estructura de Datos

El esquema sigue la estructura estándar de RenderCV:

```yaml
cv:
  name: "Jose Luis Churo Vicente"
  email: "..."
  sections:
    summary: String
    experience: Array<Job>
    education: Array<School>
    skills: Array<Category>