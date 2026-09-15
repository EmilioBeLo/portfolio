# emiliobenitez.com

Portfolio personal de Emilio Benítez, desarrollador full stack.
Sitio estático de una sola página en HTML, CSS y JavaScript, sin
dependencias ni proceso de compilación.

**En producción:** https://emiliobenitez.com

## Qué es

Una sola página con tres vistas controladas por JavaScript (`#inicio`,
`#proyectos`, `#cv`), cada una con su propia dirección. Los proyectos se
cuentan con escenas dibujadas en `<canvas>` que avanzan con el scroll,
y la portada incluye una calculadora de coste de oportunidad.

- **Inicio** — propuesta de valor, para quién encaja, calculadora, resumen de casos
- **Proyectos** — los tres proyectos a fondo
- **CV** — currículum imprimible (botón de imprimir → PDF limpio)

## Stack

Ningún framework. Un archivo HTML con CSS y JavaScript inline.
Tipografías: Fraunces (titulares) y JetBrains Mono (cuerpo), servidas
desde Google Fonts.

## Desarrollo local

No requiere instalación. Basta con abrir `index.html` en el navegador,
o servirlo con cualquier servidor estático:

```bash
python3 -m http.server 8000
```

## Despliegue

Desplegado en Vercel, conectado a la rama `main` de este repositorio.
Cada push a `main` publica automáticamente.

## Estructura

```
index.html      página completa (HTML + CSS + JS)
og.png          imagen para vista previa al compartir el enlace
robots.txt      indexación para buscadores
sitemap.xml     mapa del sitio
```

## Pendiente

- [ ] Tres cicatrices (casos donde algo salió mal)
- [ ] Dos testimonios con nombre y cargo reales
- [ ] Foto personal en la sección "Quién hay detrás"

## Licencia

Contenido y diseño © Emilio Benítez. Código disponible como referencia;
no reutilizar el contenido escrito ni las escenas sin permiso.
