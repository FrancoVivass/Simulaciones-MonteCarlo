# Simulaciones de Montecarlo - Presentación Reveal.js

Presentación interactiva sobre Simulaciones de Montecarlo desarrollada con Reveal.js para el curso de Investigación Operativa.

## 📋 Descripción

Esta presentación explica de manera didáctica el método de Simulación de Montecarlo, incluyendo conceptos básicos, aplicaciones prácticas, ventajas, desventajas y un ejemplo completo en Python.

## 👥 Autores

- **Grupo 5**
- San Román Matías
- Vivas Franco
- **Curso:** Investigación Operativa

## 🚀 Características

- ✅ Presentación interactiva con Reveal.js
- ✅ Tema personalizado: fondo negro con texto rojo
- ✅ Animaciones y transiciones suaves
- ✅ Navegación por teclado y controles visuales
- ✅ Código Python con resaltado de sintaxis
- ✅ Imágenes ilustrativas
- ✅ Contenido completo y profesional
- ✅ Responsive design

## 📁 Estructura del Proyecto

```
Investigacion Operativa/
│
├── index.html              # Archivo principal de la presentación
├── styles.css              # Estilos personalizados
├── README.md               # Este archivo
│
├── Imagenes/               # Carpeta con imágenes utilizadas
│   ├── CasinoMonteCarlo.PNG
│   ├── comportamiento-probable.PNG
│   ├── evento-incierto.PNG
│   ├── finanzas.PNG
│   ├── gestion-de-proyectos.PNG
│   ├── ingenieria-o-produccion.PNG
│   ├── Linea-que-representa-una-simulacion-distinta.PNG
│   ├── numero-generado-al-azar.PNG
│   ├── paso-a-paso.PNG
│   ├── rango-de-resultados.PNG
│   ├── regocios-o-marketing.PNG
│   ├── repeticiones-o-simulaciones.PNG
│   └── resultado-aleatorio.PNG
│
└── reveal.js-master/       # Librería Reveal.js (local)
    ├── dist/
    │   ├── reveal.css
    │   ├── reveal.js
    │   └── theme/
    └── plugin/
        ├── highlight/
        ├── markdown/
        └── notes/
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **Reveal.js 4.3.1** - Framework para presentaciones
- **Highlight.js** - Resaltado de sintaxis para código

## 📦 Instalación

### Opción 1: Usar directamente (Recomendado)

1. Clona o descarga este repositorio
2. Abre el archivo `index.html` en tu navegador web
3. ¡Listo! La presentación debería cargar automáticamente

### Opción 2: Usar un servidor local

Si experimentas problemas con las imágenes o recursos, puedes usar un servidor local:

#### Con Python 3:
```bash
python -m http.server 8000
```

#### Con Python 2:
```bash
python -m SimpleHTTPServer 8000
```

#### Con Node.js (http-server):
```bash
npx http-server
```

Luego abre tu navegador en: `http://localhost:8000`

## 🎮 Uso de la Presentación

### Navegación Básica

- **Flecha Derecha/Abajo** o **Espacio**: Siguiente slide
- **Flecha Izquierda/Arriba**: Slide anterior
- **ESC** o **O**: Vista general (overview)
- **F**: Pantalla completa
- **S**: Modo presentador (speaker notes)
- **B** o **.**: Pausar presentación (blackout)
- **?**: Mostrar ayuda de teclado

### Navegación por Slides

La presentación está organizada en secciones principales:

1. **Portada**
2. **Introducción** (4 slides verticales)
3. **¿Para qué sirve?** (5 slides verticales)
4. **Conceptos básicos** (7 slides verticales)
5. **¿Cómo funciona paso a paso?** (6 slides verticales)
6. **Ventajas y Desventajas** (3 slides verticales)
7. **Herramientas** (1 slide)
8. **Ejemplo Práctico** (6 slides verticales)
9. **Bibliografía** (2 slides verticales)
10. **Slide Final**

### Navegación Vertical

Algunas secciones tienen slides verticales (sub-slides). Para navegar:
- **Flecha Abajo**: Ir a la siguiente sub-slide
- **Flecha Arriba**: Volver a la sub-slide anterior

## 🎨 Personalización

### Cambiar Colores

Los colores se pueden modificar en el archivo `styles.css`:

```css
/* Color principal (rojo) */
color: #ff0000;

/* Color secundario (rojo claro) */
color: #ff6666;

/* Fondo */
background: #000000;
```

