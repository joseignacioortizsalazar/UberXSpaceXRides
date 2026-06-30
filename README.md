# UberX SpaceX Space Rides

Proyecto web estático inspirado en una aplicación de viajes espaciales tipo Uber, donde el usuario puede iniciar sesión, explorar destinos del sistema solar, seleccionar una nave, elegir un método de pago y consultar un recibo del viaje.

-integrantes del proyecto : Johan Rueda, Jose Ignacio, Sara Ardila.

## Descripción

UberX SpaceX Space Rides simula una experiencia de reserva de transporte espacial. La interfaz está construida con HTML y CSS, usando fondos, animaciones, tarjetas, menús desplegables e imágenes relacionadas con planetas, naves y viajes espaciales.

El flujo principal del sitio es:

1. Login del usuario.
2. Pantalla de inicio con destinos espaciales.
3. Selección de ruta entre la Tierra y Marte.
4. Selección de nave y acceso al pago.
5. Selección de método de pago.
6. Visualización del recibo del viaje.

## Tecnologías utilizadas

- HTML5
- CSS3
- Animaciones con `@keyframes`
- Diseño responsive con media queries
- Recursos visuales locales en la carpeta `img`

## Estructura del proyecto

```text
.
├── csss/
│   ├── app.css
│   └── others.css
├── htmls/
│   ├── home.html
│   ├── index.html
│   ├── payment-methods.html
│   ├── receipt.html
│   ├── splash.html
│   └── travel.html
├── img/
│   ├── astronauta.png
│   ├── astronautaa.png
│   ├── cohete.png
│   ├── CrewDragon.png
│   ├── factura.pdf
│   ├── fondoestrellas.jpeg
│   ├── fondops2.png
│   ├── instrucciones.pdf
│   ├── loading.jpeg
│   └── ...
└── README.md
```

## Páginas principales

### `htmls/index.html`

Pantalla inicial con formulario de login. Incluye campos para nombre, correo y contraseña. El botón de registro lleva al usuario a la página principal.

### `htmls/home.html`

Página de inicio del usuario. Muestra:

- Perfil del usuario.
- Tarjeta informativa sobre seguridad espacial.
- Acceso a instrucciones en PDF.
- Accesos visuales al viaje.
- Lista de destinos: Tierra, Marte, Luna y Estación Espacial Internacional.
- Barra flotante de navegación.

### `htmls/travel.html`

Pantalla de selección de viaje. Contiene:

- Mapa visual de ruta entre Earth y Mars.
- Línea orbital animada.
- Menú inferior desplegable.
- Opciones de nave: Crew Dragon, Starliner y Dream Chaser.
- Botón para continuar al pago.

### `htmls/payment-methods.html`

Pantalla de métodos de pago. Incluye:

- Buscador visual de métodos de pago.
- Tarjetas guardadas.
- Opciones como Mastercard, Nequi y PayPal.
- Enlace hacia el recibo del viaje.

### `htmls/receipt.html`

Pantalla de recibo. Presenta:

- Total del viaje.
- Fecha del viaje.
- Detalles de salida y llegada.
- Número de vuelo.
- Asiento.
- Tarifa, impuestos y total.
- Método de pago.
- Acceso al PDF de la factura.

## Cómo ejecutar el proyecto

Este proyecto no necesita instalación de dependencias ni servidor backend. Solo requiere un navegador web.

Opción recomendada:

1. Abre la carpeta del proyecto.
2. Entra a la carpeta `htmls`.
3. Abre el archivo `index.html` en tu navegador.

También puedes iniciar directamente desde:

```text
htmls/index.html
```

## Navegación del sitio

```text
index.html
   ↓
home.html
   ↓
travel.html
   ↓
payment-methods.html
   ↓
receipt.html
```

## Características destacadas

- Interfaz visual con temática espacial.
- Pantalla de carga animada.
- Fondos personalizados.
- Planetas e imágenes interactivas.
- Menú desplegable hecho solo con HTML y CSS.
- Diseño adaptable para escritorio y pantallas pequeñas.
- Recibo final con datos del viaje.

## Recursos incluidos

El proyecto incluye imágenes de planetas, cohetes, astronautas, fondos, logos de medios de pago y documentos PDF como:

- `img/instrucciones.pdf`: información de seguridad del viaje espacial.
- `img/factura.pdf`: factura o recibo descargable.

## Autores

Proyecto académico desarrollado como una simulación de aplicación web para viajes espaciales.
