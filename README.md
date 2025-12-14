# Plataforma de Análisis: Estrés Hídrico e Impacto de Género

Este repositorio contiene el código fuente y la documentación técnica de la plataforma web desarrollada para el monitoreo, análisis y visualización del impacto social de la escasez hídrica en comunidades rurales de Ecuador, con un enfoque específico en la brecha de género.

## Descripción del Proyecto

El proyecto aborda la problemática del acceso al agua desde una perspectiva dual: técnica y social. Mediante el uso de tecnologías de simulación de datos y visualización interactiva, la plataforma busca evidenciar la carga desproporcionada que asumen las mujeres en el acarreo y gestión del agua, correlacionándola con indicadores técnicos de disponibilidad y calidad del recurso.

La solución integra un Data Warehouse simulado con visualizaciones en Tableau, presentadas a través de una interfaz web responsiva y profesional.

## Objetivos del Sistema

* **Visibilización Social:** Cuantificar y exponer las horas invertidas por mujeres en el acarreo de agua mediante el análisis de 2.500 registros de encuestas simuladas.
* **Monitoreo Técnico:** Presentar indicadores (KPIs) sobre niveles de tanques de almacenamiento, calidad del agua y porcentajes de estrés hídrico.
* **Soporte a la Toma de Decisiones:** Centralizar la información en dashboards interactivos para facilitar la intervención de organismos no gubernamentales (ONGs) y entidades estatales.

## Arquitectura Tecnológica

El desarrollo del proyecto se ha estructurado utilizando las siguientes tecnologías:

### Frontend y Diseño Web
* **HTML5 Semántico:** Estructura limpia y organizada para la navegación entre módulos.
* **CSS3:** Diseño responsivo (Mobile-First) utilizando Flexbox y CSS Grid. Se implementó una paleta de colores corporativa ("Corporate Blue") para transmitir seriedad y confianza institucional.
* **Integración:** Embed API de Tableau para la incrustación fluida de dashboards analíticos.

### Ingeniería de Datos (Backend Simulado)
* **Python:** Scripts de generación de datos sintéticos para simular escenarios de encuestas y lecturas de sensores IoT.
* **PostgreSQL:** Base de datos relacional utilizada para el modelado y almacenamiento estructurado de la información (Data Warehousing).

### Visualización e Inteligencia de Negocios
* **Tableau Public:** Desarrollo de dashboards interactivos para la exploración de datos geográficos (mapas de calor) y estadísticos.

## Estructura del Repositorio

La organización de los archivos en el repositorio es la siguiente:

* **index.html**: Página de aterrizaje (Landing Page). Presenta el resumen ejecutivo del proyecto y los KPIs principales de alto nivel.
* **dashboard-social.html**: Módulo de análisis social. Contiene la integración del dashboard de género, tiempos de acarreo y demografía.
* **dashboard-tecnico.html**: Módulo de ingeniería. Visualiza los datos técnicos de la infraestructura hídrica y calidad del suministro.
* **css/**: (Opcional si decidieras separar estilos) Hojas de estilo en cascada.
* **img/**: Recursos gráficos y fotografías del proyecto.

## Despliegue y Visualización

Para visualizar el proyecto en un entorno local:

1. Clone este repositorio o descargue los archivos ZIP.
2. Asegúrese de mantener la estructura de carpetas (imágenes en su directorio correspondiente).
3. Ejecute el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Edge).
4. La navegación entre los módulos "Social" y "Técnico" se realiza a través de la barra de navegación superior o los botones de acción en la página principal.

## Nota Legal y Datos

**Aviso de Simulación:** Los datos presentados en esta plataforma (encuestas, mediciones de sensores y geolocalización) han sido generados computacionalmente mediante algoritmos en Python y PostgreSQL con fines estrictamente académicos y de demostración técnica. No representan mediciones en tiempo real de comunidades específicas.

## Autores

Proyecto desarrollado por:

* **Ricardo Espinosa**
* **Juan Diego Guerrero**

---
© 2025 Proyecto de Investigación Agua y Género. Todos los derechos reservados.
