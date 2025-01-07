## Hola Anna

Buen trabajo!, aunque estos módulos son la introducción a todo, has avanzado muy bien, ojalá que sigas así y no pierdas el entusiasmo :D Este proyecto lo podrías mejorar y trabajar en los módulos posteriores 

Puntos a destacar:

- Utilizaste un archivo CSS distinto para cada HTML. Eso está bien porque de esta manera el codigo es más reutilizable. Sin embargo, podrías tener un style.css general con todo el diseño que va a ser aplicado a lo largo de las páginas (como diagramación, colores, tipografías) que esté linkeado en todas las páginas, y aparte, linkear los archivos CSS que sean específicos a la página o sección que esté visitando el usuario. (Recuerda que puedes linkear más de un archivo CSS)

- Mantuviste el código legible y ordenado, así como la estrucutra de tus carpetas y archivos

- Usaste selectores CSS avanzados para la animación de los destinos y el formulario de login. Ya sea que hayas visto tutoriales o te hayas apoyado en la IA, está muy bien que trabajes con código de alguien más. No hay que reinventar la rueda si ya existe lo que necesitas. Lo importante es que ya lo entiendas, lo sepas implementar y que puedas hacer cambios si así lo requieres.

- Tomaste en cuenta la parte del diseño responsivo con media queries. Aquí aún tienes un margen de mejora pero es importante que siempre lo tengas a la vista.

- En general aplicaste todo lo que vimos en clase :D

Aquí tienes algunos puntos de mejora:

- Aún falla un poco el tema de las etiquetas semánticas, por ejemplo, en la sección de Ayuda: los párrafos no deberían contener a los títulos. Estos dos elementos deberían ser hermanos (Estar al mismo nivel).

- Utilizaste muchos <br> para poner espacio. Esto sería mejor controlarlo con CSS.

- Si vas a usar varios archivos CSS lo mejor sería que el nombre del archivo corresponda a su homólogo, es decir, si tu html se llama iniciar-sesion.html, podrías usar el mismo nombre para su CSS iniciar-sesion.css

- Esto no es en cuanto a la programación, sino en cuanto a la usabilidad. En la sección de Ayuda, desaparece el menú principal, lo que le dificulta la navegación al usuario (ya no tiene como volver a la página principal). Este menú principal debería aparecer en todas las páginas.

- En los archivos de tu repositorio viene un archivo oculto (.vscode) que trae la configuración de tu Visual Studio Code (En este caso veo que cambiaste el color de tu VSCode a azul). Para evitar que se suban este tipo de archivos puedes usar un archivo .gitignore:

El archivo .gitignore se usa para decirle a Git qué archivos o directorios no deben ser rastreados o versionados en tu repositorio. Esto es útil para evitar que archivos temporales, configuraciones locales o artefactos de compilación sean incluidos en el control de versiones.

Dentro de tu repositorio, puedes crear este archivo .gitignore y dentro puede contener algo como esto:

```
# Ignorar archivos temporales de IDE
.vscode/

```

En [este enlace](https://desarrolloweb.com/articulos/eliminar-archivos-git-gitignore.html) puedes revisar más a detalle como eliminar este archivo y quitarle el seguimiento que hace git

Gracias por el tiempo invertido Anna, espero que sigas creciendo y aprendiendo, aún queda mucho por delante y estoy seguro que vas por el camino correcto :)