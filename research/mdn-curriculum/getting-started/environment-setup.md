# Environment setup
https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Environment_setup


## Notes
- https://www.theverge.com/2024/1/25/24050478/apple-ios-17-4-browser-engines-eu
    - Apple only allowed other browser engines than WebKit in iOS 17.4  (Jan (March 2024) after the EU stipulated in the Digital Markets Act (DMA) that users should be allowed to uninstall preinstalled apps that "steer them to the products and services of the gatekeeper".
    - Safari is based on the WebKit browser engine, Chromium browsers are based on the Blink engine, and Firefox is based on Gecko.
- Website folder structure
    - `index.html`
    - `images/`
    - `styles/`
    - `scripts/`
- Best practices for naming files
    - hyphens to represent spaces
    - all lowercase
- Best practices for URLs
    - https://developers.google.com/search/docs/crawling-indexing/url-structure
    - https://en.wikipedia.org/wiki/URI_fragment
        - fragments is what comes after "#"
        - they are used by the browser, not the server
        - never sent to the server
        - search engines ignore fragments
        - dont use fragments to change the content of a page
    - use readable words for url paths
    - use hyphens to separate words and underscores to denote concepts that should be kept together (`format_date`)
    - avoid the use of session IDs in URLs, prefer cookies instead
- why does Windows use backslashes for directory separators instead of forward slashes like UNIX?
    - MSDOS 1.0 used forward slashes for switches (like command line flags), inherited from Digital Equipment Corporation
    - When MSDOS 2.0 introduced directories, they used a backslash as the directory separator
    - There was (is?) an undocumented config option that let you use hyphens for switches and forward slashes for directory separators
- `curl`
    - curl -L follows redirects
    - curl -I outputs headers
- awk '{ print "https://developer.mozilla.org" $2 }' - takes the second part of stdin

## Next steps
- None!
