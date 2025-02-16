# HTML basics: Introduction

## Introduction

### Outline

- What is markup?
- How do Markdown and HTML represent markup?
- Your First HTML Page explanation of doctype, meta etc.

### Guidelines

- Focus on content, not on style!
- Knowing everything is not necessary!
- VS Code: Emmet, "html:5"
    - `mkdir xyz` -> `cd xyz` -> `code .`
    - Clean work environment
- Altenative online environment: https://codesandbox.io/

### Documentations

- https://www.w3schools.com/
- https://devdocs.io/
- https://htmlcheatsheet.com/

### Live Server

- Live Server configuration

### Tags

- Tags: `<tagname> ... </tagname>`

- Headings `<h1> ... </h1>` (only one)
- Paragraphs `<p> ... </p>` (block level elements)

- Whitespaces in VS Code and browser

- VS Code: "lorem50", Alt+Z (text format),
- VS Code: `p*3`, `(p>lorem5)*3`

- Browser: development tools

- Italic: `<em> ... </em>` - and not `<i> ... </i>`
- Bold: `<strong> ... </strong>` - and not `<b> ... </b>`

### Lists

- `<ul> ... </ul>`, `<ol> ... </ol>`
- `<li> ... </li>`
- VS Code `ul>li*6`

### Images

- VS Code: `img`
- `<img src="" alt"">` - we do not need to close images
- Relative Paths: `src`, `"images/profile.jpg"`, `"./images/profile.jpg"`, `"../images/profile.jpg"`
- URL path (link)
- Accessibility: `alt`
- Size: `width="250" height="300"`. Don't distort the aspect ratio!

### I.D's and Links

- Tag ID: e.g. `id="skill-table"`
- In the browser: e.g. `http://127.0.0.1:5500/index.html#skill-table`

- Internal Links:
    - Same file: e.g. `<a href="#skill-table">My Programming Skills</a>`
    - Another file: e.g. `<a href="projects.html"My Projects</a>`
    - Another file with an anchor: e.g. `<a href="index.html#skill-table">My Programming Skills</a>`
    - Image in another project directory: e.g. `<a href="../Images/profile.jpg">Me</a>`

- External Links: `<a href="http://www.google.com">Find Me...</a>`

- In new tab: `target="blank"`

### Forms

    Hello
    -