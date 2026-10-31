# Cobalion Web

Landing page de Cobalion, estudio digital en Los Mochis, Sinaloa. Presenta sus servicios de desarrollo de software y ciberseguridad, el proceso de trabajo y las opciones de contacto.

## Desarrollo local

El sitio es estático y no requiere un paso de compilación. Para verlo localmente con el entorno de Cloudflare Workers Assets, ejecuta:

```bash
npx wrangler dev
```

Abre la dirección local que Wrangler muestra en la terminal.

## Despliegue

El proyecto usa [Wrangler](https://developers.cloudflare.com/workers/wrangler/) y la configuración de [`wrangler.jsonc`](./wrangler.jsonc). Después de iniciar sesión en Cloudflare con Wrangler, despliega con:

```bash
npx wrangler deploy
```

Los archivos publicados se sirven desde `public/`, según la configuración `assets.directory`.

## Estructura

```text
public/
  index.html              Contenido y estructura de la página
  styles.css              Diseño adaptable y estilos
  script.js               Menú móvil
  media/
    brand/                Logotipo
    fonts/                Tipografías Dosis y Chakra Petch
assets/
  images/business_identity/  Archivos originales de identidad visual
wrangler.jsonc             Configuración de Cloudflare
```

## Contenido

- Desarrollo web, sistemas a medida e integraciones.
- Pruebas de seguridad, consultoría y evaluación de riesgos.
- Contacto telefónico y conversación por WhatsApp.

La foto del equipo se carga desde Unsplash; requiere conexión a internet para mostrarse.
