# Boda Cisneros Perez – Planificador

Plataforma web para organizar la boda: presupuesto, checklist, plan de pagos, calendario, proveedores y branding.
Boda: 17 de julio de 2027.

## Contenido del proyecto

```
boda-github/
├── index.html          ← toda la aplicación
├── assets/
│   └── favicon.svg     ← icono de la pestaña
├── .nojekyll           ← evita procesamiento extra de GitHub Pages
└── README.md           ← este archivo
```

## Cómo publicarla en GitHub Pages (gratis)

1. Entra a https://github.com y crea una cuenta (o inicia sesión).
2. Toca **New repository**. Nombre sugerido: `boda`. Déjalo en **Public** y toca **Create repository**.
3. En el repositorio nuevo toca **uploading an existing file**.
4. Descomprime el zip y arrastra **todo el contenido** (index.html, la carpeta assets, .nojekyll y README.md) a la ventana. Si tu navegador no deja subir `.nojekyll`, no pasa nada: la página funciona igual.
5. Toca **Commit changes**.
6. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y guarda.
7. Espera 1–2 minutos. Tu página quedará en: `https://TU-USUARIO.github.io/boda/`

## Dónde se guardan los datos

- Los datos se guardan **solo en el navegador** de cada dispositivo (no se suben a GitHub). Por eso es seguro que el repositorio sea público: ahí solo está el código.
- Si borras los datos del navegador, se pierden. **Respalda seguido** con el botón **Respaldar datos**.

## Cómo compartir datos entre dos personas

1. Quien capturó toca **Respaldar datos**. Se descarga un archivo `.json`.
2. Se lo manda a la otra persona (WhatsApp, correo, etc.).
3. La otra persona toca **Importar** y elige el archivo. Esto reemplaza los datos de ese navegador.

Conviene turnarse: no editar al mismo tiempo, porque al importar se reemplaza todo.

## Notas

- Los montos están en USD. El plan de pagos usa apartado del 20 % y mensualidades iguales hasta el 1 de julio de 2027.
- El botón **PDF** abre la impresión del navegador; elige "Guardar como PDF".
- Para cambiar la fecha, el presupuesto o los nombres, edítalos dentro de la propia página.
