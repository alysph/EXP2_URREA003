# Pelushop

Sitio web de una tienda de ropa y accesorios para mascotas, desarrollado como proyecto universitario. Incluye múltiples secciones informativas, formularios y consumo de una API pública de indicadores económicos chilenos en tiempo real.

## Demo en vivo

> _Agrega aquí el link de GitHub Pages una vez que lo actives_

---

## Capturas

> _Agrega aquí capturas de pantalla del sitio_

---

## Funcionalidades

- **Inicio** — Carrusel de imágenes con descripción de productos y reloj en tiempo real
- **¿Quiénes somos?** — Historia, misión y visión de la tienda, con video integrado
- **Galería** — Muestra de productos disponibles (ropa y accesorios para perros y gatos)
- **Contacto** — Formulario de contacto con validación mediante jQuery Validate
- **Registro** — Formulario de registro de usuarios con efectos de focus animados
- **API de Indicadores** — Consulta en tiempo real a la API pública [mindicador.cl](https://mindicador.cl), mostrando el valor actualizado de divisas e indicadores económicos chilenos (UF, UTM, dólar, euro, etc.)

---

## Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de páginas |
| CSS3 | Estilos personalizados |
| JavaScript (Vanilla) | Reloj en tiempo real, efectos de UI |
| Bootstrap 5 | Layout responsivo, navbar, carrusel, tablas |
| jQuery | Manipulación del DOM, peticiones AJAX |
| jQuery Validate | Validación de formularios |
| Font Awesome | Iconografía |
| API REST (mindicador.cl) | Indicadores económicos en tiempo real |

---

## Estructura del proyecto

```
Pelushop/
├── index.html          # Página de inicio
├── quienessomos.html   # Quiénes somos
├── galeria.html        # Galería de productos
├── contacto.html       # Formulario de contacto
├── registro.html       # Formulario de registro
├── api.html            # Indicadores económicos en tiempo real
├── css/
│   ├── estilo.css      # Estilos principales
│   └── style.css       # Estilos complementarios
├── js/
│   └── java.js         # Reloj en tiempo real y efectos de formularios
└── img/                # Imágenes del sitio
```

---

## Cómo ejecutar el proyecto

El proyecto es 100% frontend estático, no requiere instalación de dependencias ni servidor.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/alysph/pelushop.git
   ```
2. Abre el archivo `Pelushop/index.html` en tu navegador.

¡Listo! El sitio corre de forma local sin configuración adicional.

---

## Autora

**Alison Urrea** — [GitHub](https://github.com/alysph)

---

## Licencia

Proyecto académico — Duoc UC, 2022.
