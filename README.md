<p align="center">
  <img src="assets/logo.png" alt="ModernAsh logo – símbolo minimalista de un ave/phoenix emergiendo de cenizas con degradado naranja/rojo y la palabra ModernAsh en tipografía sans moderna" width="220">
</p>

# ModernAsh – Documentación de servicios y material comercial

Este repositorio centraliza la documentación de **ModernAsh**, una startup de consultoría y servicios enfocada en:

1. **Modernización de aplicaciones legacy hacia arquitecturas modernas en AWS**  
2. **Modernización del proceso de desarrollo con IA generativa**, integrando la IA como un integrante más del equipo (ModernAsh DevEngage.AI)

Aquí vas a encontrar:

- Textos completos para publicar en **AWS Marketplace**  
- Contenidos para **landing comercial** (web)  
- Material para **pitch deck** (presentaciones a clientes, partners e inversores)

---

## Estructura general del repositorio

> Ajustá rutas/carpetas según cómo organices el proyecto.  
> En este README se asume que todos los `.md` están en la raíz del repo.

- `modernash-aws-marketplace-product.md`  
- `modernash-landing-es.md`  
- `modernash-pitch-deck.md`  
- `modernash-devengage-ai-aws-marketplace-product.md`  
- `modernash-devengage-landing-es.md`  
- `modernash-devengage-pitch-deck.md`  
- `README.md` (este archivo)

---

## 1. Servicio: Modernización de aplicaciones legacy en AWS

### 1.1 Descripción general

ModernAsh ofrece un servicio de **modernización de aplicaciones legacy** (por ejemplo COBOL, mainframe y Java antiguo) hacia **Java, Python o Node.js** desplegado sobre **AWS**, usando:

- **IA asistida** para análisis y migración de código  
- Buenas prácticas de **arquitectura moderna** (layered, hexagonal, microservicios, event-driven, etc.)  
- Una batería completa de **tests unitarios e integración**  
- **Documentación y diagramas** (UML, C4, README, HOWTOs) en el repositorio destino  
- Capacidad de **actualizar Java desde versiones viejas a versiones modernas LTS**, modernizando también la arquitectura

El servicio se ofrece como un **engagement de bajo costo y alcance acotado (PoC)** para reducir riesgo y abrir la puerta a proyectos de modernización completos.

### 1.2 Archivos relacionados

- 📄 **AWS Marketplace (EN)**  
  `modernash-aws-marketplace-product.md`  
  Contiene la descripción completa del producto “ModernAsh Legacy Modernization PoC – AI-Assisted Low-Cost Introductory Engagement on AWS” para publicar como **Professional Services** en AWS Marketplace.

- 🌐 **Landing comercial (ES)**  
  `modernash-landing-es.md`  
  Texto orientado a la web de ModernAsh en español, explicando el servicio de modernización, beneficios, cómo trabajamos y próximos pasos.

- 📊 **Pitch deck (ES)**  
  `modernash-pitch-deck.md`  
  Estructura de presentación en formato “slide por slide” para usar en presentaciones comerciales, partners, AWS, etc.

---

## 2. Servicio: ModernAsh DevEngage.AI – GenAI para equipos de desarrollo

### 2.1 Descripción general

**ModernAsh DevEngage.AI** es un servicio de consultoría para **integrar IA generativa** (GitHub Copilot, LLMs, agentes) en el **ciclo completo de desarrollo de software**:

- IA como un **integrante más del equipo**, encargada de:
  - Tareas repetitivas y no creativas (boilerplate, scaffolding)
  - Generación y mantenimiento de tests (unitarios, integración)
  - Documentación (README, HOWTOs, comentarios, changelogs)
  - Refactors y sugerencias de mejoras
- **Agnóstico al lenguaje** y **agnóstico a la topología del equipo**:
  - Java, Python, Node.js, .NET, front-end, data/ML, etc.
  - Squads de producto, equipos de plataforma, capítulos, etc.
- **Compatible con Scrum, Kanban y derivados**:
  - No requiere cambiar de framework ni de proceso
- Implementación de **Spec Driven Development (SDD)**:
  - La *spec* es el centro: IA y humanos generan código/tests/docs alineados a esa especificación
