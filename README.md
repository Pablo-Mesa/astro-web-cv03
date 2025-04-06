# Astro Web CV

Este proyecto es un portafolio personal desarrollado con el framework [Astro](https://astro.build/). Incluye componentes como `Education`, `Skills` y un diseño responsivo para mostrar información personal y profesional.

## Características

- **Framework:** Astro
- **Estilos:** CSS modular
- **Diseño:** Responsivo y minimalista
- **Componentes:** 
  - `CardLeftTopSide.astro`: Muestra información personal.
  - `RS_header.astro`: Menú de navegación tipo acordeón.
  - `CRTS_body.css`: Contenedor principal para componentes como `Education` y `Skills`.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/Pablo-Mesa/astro-web-cv03.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd astro-web-cv03
   ```
3. Instala las dependencias:
   ```bash
   npm install
   ```

## Uso

1. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```
2. Abre tu navegador en `http://localhost:3000`.

## Estructura del Proyecto

```
astro-web-cv03/
├── src/
│   ├── components/
│   │   ├── CardLeftTopSide.astro
│   │   ├── RS_header.astro
│   ├── styles/
│   │   ├── cardLeftTopSide.css
│   │   ├── rsHeader.css
│   │   ├── CRTS_body.css
├── public/
│   ├── assets/
│   │   ├── imagenes/
├── package.json
├── README.md
```

## Contribución

Si deseas contribuir, por favor abre un issue o envía un pull request.

## DEV

Este archivo readme fue generado directamente con copilot