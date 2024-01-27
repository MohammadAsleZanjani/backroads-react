# Backroads App

[Working Application - Deployed](https://zanjani-first-reactapp.netlify.app/)

- remove in src

  - setupTests.js
  - reportWebVitals.js
  - App.test.js

- be careful with multiple css files

App.js


- remove
  - remove logo.svg
  - App.css

#### Setup Structure

- public/index.html

  - change title
  - copy/paste font-awesome link (from html project)

- index.css

  - copy/paste css (from html project - css/styles.css)
  - error in line 209, just comment out for now

#### Setup Components

- in src create components folder
- in the components create following files
  - Navbar.js
  - Hero.js
  - About.js
  - Services.js
  - Tours.j
  - Footer.js
- setup components with default export (snippet - rafce)
- carefully move the code from App.js into components (files)
  - hint - look for navbar, footer and section tags
- App.js should be empty
- import and render all components in App.js (try auto imports)
- result is going to be the same, it's just easier to manage the code
- again, it's just my preference to split up code in such way.
  You can split it up in any way that makes the most sense to you.