- Objetivo final:
  - **Más calidad**, **más seguridad**, **más pruebas**, **más documentación** y **más producción**
  - Sin quemar al equipo, liberando tiempo para diseño, arquitectura y decisiones de negocio

### 2.2 Archivos relacionados

- 📄 **AWS Marketplace (EN)**  
  `modernash-devengage-ai-aws-marketplace-product.md`  
  Descripción completa del producto “ModernAsh DevEngage.AI – GenAI-Driven Engineering Enablement on AWS” para publicarlo como **Professional Services** en AWS Marketplace.

- 🌐 **Landing comercial (ES)**  
  `modernash-devengage-landing-es.md`  
  Contenido en español orientado a la web, explicando qué es DevEngage.AI, problemas que resuelve, beneficios y cómo trabajamos.

- 📊 **Pitch deck (ES)**  
  `modernash-devengage-pitch-deck.md`  
  Estructura de presentación para explicar DevEngage.AI a clientes, partners e inversores (slide por slide).

---

## 3. Cómo usar estos documentos

### 3.1 Para AWS Marketplace

- Tomar los archivos:
  - `modernash-aws-marketplace-product.md`
  - `modernash-devengage-ai-aws-marketplace-product.md`
- Adaptar:
  - Campos de **short description**, **pricing**, **contacto** y otros límites de caracteres según los formularios de AWS Marketplace.
- Copiar/pegar el contenido en el **formulario de creación de producto de Professional Services**.
- Ajustar detalles legales y comerciales (SoW, T&Cs) según lo que defina el área legal/fiscal.

### 3.2 Para la web (landing)

- Usar:
  - `modernash-landing-es.md`
  - `modernash-devengage-landing-es.md`
- Adaptar el contenido a la estructura del sitio (secciones, componentes, CTAs).
- Mantener el mensaje consistente:
  - ModernAsh = modernización de sistemas + modernización de cómo se desarrolla (DevEngage.AI).

### 3.3 Para pitch decks y presentaciones

- Usar:
  - `modernash-pitch-deck.md`
  - `modernash-devengage-pitch-deck.md`
- Cada archivo está estructurado como:
  - `Slide 1 – Título...`
  - `Slide 2 – ...`
- Convertir esos bloques en slides en tu herramienta preferida (PowerPoint, Keynote, Google Slides, etc.).

---

## 4. Convenciones y estilo

- **Idioma**:
  - Documentos para AWS Marketplace: **inglés**.  
  - Landings y pitch decks internos/comerciales: **español**, salvo que se indiquen versiones en inglés más adelante.

- **Logo**:
  - Todos los documentos deben usar el logo:
    ```html
    <p align="center">
      <img src="assets/logo.png" alt="ModernAsh logo – símbolo minimalista de un ave/phoenix emergiendo de cenizas con degradado naranja/rojo y la palabra ModernAsh en tipografía sans moderna" width="220">
    </p>
    ```

- **Nombres de servicios**:
  - Servicio de modernización:  
    “**ModernAsh Legacy Modernization PoC – AI-Assisted Low-Cost Introductory Engagement on AWS**”
  - Servicio de IA para equipos de desarrollo:  
    “**ModernAsh DevEngage.AI – GenAI-Driven Engineering Enablement on AWS**”

---

## 5. Próximos pasos / To-Do (sugerido)

- [ ] Ajustar nombres de archivos y directorios si se decide una estructura `/docs`, `/marketplace`, `/pitch`, etc.  
- [ ] Revisar textos con equipo legal/comercial (precio, disclaimers, NDA, etc.).  
- [ ] Crear versiones **EN** de los pitch decks si se apunta a inversores o partners globales.  
- [ ] Agregar ejemplos concretos de clientes (cuando existan) como nuevos `.md` o secciones adicionales.

---

Si tenés dudas sobre qué archivo usar para cada contexto, el resumen rápido es:

- **Marketplace** → archivos `*-aws-marketplace-product.md`  
- **Web** → archivos `*-landing-es.md`  
- **Presentaciones** → archivos `*-pitch-deck.md`
