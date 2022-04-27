# Getting Started with the barebones template

To use this template, clone this repo into whatever directory suits you (I recommend naming the directory `cra-template-barebones`). Do not run npm install, as there is no need!

Then you can simply execute  
 `npx create-react-app my-app --template file:../path/to/cra-template-barebones`

 That's it.
 
# Differences from default template
  - Does not install web-vitals and does not include reportWebVitals.js
  - Does not install the the React Testing Library packages
  - Public directory does not include robots.text or manifest.json
  - Home page simply displays raw text ('Hello world!')
  - The styling imported in index.js sets the margin and padding to 0 for the `html` and `body` tags. That's it.

# Project structure
Any app built with this template will have the following project structure:
```
/node_modules
/public
  favicon.ico
  index.html
/src
  App.jsx
  index.css
  index.js
.gitignore
package.json
package-lock.json
```
