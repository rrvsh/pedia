# Your first website
https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website

- Firefox design system: https://acorn.firefox.com/latest/home/acorn-aRSAh0Sp
- https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Colors/Color_format_converter
- Web safe fonts: generally available across all systems
    - sans-serif: arial (or helvetica), trebuchet ms (not on mobile), verdana
    - serif: Georgia, Times New Roman
    - monospace: Courier New
- HTML syntax:
    - doctype: `<!doctype html>` preamble
        - https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Quirks_mode_and_standards_mode
        - pages used to be written in two versions, for netscape navigator and for internet explorer
        - when W3C web standards introduced, browsers introduced:
            - quirks mode to emulate behaviour in navigator 4 and IE5
            - no quirks (full standards) mode, the desired behaviour of the modern HTML and CSS spec
            - limited quirks (almost standards) mode, very small number of quirks
        - `<!doctype html>` will ensure the browser uses no-quirks mode to render the site
    - `<html>`: root element, all other elements must be descendants of it
        - should include one `<head>` element followed by one `<body>` element
        - should include the `lang` attribute containing BCP 47 language tag
    - `<head>`: stuff to include that isnt the content you are showing to the pages viewers
        - metadata like title, scripts, style sheets
        - `<meta charset="utf-8">`, sets character set to the utf-8 character encoding, which can represent any standard unicode character
            - UTF-8 supersedes ASCII, which uses 7-bit to represent 128 characters, and the first 128 UTF-8 characters match the first 128 ASCII characters - all ASCII text is valid UTF-8
        - `<meta name="viewport" content="width=device-width">`: viewport element, ensures page renders at the width of the browser viewport
            - prevents mobile browsers from rendering pages wider than the viewport hen shrinking them down (?)
    - `<body>` represents the content of the html document
    - `<img>` takes:
        - src attribute: path to the image file
        - alt attribute: descriptive text for users who cannot see the image
    - empty or void elements do not have contents or closing tags
    - HTML comments `<!--` and `-->`
    - HTML contains `<h1>` to `<h6>`
    - `<p>` is for paragraphs
    - list can be unordered `<ul>` or ordered `<ol>`
    - links use the anchor element `<a>` with the href attribute containing the link to the web address
        - href stands for hypertext reference


## 16 feb 26

- idea for project: I went through the MDN web docs for two weeks and made a website!
- go through and collate empty fields like "what does do do:" and "who do you come:"
- only then ideate
- then implement into site
- <https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website>
    - transliterating this into action items for the website
    - filling out those action items with what i want for the site
    - putting the content and HTML elements into the site

- for the website:
    - future ideas:
        - the image shoudl be on a slideshow, showing the more SFW image first then switching to the rest of subsequent page visits
    - action items:
        - what does it do: look cool and make me look cool
        - what is it about: me, a young aspiring hacker
        - what information are you presenting?: information about me and my published works
        - what color palette: #4F000B, #B48100, #2274A5 from coolors.co
        - what font: courier new
        - header element children are vertically stacked
    - js learning points: 
        - window.location.pathname to check route
        - "incline-block" display for children, display: flex for parent,   justify-content: center; to get center aligned inline children

- next up is <https://developer.mozilla.org/en-US/docs/Learn_web_development/Core>
