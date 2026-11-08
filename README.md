# Orbit Terminal | Official Website

**Sitio web oficial de Orbit Terminal, una plataforma experimental de hardware, electrónica y software desarrollada por Miguel Rodríguez Saiz dentro de Ardu Solutions.**

[![Website](https://img.shields.io/badge/Website-Online-16A34A?style=flat-square)](https://ardu01.github.io/orbit-web/)
![HTML5](https://img.shields.io/badge/HTML5-Web-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Design-1572B6?style=flat-square&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Web-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Blender](https://img.shields.io/badge/3D-Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Hosting-GitHub_Pages-222222?style=flat-square&logo=github)
![License](https://img.shields.io/badge/License-Apache--2.0-2563EB?style=flat-square)

---

## Descripción

**Orbit Terminal Web** es la página oficial de presentación y documentación visual de **Orbit Terminal**, un proyecto experimental que combina informática, electrónica, fabricación digital y desarrollo de software.

Su objetivo es mostrar el diseño, los componentes y la evolución de una consola informática portátil de tipo *cyberdeck*, concebida como plataforma de experimentación y banco de pruebas tecnológico.

Orbit Terminal integra un ordenador HP, una Raspberry Pi 4 y componentes electrónicos dentro de una carcasa personalizada diseñada mediante CAD y concebida para fabricación mediante impresión 3D.

La web documenta las diferentes etapas del proyecto mediante fotografías reales, renders tridimensionales y animaciones de montaje.

**Desarrollador:** Miguel Rodríguez Saiz  
**Organización:** Ardu Solutions  
**Categoría:** Desarrollo Web / Hardware / Electrónica / Diseño CAD  
**Proyecto principal:** Orbit Terminal  
**Publicación:** GitHub Pages

## Acceder a la web

**[Visitar la web oficial de Orbit Terminal](https://ardu01.github.io/orbit-web/)**

## Características

- Presentación oficial de Orbit Terminal.
- Información sobre el hardware y sus componentes.
- Documentación visual de la construcción.
- Fotografías reales del prototipo.
- Línea de tiempo de evolución del proyecto.
- Animaciones tridimensionales de montaje.
- Visualizaciones creadas mediante Blender.
- Información sobre diseño CAD e impresión 3D.
- Presentación del entorno Orbit OS.
- Capturas de la interfaz del sistema.
- Indicadores del estado de desarrollo.
- Diseño web adaptable.
- Publicación mediante GitHub Pages.

## Tecnologías

| Tecnología | Función |
|---|---|
| HTML5 | Estructura y contenido |
| CSS3 | Diseño visual |
| JavaScript | Interactividad y animaciones |
| Blender | Renderizado y animación 3D |
| OpenSCAD | Modelado CAD del proyecto |
| WebP | Imágenes optimizadas |
| GitHub Pages | Alojamiento y publicación |
| Git | Control de versiones |

La web funciona como un sitio estático sin frameworks ni dependencias externas de ejecución.

## Proyecto principal: Orbit Terminal

Orbit Terminal es una consola informática experimental que combina diferentes plataformas de hardware dentro de una estructura personalizada.

### Componentes principales

| Componente | Función |
|---|---|
| Ordenador HP | Plataforma informática principal |
| Raspberry Pi 4 | Ejecución de Orbit OS y funciones de control |
| Pantalla MSI PRO MP161 E2U | Visualización de 15,6 pulgadas |
| Carcasa personalizada | Estructura del dispositivo |
| Componentes electrónicos | Integración y experimentación |
| Almacenamiento interno | Soporte de datos |
| Orbit OS | Entorno de software del proyecto |

### Diseño CAD

El proyecto incluye el desarrollo de piezas mecánicas personalizadas mediante OpenSCAD.

Entre los componentes diseñados se encuentran:

- Base y carcasa.
- Bisel de pantalla.
- Soportes internos.
- Bandejas de componentes.
- Soportes de almacenamiento.
- Placas de conectores.
- Elementos de fijación.
- Controles y piezas auxiliares.

Las dimensiones y determinadas características de diseño se encuentran sujetas a revisión, por lo que la documentación distingue entre datos confirmados y medidas provisionales.

## Documentación visual

### Evolución del prototipo

La web incorpora una sección dedicada a mostrar las distintas etapas de desarrollo mediante fotografías reales.

Esta línea de tiempo permite observar el progreso del hardware y los cambios realizados durante la construcción.

### Animaciones 3D

El sitio incluye animaciones de montaje renderizadas con Blender a partir de geometría CAD del proyecto.

Se ofrecen representaciones visuales de diferentes estilos para ilustrar la disposición y ensamblaje de los componentes.

**Las animaciones 3D son representaciones ilustrativas y no deben confundirse con grabaciones reales del montaje.**

### Orbit OS

La página también presenta el entorno de software desarrollado para Orbit Terminal.

Las capturas publicadas corresponden a recursos reales del proyecto Control-deck.

La demostración animada del cambio entre sistemas se identifica como ilustrativa hasta disponer de una grabación real.

## Estructura del repositorio

Entre sus componentes principales se encuentran:

| Archivo o directorio | Función |
|---|---|
| `index.html` | Página principal |
| `montaje.js` | Interactividad de montaje |
| `assets/img/` | Imágenes y renders |
| `assets/fotos/` | Fotografías reales |
| `assets/montaje/` | Secuencias y renders 3D |
| `assets/demo/` | Animaciones ilustrativas |
| `assets/screenshots/` | Capturas del software |
| `README.md` | Documentación principal |
| `LICENSE` | Licencia Apache 2.0 |
| `NOTICE` | Créditos y atribuciones |

## Ejecución local

Clonar el repositorio:

```bash id="k9a1mz"
git clone https://github.com/ardu01/orbit-web.git
cd orbit-web
```

Iniciar un servidor HTTP local:

```bash id="vw92bx"
python3 -m http.server 8000
```

Acceder desde el navegador a:

`http://localhost:8000`

La web no requiere instalar dependencias adicionales para visualizar su contenido estático.

## Estado del proyecto

Orbit Terminal es un proyecto experimental que dispone de prototipos, documentación de construcción y desarrollo de software asociado.

La web diferencia los estados de sus elementos mediante las categorías:

- **Terminado:** elemento documentado como completado.
- **En pruebas:** componente en evaluación.
- **Pendiente:** elemento todavía no completado o sin verificar.

Algunas características permanecen pendientes de medición o confirmación.

Los datos técnicos definitivos deben consultarse en la documentación del proyecto principal.

## Proyecto de hardware y software

El desarrollo técnico de Orbit Terminal se encuentra en:

**[Control-deck — GitHub](https://github.com/Sopa-IA/Control-deck)**

Este repositorio web se dedica exclusivamente a la presentación, documentación visual y seguimiento del proyecto.

El diseño CAD, las configuraciones de hardware y el software asociado se mantienen en el repositorio principal.

## Autor

**Miguel Rodríguez Saiz**

Diseño, desarrollo y documentación del proyecto.

**Ardu Solutions** — Desarrollo de software, electrónica, sistemas, inteligencia artificial y soluciones tecnológicas.

- **Web oficial:** https://ardu01.github.io/orbit-web/
- **Proyecto principal:** https://github.com/Sopa-IA/Control-deck
- **Portfolio:** https://ardu01.github.io/proyectos/
- **Ardu Solutions:** https://ardusolutions.pages.dev/
- **GitHub:** https://github.com/ardu01

## Licencia

El código y los contenidos cubiertos por la licencia principal del repositorio se distribuyen bajo **Apache License 2.0**.

Los modelos y recursos de terceros conservan sus respectivas licencias, incluyendo determinados componentes bajo CC0 y CC BY-SA 4.0.

Las fotografías reales del prototipo son propiedad de **Miguel Rodríguez Saiz** y no se distribuyen bajo Apache 2.0.

Los renders que incorporan geometría sujeta a CC BY-SA 4.0 mantienen las condiciones de atribución y distribución correspondientes.

Consultar [LICENSE](LICENSE) y [NOTICE](NOTICE) para más información.

---

**© 2026 Miguel Rodríguez Saiz · Ardu Solutions**

*Orbit Terminal — Hardware, software and engineering in one platform.*
