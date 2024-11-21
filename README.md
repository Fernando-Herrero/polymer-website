# Proyecto: Polymer website

## **Descripción del Proyecto**  
Este proyecto es un sitio web modular desarrollado como práctica de diseño y maquetación. Está basado en un diseño previamente creado en **Figma**, lo que permitió trabajar sobre una guía visual clara y profesional. El objetivo principal fue replicar fielmente el diseño.

## **Live Preview**  
Accede al sitio web funcionando aquí: [Live Preview](https://polymer-website.netlify.app)
---

## **Tecnologías Usadas**  
- **HTML5**: Para la estructura y el contenido de las páginas.  
- **CSS3**: Para los estilos y diseño visual.  
- **Flexbox**: Para el diseño y la distribución del contenido.  
- **Linear Gradients**: Utilizados para fondos atractivos.  

---

## **Estructura del Proyecto**  

El proyecto está dividido en una página principal y múltiples subpáginas tanto en HTML como CSS, diseñadas para modularidad y escalabilidad.  

### **HTML**:  
- `index.html`: Página principal que actúa como punto de entrada.  
- Otras 4 páginas:  
  - `blog.html`.  
  - `changelog.html`.  
  - `features.html`.
  - `pricing.html`.  

### **CSS**:  
- `styles.css`: Archivo global con estilos base.  
- Otras 3 hojas de estilo específicas:  
  - `styles-b.css`.  
  - `styles-c.css`.  
  - `styles-f.css`.

---

## **Buenas Prácticas Aplicadas**  

1. **Separación de Concerns (SoC)**:  
   - Se dividió el contenido en HTML y los estilos en CSS para garantizar claridad y mantenimiento.  
2. **Uso de Selectores Globales**:  
   - Implementación de `*::before`, `*::after` y `*` para unificar el box-sizing.  
3. **Tipografía Responsiva**:  
   - Uso de fuentes estándar del sistema como `-apple-system` y `Segoe UI`.  
4. **Uso Eficiente de Flexbox**:  
   - Clases como `.flex-1`, `.flex-2`, `.flex-3` para distribuciones versátiles.  
5. **Diseño Consistente**:  
   - Aplicación de bordes redondeados (`border-radius`) y sombras (`box-shadow`).  
6. **Mantenimiento Semántico**:  
   - Uso de etiquetas como `<header>`, `<main>`, `<section>` y `<footer>` para mejorar la semántica del sitio.  

---

## **Detalles de Cada Sección**  

### **Página Principal (`index.html` y `styles.css`)**  
- **Descripción**: Página que introduce al usuario al sitio web. Contiene un encabezado, sección principal con texto alineado al centro y un pie de página estilizado.  
- **Reto**: Crear un diseño adaptable que sea visualmente atractivo utilizando un gradiente en el fondo y sombras para elementos destacados.  

### **Subpáginas**  
- **Descripción**: Páginas individuales dedicadas a cada sección del sitio.  
- **Reto**: Mantener consistencia con la página principal mientras se añade un diseño único en cada una.  

### **Estilos Específicos**  
- **Descripción**: Archivos CSS para personalizar cada subpágina con colores, alineaciones y distribuciones específicos.  
- **Reto**: Modularizar el CSS para evitar redundancias y mantener un código limpio.  