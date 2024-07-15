# intergrav/fonts

[![NPM Version](https://img.shields.io/npm/v/@intergrav/fonts)](https://www.npmjs.com/package/@intergrav/fonts) [![jsDelivr hits (npm)](https://img.shields.io/jsdelivr/npm/hm/@intergrav/fonts)](https://cdn.jsdelivr.net/npm/@intergrav/fonts/) [![GitHub Repo stars](https://img.shields.io/github/stars/intergrav/fonts)](https://github.com/intergrav/fonts)

A fast, open-source CDN for open-source fonts. You can view available fonts in the [`/serve`](https://github.com/intergrav/fonts/tree/main/serve) directory. More fonts will be added later. If you have any suggestions for general improvements or fonts, feel free to open an issue.

Typically, web developers have two main methods for using custom fonts on their websites:

1. Hosting font files on the same server as the website. This method provides all control over font hosting, but it will usually result in slower loading times and increased server load, especially in some areas of the world.

2. Using a central font service, such as Google Fonts or Adobe Typekit. This method is very easy, but if the service ever experiences downtime or slowdowns, it can negatively impact the user experience.

In comparison, intergrav/fonts offers several advantages:

- intergrav/fonts serves font files through jsDelivr's global content delivery network. jsDelivr uses [multiple CDNs](https://www.jsdelivr.com/network/infographic) for delivery, ensuring that fonts are delivered quickly and reliably regardless of user location.

- intergrav/fonts is fully open source, so anyone can contribute to its development and improvement. This includes requesting new fonts or making improvements to files. You can also fork it if you want to start your own project.

- intergrav/fonts exclusively serves open source fonts. By avoiding proprietary or licensed fonts, you can avoid any potential restrictions through licensing.

## Importing

To use the fonts provided by intergrav/fonts, you have to import the CSS file in your project. There are two ways to do this:

### CSS Import

In your CSS file, you can import the font CSS content using the `@import` rule:

```css
@import url("https://cdn.jsdelivr.net/npm/@intergrav/fonts@1/serve/inter.min.css");
```

### HTML Link

Alternatively, you can link the font CSS file directly in the `<head>` section of your HTML file:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@intergrav/fonts@1/serve/inter.min.css">
```

### Set a font

Remember to replace `inter` in the URL with the actual font name you want to use. Visit the [`/serve`](https://github.com/intergrav/fonts/tree/main/serve) directory for fonts that you can use. You can [open an issue](https://github.com/intergrav/fonts/issues) if you need a font to be added, but remember that this project only serves open-source fonts.

If you're curious, the `.min` in the link means to ask jsDelivr to minify the file using [clean-css](https://github.com/clean-css/clean-css). It often significantly decreases the file's size at no cost, so I recommend using it.

## Credits

- [xz/fonts](https://github.com/xz/fonts) is the main inspiration for this project
