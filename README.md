# code-examples
code snippets from different languages

## html-5
- notes:
  - elements have default css settings
- structural elements:
  - open and close html: `<html></html>`
  - style (for css): `<style></style>`
  - metadata: `<head></head>`
  - body (actually displayed): `<body></body>`
  - title (used within metadata): `<title></title>`
  - header: `<h1></h1>`
  - paragraph: `<p></p>`
  - new section (start from a new line): `<div></div>`
  - group inline-elements: `<span></span>`
  - hyperlink: `<a href="https:google.com"> Click me! \a>`
    - target: open page in new tab / window
  - ordered list: `<ol></ol>`
  - unordered list: `<ul></ul>`
  - list item: `<il></il>`
- semantic elements (these allow you split structural elements in different sections):
  - header: `<header></header>`
  - article: `<article></article>`
  - figure: `<figure></figure>`

## css (cascading style sheet)

- notes:
  - separates style information from the structure of pages
- syntax:
  ```{css}
  [element-selecter] {
    [element-attribute]: [value];
  }
  ```
- an example:
  ```{css}
  body {
    background: white;
  }

  li {
    padding-bottom: 6px;
  }
  ```
- to refer to a class: `[html-element].[class-name]` or just `.[class-name]`
- how to target a specific html element (use classes in favor of ids)
  - html:
    ```{html}
    <p class='big'> This is supposed to look big. </p>
    ```
  - css:
    ```{css}
    p.big {
      font-size: 50px
    }
    ```
























