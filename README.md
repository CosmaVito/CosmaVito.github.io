# cosmavito.github.io

Source of my personal page, published with GitHub Pages at https://cosmavito.github.io.

One static page written by hand in HTML and CSS. There is no JavaScript, no cookie and no tracking. Fonts are self-hosted: Archivo and B612 Mono, both under the SIL Open Font License (see `fonts/`). The only external request is my GitHub avatar.

## Checks

Every push runs HTML validation and an accessibility check with axe, see `.github/workflows/check.yml`.

## Known limits

GitHub Pages does not allow custom HTTP response headers. The Content Security Policy is set with a meta tag, so directives that only work as headers, such as `frame-ancestors`, are not applied.

## License

Code under the MIT license. Text and photo © Cosma Vito Iaffaldano. Fonts under their own OFL licenses.
