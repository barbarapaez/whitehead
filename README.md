# Proyecto Whitehead — PICIFFYH

Sitio web del proyecto de investigación **PICIFFYH**, radicado en el Centro de Investigaciones "María Saleme de Burnichon" de la Facultad de Filosofía y Humanidades (FFyH), Universidad Nacional de Córdoba. El proyecto indaga el surgimiento de la metafísica procesual en la filosofía de la ciencia temprana de Alfred North Whitehead.

Este sitio también es el trabajo final de la materia de desarrollo web.

## Estructura del sitio

- `index.html` — inicio
- `pages/proyecto.html` — fundamentación del proyecto
- `pages/equipo.html` — integrantes
- `pages/nuestro-trabajo.html` — actividades realizadas y galería de las Jornadas Whitehead y la Filosofía de la Ciencia 2024
- `pages/publicaciones.html` — publicaciones y repositorios
- `pages/glosario.html` — glosario de términos
- `pages/contacto.html` — cómo encontrarnos

## Tecnologías

- HTML5 semántico
- SCSS, organizado en `utilities/`, `base/`, `layout/` y `components/`, con un único punto de entrada en `scss/main.scss`
- [Bootstrap 5](https://getbootstrap.com/) (navbar y carrusel de fotos), revestido con nuestra propia paleta de colores
- [AOS](https://michalsnik.github.io/aos/) para animaciones al hacer scroll

## Compilar el SCSS

```bash
npm install
npx sass scss/main.scss styles/styles.css
```

## Estado

- [ ] Publicar un email de contacto propio del proyecto (por ahora, `contacto.html` deriva a la FFyH)

## Créditos

Retrato de Alfred North Whitehead: fotografía de archivo, [Wellcome Collection](https://wellcomecollection.org/) (dominio público).
