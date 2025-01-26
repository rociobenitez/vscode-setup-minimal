# Editando archivos en VSCode

1. [Ordenar código](#ordenar-código)
2. [Comentar código](#comentar-código)
3. [Crear nuevo archivo](#crear-nuevo-archivo)
4. [Ir a la definición](#ir-a-la-definición)
5. [Borrar varias líneas a la vez](#borrar-varias-líneas-a-la-vez)
6. [Deshacer y rehacer](#deshacer-y-rehacer)
7. [Ocultar y mostrar](#ocultar-y-mostrar)
   - [Sidebar](#sidebar)
   - [Terminal](#terminal)
8. [Manejo de tabs](#manejo-de-tabs)
   - [Buscar un archivo](#buscar-un-archivo)
   - [Abrir, cerrar, reabrir pestañas](#abrir-cerrar-reabrir-pestañas)
   - [Tabulaciones](#tabulaciones)

## Ordenar código

**Tips:**

```
⌥ ↓
⌥ ↑
```

Si queremos ordenar por ejemplo este fragmento de código:

```
<ul>
    <li>Descripción 7</li>
    <li>Descripción 6</li>
    <li>Descripción 2</li>
    <li>Descripción 3</li>
    <li>Descripción 5</li>
    <li>Descripción 4</li>
    <li>Descripción 1</li>
</ul>
```

### Opción 1: Si el código se puede ordenar alfabéticamente

Podemos:

1. Seleccionar todos los `<li>`
2. Abrir la paleta de commandos con `Cmd + Shift + P`
3. Escribir **Sort Lines Ascending**

### Opción 2: Mover u ordenar líneas independientes

Podemos:

1. Colocarnos en la línea
2. Usar `⌥ ↓` o `⌥ ↑` para cambiarla de posición.

### Opción 3: Mover un bloque de codigo

Por ejemplo:

```
<ul>
    <li>
        <span>Superheroina 4</span>
        <span>Superpoder 4</span>
    </li>
    <li>
        <span>Superheroina 3</span>
        <span>Superpoder 3</span>
    </li>
    <li>
        <span>Superheroina 1</span>
        <span>Superpoder 1</span>
    </li>
    <li>
        <span>Superheroina 2</span>
        <span>Superpoder 2</span>
    </li>
</ul>
```

Podemos:

1. Seleccionar el bloque que queremos mover (por ejemplo todo el `<li></li>`).
2. Usar `⌥ ↓` o `⌥ ↑` para desplazarlo.

## Comentar código

**Tips:**

```
⌘ /
⇧ ⌥ A
```

Para ver o cambiar el shortcut que comenta el código:

1. Abrir la paleta de commandos con `Cmd + Shift + P`
2. **Toggle Line Comment** > _Configurar el enlace de teclado_ (icono de configuración)

Usamos `⌘ /` para comentar toda la línea y `⇧ ⌥ A` para comentar solo una parte.

## Crear nuevo archivo

**Tips:**

```
⌘ click
```

Si un archivo no existe por ejemplo este:
`   <script src="assets/js/app.js"></script>
  `

y hacemos `⌘ + click`, VSCode nos va a avisar de que el archivo no existe y no preguntará si queremos crearlo.

## Ir a la definición

**Tips:**

```
⌘ + click
```

Podemos hacer `⌘ + click` sobre una función, método o archivo importado y nos va a llevar al archivo donde se definió (como si fueran hipervínculos).

Por ejemplo en esta situación:

```
import { congratulate } from './extra/functions';

const congratulation = congratulate( 'Rocío' );

console.log(congratulation);
```

## Borrar varias líneas a la vez

**Tips:**

```
⇧ ⌘ L   # Seleccionar todas las ocurrencias de la selección
⇧ ⌘ K   # Borrar la selección
```

1. Nos posicionamos sobre la palabra común de varias líneas que deseamos borrar.
2. Usamos `⇧ ⌘ L` para seleccionarlas todas.
3. Presionamos `⇧ ⌘ K` para borrarlas.
4. Si queremos volver a un único cursor, pulsamos `Esc`.

## Deshacer y rehacer

**Tips:**

```
⌘ Z     # Deshacer
⌘ ⇧ Z   # Rehacer
```

## Ocultar y mostrar

### Sidebar

**Tips:**

```
⌘ B
```

### Terminal

**Tips:**

```
⌃ `
```

## Manejo de tabs

### Buscar un archivo

1. Abrir la paleta de commandos con `Cmd + Shift + P`
2. Escribir el nombre del archivo (o lo que recordemos de ese archivo)
3. Presionar `Enter`

### Abrir, cerrar, reabrir pestañas

**Tips:**

```
⌘ K ⌘ W  # Cerrar todas
⌘ W      # Cerrar tab  / Cerrar aplicación
⇧ ⌘ T    # Reabrir anterior
⌥ ⌘ ←    # Cambiar de tab
⌥ ⌘ →    # Cambiar de tab
```

### Tabulaciones

**Tips:**

```
Tab
⇧ Tab
```

Podemos jugar con la tabulación con estos dos comandos.
