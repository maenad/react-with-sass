# How to quickly add SASS to your React project

When I first started experimenting with SASS, the first thing I did was look for a VS Code plug-in to add SASS automatically to my project; nevertheless, when I started working with other people that had different code editors, this became an issue.
I took the time to check some YouTube videos and found a quick way to add SASS to your React project, no matter in which state the project is.

I'm not going to make this as those people who create food recipes that tell their life story before posting the actual information, so...

## Here we go:

* Create your React project

* Open your terminal of choice and input:

   `npm install --save-dev node-sass`

* Create a folder called *Styles* inside your `src` folder.

* Inside the *Styles* folder create a *variables.scss* sheet.

* Convert *App.css* to *App.scss* and move it inside *Styles*

* Go to *App.js* and change *App.css* to *App.scss*. It should be at the top, on your imports.

* Go to *App.scss* and import your variables sheet (*variables.scss*)

* THAT'S IT!

Something broke? Let me know and we can fix it together!

---
Cuando empecé a experimentar con SASS, lo primero que hice fue buscarme un plugin de VSCode para que agregase la herramienta automáticamente a mi sistema; sin embargo, cuando comencé a trabajar en proyectos conjuntos con personas que utilizaban otros editores de código, la utilización del plugin se convirtió en un problema.

A principios de año me tomé el tiempo de revisar varios videos de YouTube y encontré una manera bastante rápida y fácil de agregar SASS a un proyecto de React que recién comienza (¡para los que van avanzados también se puede adaptar!)

Seguro hay mil maneras más de hacerlo, pero esta es la que yo encontré y me ha funcionado muy bien.

## AQUÍ VAMOS:

* Crea tu proyecto de React en el editor de código que quieras.

* Abre la terminal que usas siempre y escribe

   `npm install --save-dev node-sass`

* Crea una carpeta llamada *Styles* dentro de tu carpeta `src`.

* Dentro de la carpeta *Styles* crea un archivo *variables.scss*.

* Cambia *App.css* a *App.scss* sobre-escribiéndolo y mueve el archivo dentro de la carpeta *Styles*

* Ve a *App.js* y cambia *App.css* a *App.scss*. Esto debería aparecerte en la parte superior, donde están los archivos importados (imports).

* Dentro de *App.scss* importa tu archivo de variables (*variables.scss*)

* ¡LISTO!

---

¿Se rompió todo? ¿Le ves algo raro? Avísame y lo arreglamos 😉
