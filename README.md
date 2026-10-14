# cosmavito.github.io

Source of my personal page, published with GitHub Pages at https://cosmavito.github.io.

One static page in HTML, CSS and inline SVG, with no build step. It uses no JavaScript. There are no cookies and no tracking. Fonts are self-hosted: Archivo and B612 Mono, both under the SIL Open Font License (see `fonts/`). The only external request is my GitHub avatar.

The interactive parts work without JavaScript as well: the accordions are `<details>` elements, the filters and the assembled view are radio buttons and a checkbox read by `:has()`, and the section index follows the scroll with CSS scroll-driven animations where the browser supports them.

## Checks

Every push runs HTML validation and an accessibility check with axe, see `.github/workflows/check.yml`.

## Known limits

GitHub Pages does not allow custom HTTP response headers. The Content Security Policy is set with a meta tag, so directives that only work as headers, such as `frame-ancestors`, are not applied.

## License

Code under the MIT license. Text and photo © Cosma Vito Iaffaldano. Fonts under their own OFL licenses.
