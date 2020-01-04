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

---
