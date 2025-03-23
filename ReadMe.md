# Currículum Interactivo en HTML

Este repositorio contiene un currículum interactivo creado en HTML. El objetivo de este proyecto fue explorar y aplicar nuevas etiquetas HTML que no eran conocidas previamente, con el fin de mejorar la interactividad y la presentación del currículum.

### 1. Etiqueta `<details>`

#### ¿Qué es?
La etiqueta `<details>` se utiliza para crear un widget de desplegable que el usuario puede abrir y cerrar. Dentro de esta etiqueta, se incluye un elemento `<summary>` que actúa como el título o la etiqueta que el usuario hace clic para expandir o colapsar el contenido.

#### ¿Cómo la apliqué?
En mi currículum, utilicé la etiqueta `<details>` para mostrar información detallada sobre mi experiencia laboral. Por ejemplo, al hacer clic en "Gestión de Redes Sociales" o "Gasfitería", se despliega una descripción más detallada de estas experiencias.

#### Ejemplo de código:
```
<details>
    <summary><b>Gestión de Redes Sociales</b></summary>
    <p>Gestiono las redes sociales del emprendimiento <a href="https://www.facebook.com/p/Caba%C3%B1as-Carelmapu-100063607269075/">Cabañas Carelmapu</a>.</p>
</details>
```

### 2. Etiqueta `<abbr>`

### ¿Qué es?

La etiqueta `<abbr>` se utiliza para definir una abreviatura o un acrónimo. Al pasar el cursor sobre el texto abreviado, se muestra el texto completo en un tooltip.

### ¿Cómo la apliqué?

En la sección de "Educación y Certificaciones", utilicé la etiqueta `<abbr>` para mostrar la vigencia de mi licencia de conducir. Al pasar el cursor sobre "Licencia de conducir Clase B", se muestra un tooltip con la información adicional.

### Ejemplo de código:

```
<abbr title="Vigente hasta el año 2027">Licencia de conducir Clase B.</abbr>
```

### 3. Etiqueta `<mark>`

### ¿Qué es?

La etiqueta `<mark>` se utiliza para resaltar texto que es relevante o que debe destacarse en un contexto particular. El texto dentro de esta etiqueta se muestra resaltado con un fondo amarillo por defecto.

### ¿Cómo la apliqué?

En la sección de "Habilidades", utilicé la etiqueta `<mark>` para resaltar mi experiencia en la creación y administración de servidores de Minecraft, lo que ayuda a que esta habilidad destaque visualmente.

### Ejemplo de código:

```
<li>Experiencia en creación y administración de <mark>servidores de Minecraft</mark>.</li>
```