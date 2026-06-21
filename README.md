# Laboratorio de Agentes IA - PFO2

## 👤 Datos del Estudiante

* Nombre y Apellido: Facundo David Bascur
* Institución: Instituto de Formación Técnica Superior (IFTS) N.° 29
* Asignatura: Desarrollo de Sistemas Web (Front End)

---

## 🚀 Deploy Unificado
Puedes ver el proyecto en vivo y navegar por las distintas versiones generadas por IA a través del siguiente enlace oficial en Vercel:

🔗 https://pfo2-front-bascur-facundo-xaglpf2g9.vercel.app/



## 🤖 Prompt Exacto Utilizado
Para la generación de las landing pages que se encuentran dentro de las carpetas correspondientes, se estructuró y ejecutó el siguiente prompt de ingeniería:

# ARQUETIPO
Actúa como un Diseñador UI/UX Principal y Desarrollador Frontend Senior especializado en la estética visual de plataformas SaaS de élite (como Linear, Stripe y Supabase). Eres un experto creativo que domina el diseño responsivo, las micro-interacciones, y la creación de interfaces oscuras altamente tecnológicas. Tu objetivo es generar una landing page ultracontemporánea para la empresa de servicios informáticos "SurDev", utilizando frameworks modernos como Tailwind CSS para lograr un acabado visual impecable y dinámico.

# INSTRUCCIONES TÉCNICAS
<pensamiento_cadena>
1. **Análisis del Sistema de Diseño (UI):** Adopta una paleta de colores para "SurDev" basada en un modo oscuro profundo (`bg-slate-950`), textos en alto contraste (`text-slate-100`) y acentos de color vibrantes (como cian eléctrico `text-cyan-400` y azul neón).
2. **Revolución Visual del Hero (Eliminación de la Imagen Cuadrada):** En lugar de una imagen rectangular o cuadrada rígida tradicional, diseña un contenedor visual tecnológico abstracto en la columna derecha. Este debe consistir en un entramado de tarjetas flotantes tipo panel de control (Dashboard/Terminal Mockup) con bordes ultra-redondeados, sombras difusas dinámicas, efectos de desenfoque de fondo (*glassmorphic blur*) y gradientes de color que simulen flujos de datos o servidores en red.
3. **Optimización Tecnológica:** Incorpora Tailwind CSS vía CDN, fuentes premium de Google Fonts (ej. 'Plus Jakarta Sans') y un set de iconos moderno (como Lucide Icons o FontAwesome) para garantizar un acabado profesional, escalable y limpio sin necesidad de imágenes pesadas.
4. **Construcción Modular:** Desarrolla de manera secuencial y sin interrupciones las 7 secciones obligatorias requeridas, manteniendo una estructura de código perfectamente comentada en español.
</pensamiento_cadena>

## DATOS DE REFERENCIA
<contexto>
- **Nombre comercial:** SurDev
- **Nicho:** Soporte IT premium, infraestructura de redes, desarrollo y optimización de hardware/software corporativo.
- **Enfoque Estético:** Interfaz SaaS moderna de última generación, modo oscuro texturizado, elementos flotantes con profundidad y efectos de brillo (*glow*).
</contexto>

<requisitos_estructurales_y_visuales>
La landing page debe incluir las siguientes 7 secciones maquetadas con Tailwind CSS:

1. **Cabecera (Header):** Menú de navegación flotante o `sticky top-0` con un fondo translúcido (`backdrop-blur-md bg-slate-950/70`) y borde inferior milimétrico. Incluye el logo de "SurDev" con tipografía seminegrita y un botón CTA destacado ("Soporte Urgente") a la derecha con transiciones suaves en hover.
2. **Hero Section (Diseño de Impacto):** Layout asimétrico de 2 columnas en desktop.
   - *Columna Izquierda:* Título (`<h1>`) con tipografía fluida y masiva donde la propuesta de valor use un degradado de texto brillante (`bg-clip-text text-transparent bg-gradient-to-r`). Botón CTA magnético con un sutil resplandor de fondo (`shadow-cyan-500/20 shadow-lg`).
   - *Columna Derecha (Arte IT Abstracto):* Queda **estrictamente prohibido** el uso de imágenes cuadradas planas. Debes maquetar un contenedor interactivo visual que simule una consola de comandos o un rack modular mediante código HTML/CSS limpio. Usa capas superpuestas (`relative/absolute`), bordes redondeados complejos (`rounded-2xl`), gradientes radiales oscuros y líneas de código simuladas con luces intermitentes tipo LED (`animate-pulse`).
3. **Descripción / Sobre Nosotros:** Bloque tipográfico espaciado con elegancia. Centrado, con textos limpios que expliquen cómo SurDev maximiza el tiempo de actividad (uptime) corporativo.
4. **Sección de Servicios:** Grid modular responsivo (1 col en móvil, 4 cols en desktop). Cada tarjeta debe ser un contenedor oscuro con hover dinámico (que se eleve levemente y aumente el brillo de su borde) que represente: Soporte IT, Redes de Datos, Ingeniería de Software y Soluciones de Hardware.
5. **Testimonios / Reseñas:** Layout tipo "Bento Box" o tarjetas minimalistas pulidas con variaciones sutiles de color de fondo (`bg-slate-900`). Incluye avatares circulares limpios, nombres de clientes, cargos y un sistema visual de 5 estrellas de calificación con colores nítidos.
6. **Formulario de Contacto:** Tarjeta centralizada con sombreado difuso. Inputs integrados en el modo oscuro (`bg-slate-900 border-slate-800 focus:border-cyan-500 focus:ring-1 focus:ring-cyan-500`) con validación HTML5 nativa y un botón de envío masivo de alta conversión.
7. **Pie de Página (Footer):** Enlaces rápidos de navegación organizados por columnas, derechos de autor de SurDev y una fila con iconos perfectamente alineados para redes sociales profesionales.
</requisitos_estructurales_y_visuales>

<restricciones_criticas>
- **Tecnologías Autorizadas:** Utiliza Tailwind CSS (clases utilitarias directas en el HTML), fuentes modernas de Google Fonts cargadas en el `<head>`, e iconos vectoriales SVG limpios o fuentes de iconos reconocidas.
- **Separación de Entregables:** Entrega obligatoriamente el código estructurado en dos bloques independientes de Markdown bien identificados: uno para el archivo `index.html` y otro para el archivo `styles.css` (destinado a configuraciones personalizadas, animaciones de pulsación de luces LED o variables del tema si se requieren fuera de Tailwind).
- **Prohibición de Código Incompleto:** Escribe el 100% de la estructura. No uses comentarios perezosos que omitan elementos o fuercen al usuario a rellenar el código por su cuenta.
</restricciones_criticas>

## FORMATO DE SALIDA
Genera el resultado estructurado estrictamente en los dos bloques de código independientes:

### 1. INTERFAZ Y MAQUETADO (`index.html`)
```html
<!-- Código HTML5 Completo con Tailwind CSS y componentes visuales detallados -->
