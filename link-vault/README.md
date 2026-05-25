# LinkVault

Gestor personal de enlaces en un solo archivo HTML. Sin dependencias, sin servidor, sin instalación.

## ¿Qué es?

LinkVault es una aplicación web autónoma (single-file `.html`) para guardar, organizar y buscar enlaces de manera persistente. Funciona completamente en el navegador, sin necesidad de backend, registro ni conexión a internet.

Ideal para guardar videos, artículos, recursos o cualquier link que quieras conservar sin saturar los marcadores del navegador.

## Características

- **Categorías** — organizá tus links en grupos temáticos. Creá, renombrá, mové o eliminá categorías.
- **Búsqueda en vivo** — filtrá por texto del link, título de categoría o anotación.
- **Orden alfabético** — A-Z ascendente, descendente o sin orden.
- **Anotaciones** — cada link puede llevar un comentario o descripción al lado.
- **Detección de duplicados** — al procesar, avisa si un link ya existe y permite reemplazarlo o saltarlo.
- **Colapsable** — las categorías se pliegan para no scrollear de más.
- **Edición inline** — editá o eliminá links individuales desde el listado.
- **Mover links** — pasá todos los links de una categoría a otra existente.
- **Exportar / Importar** — respaldá todo como JSON con el nombre personalizado.
- **Tres temas** — Claro, Oscuro y OLED (negro puro).
- **Título editable** — personalizá el encabezado según el contenido.
- **Persistencia local** — todo se guarda automáticamente en el navegador.

## Cómo se usa

1. Abrí `LinkVault.html` en cualquier navegador moderno.
2. Escribí un nombre de categoría y debajo sus links (uno por línea).
3. Agregá anotaciones opcionales después del link, con o sin paréntesis.
4. Apretá **Procesar** para guardarlos.
5. Repetí con más categorías en el mismo bloque de texto.

```
Nombre de la categoría
https://ejemplo.com/link (anotación opcional)
https://otro-link.com
```

## Exportar datos

Los datos se guardan en el navegador (localStorage). Para respaldarlos o transferirlos:

1. Apretá **Exportar JSON** — se descarga un archivo con el nombre `LinkVault - [título].json`
2. Para restaurar, apretá **Importar JSON** y seleccioná el archivo.

## Atajos

- **Clic en título** — editá el nombre de la biblioteca.
- **Clic en categoría** — expandí / colapsá sus links.
- **✎** — editá un link individual (URL y anotación).
- **✕** — eliminá un link individual.
- **Tema** — alterna entre OLED → Claro → Oscuro.

## Requisitos

Navegador moderno con soporte para:
- localStorage
- CSS `backdrop-filter`
- ES6+

Probado en Chrome, Firefox, Edge y Brave.