### Modificar Contenido

Edita el archivo `index.html` para modificar el contenido de las slides. La estructura es:

```html
<section>
    <h2>Título</h2>
    <p>Contenido...</p>
</section>
```

### Agregar Slides

Para agregar nuevas slides, simplemente añade una nueva sección:

```html
<section data-transition="slide">
    <h2>Nueva Slide</h2>
    <p>Contenido de la nueva slide</p>
</section>
```

## 📚 Contenido de la Presentación

### 1. Introducción
- ¿Qué es la Simulación de Montecarlo?
- Origen del nombre
- Concepto básico

### 2. Aplicaciones
- Finanzas
- Gestión de proyectos
- Ingeniería y producción
- Negocios y marketing

### 3. Conceptos Básicos
- Evento incierto
- Resultado aleatorio
- Comportamiento probable
- Números generados al azar
- Repeticiones o simulaciones
- Sacar conclusiones

### 4. Proceso Paso a Paso
1. Definir el problema
2. Elegir las variables inciertas
3. Generar datos al azar
4. Correr muchas simulaciones
5. Analizar los resultados

### 5. Ventajas y Desventajas
- Ventajas del método
- Limitaciones y desventajas

### 6. Herramientas
- Excel o Google Sheets
- Python o R
- Programas especializados

### 7. Ejemplo Práctico
- Código Python completo
- Simulación de tiempo de entrega de pedidos
- Explicación paso a paso

### 8. Bibliografía
- Referencias y fuentes utilizadas

## 🔧 Configuración de Reveal.js

La configuración se encuentra al final del archivo `index.html`:

```javascript
Reveal.initialize({
    hash: true,
    controls: true,
    progress: true,
    center: true,
    transition: 'slide',
    plugins: [ RevealMarkdown, RevealHighlight, RevealNotes ]
});
```

### Opciones Disponibles

- `hash: true` - Permite navegación por URL con hash
- `controls: true` - Muestra controles de navegación
- `progress: true` - Muestra barra de progreso
- `center: true` - Centra el contenido verticalmente
- `transition: 'slide'` - Tipo de transición por defecto

## 🖼️ Imágenes

Todas las imágenes se encuentran en la carpeta `Imagenes/`. Las imágenes incluyen:
- Casino de Monte Carlo
- Diagramas explicativos de conceptos
- Ilustraciones de aplicaciones
- Gráficos del proceso

## 📝 Notas para Presentadores

Para usar las notas del presentador:
1. Presiona `S` durante la presentación
2. Se abrirá una ventana separada con las notas
3. La audiencia verá la presentación normal
4. Tú verás las notas y la siguiente slide

## 🌐 Compatibilidad de Navegadores

La presentación es compatible con:
- ✅ Chrome (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

## 📄 Licencia

Este proyecto es educativo y fue desarrollado para el curso de Investigación Operativa.

## 📧 Contacto

Para preguntas o sugerencias sobre esta presentación:
- **Grupo 5**
- San Román Matías
- Vivas Franco

## 🙏 Agradecimientos

- **Reveal.js** - Framework de presentaciones
- **Highlight.js** - Resaltado de sintaxis
- Todas las fuentes bibliográficas mencionadas en la presentación

## 📖 Recursos Adicionales

- [Documentación de Reveal.js](https://revealjs.com/)
- [Guía de Markdown](https://www.markdownguide.org/)
- [Documentación de Highlight.js](https://highlightjs.org/)

## 📊 Estadísticas del Proyecto

- **Total de slides:** ~40 slides
- **Secciones principales:** 10
- **Imágenes utilizadas:** 13
- **Ejemplos de código:** 1 completo
- **Referencias bibliográficas:** 7

## 🎯 Objetivos de la Presentación

1. Explicar qué es la Simulación de Montecarlo
2. Mostrar aplicaciones prácticas
3. Enseñar conceptos básicos
4. Demostrar el proceso paso a paso
5. Proporcionar un ejemplo práctico en Python
6. Presentar ventajas y desventajas
7. Mostrar herramientas disponibles

## 📅 Versión

- **Versión:** 1.0
- **Fecha:** 2025
- **Última actualización:** Noviembre 2025

---

**¡Gracias por usar esta presentación!**

Para más información sobre Simulaciones de Montecarlo, consulta la sección de Bibliografía en la presentación.

