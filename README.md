# Portafolio profesional de Mario Ibañez

Este repositorio contiene la base de código y la configuración para el sitio web del portafolio profesional de Mario Ignacio Ibañez Castro. El sitio está diseñado como una plataforma interactiva de alto rendimiento para presentar su experiencia laboral, proyectos de desarrollo y ciencia de datos, educación y certificaciones.

## Descripción general

El proyecto está construido bajo una arquitectura moderna utilizando Astro, un framework web enfocado en el rendimiento y la entrega de interfaces rápidas mediante la minimización del uso de JavaScript en el cliente. El diseño visual se implementa con Tailwind CSS, garantizando una interfaz responsiva, limpia y optimizada para dispositivos móviles y de escritorio.

Adicionalmente, el repositorio integra un archivo de datos estructurado en formato YAML que actúa como la fuente de verdad para el currículum del desarrollador, facilitando el mantenimiento de la información profesional y la consistencia entre la web y los currículums impresos o en formato PDF.

## Problema que resuelve

Los profesionales de la ciencia de datos, la economía y la ingeniería en la nube a menudo necesitan una forma centralizada, dinámica y profesional de demostrar sus habilidades. Este repositorio resuelve los siguientes problemas comunes:

- **Falta de visibilidad interactiva**: Permite a reclutadores e interesados examinar de forma directa e intuitiva proyectos de aprendizaje automático, automatización cartográfica y desarrollo en la nube, superando las limitaciones de un currículum estático tradicional.
- **Mantenimiento complejo de la información**: Al centralizar los datos profesionales en un formato legible como YAML, se evita la necesidad de modificar el código HTML/Astro directamente para realizar actualizaciones de rutina en la trayectoria profesional.
- **Rendimiento web deficiente**: Al usar Astro, la página web resultante carga de forma casi instantánea, optimizando la experiencia del usuario y mejorando el posicionamiento en motores de búsqueda (SEO).

## Tecnologías utilizadas

El portafolio se apoya en un conjunto de tecnologías modernas del ecosistema web y de gestión de configuración:

- **Astro (versión 5.17.3)**: Utilizado como framework de desarrollo web para generar páginas estáticas optimizadas.
- **Tailwind CSS (versión 3.4.1)**: Utilizado para la maquetación y el diseño visual responsivo a través de estilos utilitarios modernos.
- **TypeScript (versión 5.3.3)**: Empleado para añadir tipado estático y robustez al código del sitio.
- **YAML**: Formato utilizado en el archivo `mario_master.yaml` para estructurar de manera legible toda la información profesional y personal.
- **Astro robots-txt**: Integración automática para la generación del archivo `robots.txt` que optimiza el rastreo del sitio por parte de buscadores.

## Estructura del repositorio

A continuación se detalla la organización de los directorios y archivos principales del proyecto:

- **`src/`**: Directorio principal del código fuente de la aplicación Astro.
  - **`src/components/`**: Componentes reutilizables de la interfaz de usuario, como `Header.astro`, `Experience.astro`, `Projects.astro`, `AboutMe.astro`, `Education.astro` y `Technologies.astro`.
  - **`src/layouts/`**: Plantillas base de diseño para estructurar el contenido de las páginas.
  - **`src/pages/`**: Páginas del sitio. La página de inicio está definida en `index.astro`.
- **`public/`**: Archivos estáticos de acceso directo para el navegador, como imágenes de proyectos, íconos y activos visuales.
- **`mario_master.yaml`**: Archivo de configuración maestro que recopila la información completa del perfil, fortalezas, historial laboral detallado, proyectos, certificaciones y educación.
- **`Mario Ibañez.pdf` y `Mario_Ibanez_CV_2026_Analista.pdf`**: Versiones de currículum listas para descarga desde el portafolio.
- **`package.json`**: Configuración de dependencias de Node.js y definición de scripts de ejecución.
- **`astro.config.mjs`**: Configuración del comportamiento del compilador de Astro y sus respectivas extensiones.
- **`tailwind.config.mjs`**: Configuración de las reglas y extensiones del framework de estilos CSS.

## Casos de uso específicos

Este repositorio está diseñado para los siguientes escenarios particulares:

- **Presentación de portafolio web**: Despliegue del sitio en plataformas de alojamiento estático (como Netlify, Vercel, GitHub Pages u Oracle Cloud Infrastructure) para ofrecer una tarjeta de presentación digital permanente y accesible desde cualquier navegador.
- **Demostración de habilidades técnicas**: Evidencia directa del manejo de tecnologías web modernas, diseño responsivo y optimización de rendimiento para un perfil enfocado en computación en la nube y análisis de datos.
- **Portabilidad de currículum**: Extracción o referencia de la información estructurada en el archivo maestro para alimentar otros sistemas de generación de perfiles.

## Cuándo utilizar este repositorio

Se recomienda utilizar o clonar este repositorio si:

- Se desea desplegar una versión local o en producción del sitio web del portafolio.
- Se requiere actualizar el historial laboral o añadir nuevos proyectos y certificaciones en el portafolio de Mario Ibañez.
- Se busca un ejemplo práctico de desarrollo de interfaces modernas utilizando componentes independientes en Astro combinados con Tailwind CSS.

## Instrucciones de instalación y uso local

Siga los pasos descritos a continuación para configurar y ejecutar el entorno de desarrollo en su máquina local.

### Requisitos previos

Debe contar con las siguientes herramientas instaladas en su sistema:

- Node.js (versión 18 o superior recomendada)
- Un gestor de paquetes de Node como npm (incluido con Node.js)

### Pasos de configuración

1. Instale las dependencias del proyecto utilizando el gestor de paquetes:
   ```bash
   npm install
   ```

2. Inicie el servidor de desarrollo local:
   ```bash
   npm run dev
   ```
   O de forma alternativa:
   ```bash
   npm start
   ```

3. Abra su navegador web y navegue a la dirección local que se muestra en la terminal, que por lo general corresponde a `http://localhost:4321`.

4. Realice cambios en los archivos de la carpeta `src/`. Astro aplicará las actualizaciones en tiempo real en su navegador mediante su sistema de recarga rápida.

5. Para construir el proyecto para su distribución en producción, ejecute:
   ```bash
   npm run build
   ```

6. Si desea previsualizar localmente la compilación de producción antes de subir los archivos, utilice el comando:
   ```bash
   npm run preview
   ```

## Datos y fuente de verdad única

La información mostrada en el sitio refleja los datos estructurados en `mario_master.yaml`. Es fundamental mantener este archivo actualizado cuando se realicen cambios significativos en el historial profesional. Aunque los datos del sitio están maquetados en componentes Astro como `Experience.astro` o `Projects.astro`, el archivo YAML representa la especificación maestro para mantener la alineación con las versiones de currículum en formato PDF distribuidas.

## Licencia

Este proyecto cuenta con una licencia cuyos términos detallados se encuentran disponibles en el archivo `LICENSE.md` dentro de este mismo repositorio.
