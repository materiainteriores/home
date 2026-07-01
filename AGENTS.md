# Instrucciones para Agentes AI

## Proyecto

Landing page estática "Materia Interiores de Lujo" — compatible con GitHub Pages.

## Reglas

- **NO** usar bases de datos, frameworks (React, Vue, Angular, etc.) ni backend de ningún tipo
- Solo HTML5, CSS3, JavaScript vanilla (se permite Bootstrap/Materialize vía CDN si es estrictamente necesario)
- Todo debe funcionar 100% del lado del cliente y ser desplegable en GitHub Pages sin build step

## Documentación

Cada vez que se modifique el proyecto (HTML, CSS, JS, assets, estructura), se debe actualizar:

- `README.md` — mantener descripción, estructura del proyecto, instrucciones de uso y despliegue al día
- `AGENTS.md` — mantener reglas, convenciones y comandos actualizados

## Flujo obligatorio al hacer cambios

Cada vez que se modifique HTML, CSS, JS o assets, se debe seguir este orden:

1. Hacer los cambios solicitados (código)
2. **Actualizar `README.md`** si cambió la estructura, tecnologías o instrucciones
3. **Actualizar `AGENTS.md`** si cambian reglas, convenciones o comandos
4. Verificar que los docs reflejen el estado real del proyecto

## Convenciones y estilo de código

- **CSS:** usar variables en `:root`, clases semánticas en inglés con kebab-case, diseño responsivo mobile-first
- **HTML:** mantener etiquetas semánticas (`<header>`, `<section>`, `<nav>`, etc.), atributo `lang="es"`, meta tags de SEO
- **JS:** usar `'use strict'`, código limpio, sin dependencias externas, aprovechar APIs nativas (Intersection Observer, scroll-behavior, etc.)
- **Imágenes:** optimizar antes de agregar, usar `loading="lazy"`, mantener assets en `assets/img/`
- **Commits:** descriptivos en español o inglés, sin emojis

## Comandos

No hay build step. Para desarrollo local:

```bash
# Servir el proyecto localmente
npx serve .

# Alternativa con Python
python3 -m http.server
```
