# The Best-Laid Plans

## Initial Structure Sketch

site/
|
|--- public/                            // Static files
|       |-- index.html
|       |-- favicon-32.png
|       |-- favicon-48.png
|       |-- favicon-192.png
|       |-- apple-touch-icon.png
|       |-- assets/                     // Images, fonts, icons, sounds, etc.
|           |-- logo.png
|           |-- background.png
|
|--- src/                               // JavaScript, CSS, components
|       |-- components/                 // JavaScript components, one file per component
|       |       |-- home.js
|       |       |-- about.js
|       |       |-- contact.js
|       |       |-- navbar.js
|       |
|       |-- router.js                   // Routing logic
|       |-- app.js                      // Main app entrypoint
|       |--styles/                      // CSS or SCSS files    
|               |-- main.css        
|               |-- components.css
|
|-- .gitignore
|-- package.json                        // If using npm for tooling or build
|-- README.md


## Style Guide 

### Comments
**Within Code Blocks in Markdown files:** Adhere to the convention for respective programming language.

**Within a Diagram in Markdown files:** Given this project's purpose as a JavaScript learning project, use single line // JavaScript comments.

## Naming Conventions
**JavaScript:** Use Vanilla JavaScript naming conventions:
    - files/directories: `kebab-case`
    - functions/components/methods/object properties: `camelCasei`
    - class names/constructor functions: `PascalCase`
    - constants: `UPPER_SNAKE_CASE`
