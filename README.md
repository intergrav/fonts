# intergrav/fonts

[![NPM Version](https://img.shields.io/npm/v/@intergrav/fonts)](https://www.npmjs.com/package/@intergrav/fonts) [![jsDelivr hits (npm)](https://img.shields.io/jsdelivr/npm/hm/@intergrav/fonts)](https://cdn.jsdelivr.net/npm/@intergrav/fonts/) [![GitHub Repo stars](https://img.shields.io/github/stars/intergrav/fonts)](https://github.com/intergrav/fonts)

A fast, open-source CDN for open-source fonts. Inspired by [xz/fonts](https://github.com/xz/fonts).

You can view available fonts in the `/serve` directory. More fonts will be added later. If you have any suggestions, open up an issue.

Typically, web developers use custom fonts on their websites using one of two methods:

- hosting font files on the same server as the website
- using a central font service, such as Google Fonts or Adobe Typekit

intergrav/fonts, by comparison:

- serves font files through jsDelivr's global content delivery network
- is fully open source and only serves open source fonts

## Importing

In your CSS you could do:

```css
@import url("https://cdn.jsdelivr.net/npm/@intergrav/fonts@1/serve/inter.min.css");
```

Or in your HTML's `<head>` you could do:

```html
<link
	rel="stylesheet"
	href="https://cdn.jsdelivr.net/npm/@intergrav/fonts@1/serve/inter.min.css"
/>
```

Replace `inter` with the font name, of course.
