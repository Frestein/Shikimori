# Ryoumori
Ryoumori is a custom theme for the Shikimori anime and manga tracker. This documentation explains how to compile the Ryoumori theme from source using Sass.

## Prerequisites

Before you can compile the Ryoumori theme, you need to have the following software installed on your computer:

- Node.js
- bun

## Installation

To compile the Ryoumori theme, follow these steps:

1. Clone the Ryoumori theme repository from GitHub: `git clone https://github.com/Frestein/Ryoumori.git`
2. Navigate to the theme directory: `cd ryoumori`
3. Install the required dependencies using bun: `bun install`
4. Compile the SCSS files to CSS using the Sass compiler: `bun run build`

## Usage

```
@import url('https://cdn.jsdelivr.net/gh/Frestein/Ryoumori@main/css/ryoumori.min.css');
```

## Customization

Ryoumori uses Sass for its stylesheets, which makes it easy to customize the theme. To customize the theme, edit the variables in the scss/ryoumori.scss file. You can change colors, fonts, and other aspects of the theme to suit your preferences.

After making changes to the variables, run `bun run build` to rebuild the theme.

## Contributing

Contributions to Ryoumori are welcome! If you find a bug or want to suggest an improvement, please open an issue on GitHub. If you want to contribute code, please submit a pull request.

## License

Ryoumori is licensed under the ISC license. See the [LICENSE](LICENSE) file for details.

## Support

If you have any questions or need help with Ryoumori, please open an issue on GitHub 
